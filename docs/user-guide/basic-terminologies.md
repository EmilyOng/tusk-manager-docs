---
sidebar_position: 1
---

# Basic Terminologies

When you first enter the application, you will see this authentication page.

![Authentication](/img/user-guide/basic-terminologies/authentication.png)

If you have an existing account, you may log in with your previous credentials (email and password). If you are new here, you may want to sign up for an account.

The password that you enter are *hashed* before being stored in the database and the authentication system is powered by the notion of JSON Web Tokens (JWT) authentication, which keeps you logged in for 24 hours.

Now, let's hop on the basic terminologies of the application.

At its very core, each *project* that you embark on has its dedicated **Board**.

A board is simply a visual interface that you can share with other **members**. Each board contains a collection of **tasks** and each task gets its own **state**. A state specifies the stage that the task is currently at, and you can create new states depending on your workflow lifecycle. What's more, you can specify tags for each task for greater granularity in managing your work. 

![Basic Terminologies](/img/user-guide/basic-terminologies/basic-terminologies.png)
