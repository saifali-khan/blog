Title: 
Building a web application using elixir and phoenix

Introduction:
building a web application using functional programming language will be a great experience. In this blog we are going to explore the process of building a powerful web application using Elixir and Phoenix, with a focus on integrating the GitHub User API. By usig the productivity of the Phoenix framework, and the wealth of data available through the GitHub User API, we can create an application that showcases user details with ease and elegance. The  goal of this project is to provide a user-friendly interface where you can enter a GitHub username through an input tag. Once submitted, the application will start fetching the user's profile details from the API. These details are then rendered and displayed in HTML format using the Phoenix framework LiveView .


Overveiw:
1. Elixir: Elixir is a functional programming language built on the Erlang virtual machine, offers a unique set of features that make it an excellent choice for developing scalable and reliable applications. With its lightweight processes, fault-tolerant design, and emphasis on concurrency, Elixir enables the creation of high-performance web applications. Elixir's syntax is clean, expressive, and elegant, which can enhance the productivity and satisfaction of developers.

2. Phoenix framework: Phoenix is a powerful web development framework that capitalizes on the productivity of the language. Following the Model-View-Controller (MVC) architectural pattern, Phoenix provides real-time updates, WebSocket communication through channels, and a supportive community, enhancing the development experience. Phoenix LiveView allows for real-time, interactive experiences without the need for JavaScript, making it an excellent choice for developing dynamic user interfaces.

3. Github API: To enhance the functionality of our web application, we will integrate the GitHub User API. This API provides an abundance of information about GitHub users, including usernames, repositories, followers, and activity. By utilizing this data, we can craft a compelling user interface that showcases comprehensive user details, thereby highlighting their GitHub presence and contributions.

4. HTTPoison library: HTTPoison is the http client for elixir, the HTTPoisn module can be used to issue http requests and parse http responses to arbitary urls. we are using HTTPoison library to fetch user's information from the github API.

5. Poison library: The Poison library is a popular JSON (JavaScript Object Notation) encoding and decoding library for the Elixir programming language. we are using Poison library to decode the response data from github API.

6. styling: we are going to use css to style the UI, like fonts, colors, spacing, etc. we are also using media querries for the responsive designs of the application to be fit in every screen size.

7. deploying: I have used fly.io to deploy my web application. fly.io offers a global edge computing platform, ensuring optimal performance and low latency for users worldwide.


key topics covered:
1. Introduction to Elixir and Phoenix and their benefits for web application development.
2. Overview of the GitHub User API and its capabilities for fetching user information.
3. Setting up the Elixir and phoenix application.
4. Implementing GitHub User API integration in our web application using HTTPoison.
5. Decoding the response json data using Poison library
6. Designing an HTML user interface to display user details effectively.
7. styling the UI using CSS and how to use media querries.
8. deploying the application on fly.io.


conclusion:
Building a web application using Elixir and Phoenix, with the integration of the GitHub User API, has been an exciting experience. Throughout this blog, we have explored the power and elegance of Elixir as a functional programming language and the productivity boost provided by the Phoenix framework. By using the github user API we were able to fetch users details, such as followers, repositories, etc. with the help of HTTPoison and Poison we were able to create a fetch request on API, and also be able to decode the json data. we used CSS to style the application for better UI, and also the use of media querries allowed our application to adapt seamlessly to various screen sizes and devices. And finlly we deployed our application of fly.io, to ensured that our web application was accessible to users worldwide and could handle high traffic demands with ease.
