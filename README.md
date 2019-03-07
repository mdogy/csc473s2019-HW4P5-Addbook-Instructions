# csc473s2019-HW4P5-Addbook-Instructions
## HW4: Problem 5, CSC 473 Spring 2019
Instructions for problem HW4P5 in csc473s2019

You are going to study my lovely [react todo app on github](https://github.com/mdogy/react-todo-app) and build an address book app which is similar. It doesn't need to look exactly the same but the address should be on some kind of cards. You should use react-bootstrap as well as react. It should have a form at the bottom where you can add new addresses. It should include something on each card, lets say a little garbage can, to delete and unlike on my lovely page, it should ask you to confirm. The cards and the list should be react functions not component classes. Only the top level component of the app should have state ... everything else props only. The handlers should live in the top class and pointers passed down in to the compoent functions similar to how I did it. Don't forget to use create-react-app to get started.

The main "twist" here is that you should have a search box sub-component at the top right of your main component. As you type, it should try to match any partial string in any of the fields. Only those cards that have what you typed (case insensitive) as a substring in any of the fields should be displayed. It should be live so as you type it filters the list. If the box is empty, everything shows.

At the start the names below should show up.


```javascript
[
    {
        FirstName: "Cathy" ,
        LastName: "Pierce",
        Birthday: "9/14/1996",
        Telephone: "200-910-8132"
    },
    {
        FirstName: "Alfonso",
        LastName: "Cooley",
        Birthday: "8/10/1973",
        Telephone: "200-657-9362"
    },
    {
        FirstName: "Victor",
        LastName: "Gordon",
        Birthday:  "8/3/1970",
        Telephone: "200-661-9407"
    },
    {
        FirstName: "Colleen",
        LastName: "Wright",
        Birthday: "10/28/1967",
        Telephone: "200-250-7949"
    },
    {
        FirstName: "James",
        LastName: "Johnston",
        Birthday: "5/11/1972",
        Telephone: "200-645-3176"
    },
    {
        FirstName: "Anna",
        LastName: "Reyes",
        Birthday: "9/10/1975",
        Telephone: "200-707-8670"
    }
]
```
