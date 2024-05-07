# 🎬 Mission Briefing: Project Anime API 🎬

### Mission Objective:
Your mission, should you choose to accept it, is to develop an API capable of supplying crucial details for Japanese anime content to online streaming platforms. This API will serve as the backbone for delivering rich metadata, ensuring an immersive and seamless experience for anime enthusiasts worldwide.

### Mission Scope:
Your task involves creating a robust API that can efficiently handle requests from streaming platforms, providing comprehensive information on a vast array of Japanese anime titles. From basic details such as title, genre, and release date, to more intricate data like synopsis, episode count, and ratings, the API must be capable of delivering an extensive range of metadata with speed and accuracy.

### Mission Execution:
Your expertise in software development, API design, and data management will be crucial for the success of this mission. Collaborate closely with stakeholders to gather requirements, prioritize features, and ensure alignment with the objectives of online streaming platforms. Employ industry best practices, innovative technologies, and meticulous attention to detail to deliver an API that exceeds expectations and sets new standards for anime content delivery.

🕶️ This message will self-destruct in 5... 4... 3... 2... 1... 🕶️

Feel free to use the trello board to organise your work on the project.
You can start by creating one card for each task.

## TODOs

0 - Add a new private repository for the project into your github account [  ]

1 - Add me as a collaborator of the project [  ] # for the code reviews

2 - Create a minimal flask api using link in reference

3 - Make request using postman to the API endpoint created in step 2

4 - Create a python file to play with sqlalchemy (using example provided)

5 - Import data from a csv to sqlite database using SQLAlchemy with a python script [  ]

7 - List the first 100 animees sorted by release date with FlaskSQLAlchemy + postman test [  ]

8 - Get all details about "Death Note" + postman test [  ]

9 - Add an animee not existing in the database + postman test [  ]

10 - Update partially an animee + postman test [  ]

11 - Update completely an animee + postman test [  ]

12 - Delete an animee + postman test [  ]

13 - Generate a token for a client + postman test [  ]

14 - Only authenticated clients can interact with the API + postman test [  ]

## Docs

To complete this project, a link to a documentation is expected to help any clients to interact with the API.

## Test

In order to test that the API is responding accordingly, you can also implement automated tests use pytest.
At least one integration test is required for each request.

## Resources
- [Flask - A minimal API](https://sentry.io/answers/return-json-in-flask-view/) # just to reproduce a minimal api application with flask and make your first postman request to it on your local
- [Postman Getting Started](https://www.youtube.com/watch?v=MFxk5BZulVU)
- [SQLAlchemy - Getting Started](https://docs.sqlalchemy.org/en/20/orm/quickstart.html) # to understand how to use sqlalchemy to create a database from python classes, insert data and make queries to retrieve data (standalone test file)
- [Dict Reader](https://docs.python.org/3/library/csv.html#csv.DictReader)
- [Integration library Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/3.1.x/) # to understand how to use flask sqlalchemy which is a glue between flask and sqlalchemy to write and read data via flask views (functions)
- [Generate documentation for the endpoints with swagger and sqlalchemy](https://github.com/thomaxxl/safrs)
- [Flask Real life example](https://github.com/gothinkster/flask-realworld-example-app) # if you are lost about the structure of the project you can get inspired by this project for yours (specially for the tests)
- [JSON Web token: Theory](https://4geeks.com/lesson/what-is-JWT-and-how-to-implement-with-Flask)
- [JSON Web token library for flask](https://github.com/vimalloc/flask-jwt-extended)
- [Prevent from copy pasting token for each endpoint](https://community.postman.com/t/how-to-automatically-set-a-bearer-token-for-your-postman-requests/10126/17)
- [Obey the goat pdf](https://englishonlineclub.com/pdf/Test-Driven%20Development%20with%20Python%20(Second%20Edition)%20%5BEnglishOnlineClub.com%5D.pdf)
- [Obey the goat amazon link](https://www.amazon.co.uk/Test-Driven-Development-Python-Selenium-JavaScript-x/dp/1491958707/ref=as_li_ss_tl?ie=UTF8&qid=1502337608&sr=8-2&keywords=tdd+python&linkCode=sl1&tag=obethetesgoa-21&linkId=472f4eea099a845ca709cffeee73d909)
- [Git](https://www.youtube.com/watch?v=hwP7WQkmECE)
