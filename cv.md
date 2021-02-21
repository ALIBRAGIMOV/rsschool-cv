**Ali Ibragimov**
============
Moscow, Russian / +7-925-937-15-88 / +7-978-616-96-21/ Telegram - @lllimited / ialimagomed@mail.ru
# **Work Experience**
**Somonmart** 

Moscow, Russia

Front-end Developer for http://somonmart.ru/					  April 2020 – Current

* Developing responsive web pages (HTML, CSS).
* Collaborated with the frontend and backend teams on E-commerce platform developing.
* Using cutting edge technologies JavaScript, CSS (SASS), Material UI, Node.js (Express, Mongoose).
* SPA development with React.js, including SSR (Next.js).
* Internal SEO optimization.
* Backend and API development with Node.js (Express). 
* Code review and fixing bugs.
* API testing. 


# **Education**

### **Financial University under the Government of the Russian Federation	Moscow, Russia**

***Master of Science***
 
Business Analysis & Audit -
2018 / 2020

### **Financial University under the Government of the Russian Federation	Moscow, Russia**

***Bachelor of Science in Finance*** 

Taxes and Taxation -
2015 / 2018
# **Code examples**

[GitHub - Ali Ibragimov ](https://github.com/ALIBRAGIMOV)


```TypeScript
export const requestUsers = (currentPage = 1, pageSize: number): ThunkType => {

    return async (dispatch, getState) => {
        dispatch(actions.setCurrentPage(currentPage))
        dispatch(actions.toggleIsFetching(true))

        const data = await usersAPI.getUsers(currentPage, pageSize);
        dispatch(actions.toggleIsFetching(false))
        dispatch(actions.setUsers(data.items))
        dispatch(actions.setUsersTotalCount(data.totalCount))
    }
}
```



**Additional Skills**
============
Languages: English – intermediate; Russian – native


Technical Skills: HTML, CSS, Javascript/TypeScript, React/Redux/Next.js, Vue/Vuex, Node.js, Webpack, MongoDB, SQL, Ajax, OOP, Babel, MS (Excel, PowerPoint, Word, Access), Bloomberg, SAP