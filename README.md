# Currency Converter

Hi! This is a currency converter app that uses an API to fetch data and uses it. In this app you can **convert money between 7 currencies**. 

Since the used API is free, it is refreshed in every 60 minutes and has a history of 6 days. Because of these limitations I only update local storage(json-server) every 60 minutes. And also I do not store the data between the last update time and the current time, I only get the real time data.

I used **Vue3, Vuex, Axios, TailwindCSS, JSON-server** in this project.

If you want to try it out you can simply click **Code > Copy Icon** on the top right corner, go to your Terminal/Cmd etc. and paste this:

    git clone THIS_REPOSITORY_LINK

After cloning process is finished, you **must** install the npm in order to run.

    npm install
    
Then, you are ready to give it a shot! In order to run json-server you must type:

    npm run db:serve
    
Only then, you must type:

    npm run serve
    
and you will see the project in your browser!

![image](https://user-images.githubusercontent.com/40501852/152238721-7f4c1eb5-b072-4dfd-bfc8-68398c36b7f9.png)
