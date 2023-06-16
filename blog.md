Introduction:
Welcome to my GitHub REST API application, built using Elixir and Phoenix LiveView! In this project, I have used the power of Elixir and the Phoenix LiveView to create a interactive experience for fetching and displaying user details from GitHub's User API. 

The  goal of this project is to provide a user-friendly interface where you can enter a GitHub username through an input tag. Once submitted, the application performs some functions in the backend to fetch the user's profile details from the GitHub API. These details are then  rendered and displayed in HTML format using the Phoenix LiveView framework.

Overveiw:

1.  Elixir is built on the Erlang Virtual Machine (BEAM), which is renowned for its lightweight processes and excellent concurrency model. Elixir's actor-based concurrency model allows for efficient handling of concurrent tasks and ensures scalability, making it a great choice for applications that require high performance and responsiveness.

2. Elixir's syntax is clean, expressive, and elegant, which can enhance the productivity and satisfaction of developers. The language provides a comprehensive set of tools and libraries, along with powerful metaprogramming capabilities, enabling developers to build applications rapidly and efficiently

3. Elixir is a functional programming language that encourages immutability and data transformation through pure functions. This approach results in code that is easier to reason about, test, and maintain. Functional programming also promotes code that is less prone to bugs and offers better support for parallel and concurrent execution.

4.  Elixir's Phoenix framework is a high-performance web framework that seamlessly integrates with Elixir. Phoenix provides a foundation for building web applications with features such as routing, controllers, and views. Additionally, Phoenix LiveView allows for real-time, interactive experiences without the need for JavaScript, making it an excellent choice for developing dynamic user interfaces.

5. HTTPoison: The http client for elixir, the HTTPoisn module can be used to issue http requests and parse http responses to arbitary urls.

what i have learned from this project:

1. HTTP request: I have learned about how to make an http request on api using HTTPoison and also learned about the response's status codes

2. dealing with api: I have learned how to use rest api in elixir and how to perform a get event on api using HTTPoison for fetching the api data.

3. json decoding: I have used Poison an incredibly fast and pure eixir JSON library. to decode all the json data for rendering data in LiveVeiw.

4. Template rendering: I have learned how to render Poison decoded JSON data in html. using using phoenix template language called HEEx.

5. Navigation: I have also learned about phoenix Live navigation to navigate username which is inputs value to append beside url without refreshing the current page using push_pach/2.

conclusion:

In this blog, I have showed you about my elixir application on github's user api, to perform the functions from geting the input's value as an username to rendering the user's data like, user's name, avatar, blogs, followers, etc. we've explored how to perform http request, template rendering, and working with api's to render the json data into html templates. thank you for reading this blog.