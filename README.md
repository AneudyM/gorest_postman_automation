# Go REST API Automation Postman Collection

This repository contains a Postman Collection and environment exports for the
API Automation of the `/users` endpoint. It covers tests for basic functionality
such as creating, updating, and deleting users as wel as some error validations.
Once you get this collection, setting up the automation is easy. You'll only need
to retrieve an access token from Go REST and Run the collection.

## Installation

1. Clone the repository <br>

`> git clone git@github.com:AneudyM/gorest_postman_automation.git`

3. Import the collection and environment variables to Postman <br>

![img](https://user-images.githubusercontent.com/8399767/155727655-e97182bb-d7e5-4fdd-a7de-35d794709619.png)

Select **Folder** and then **Choose folder from your computer**. You will have to navigate
to and select the folder of your cloned repository containing the collection and environment
variables.

![img_2](https://user-images.githubusercontent.com/8399767/155728057-8d3bb329-4d9a-424c-8c8e-bf9d57c046cb.png)

Postman will automatically pick both files for import. Just click on the **Import** button.

![img_3](https://user-images.githubusercontent.com/8399767/155728154-f414f6fe-82bf-45e1-8d41-cc2d24d8272c.png)

3. Request an access token from Go REST

To request an access token from Go REST you can use this url: `https://gorest.co.in/consumer/login`

4. Configuring your access token

Once you obtain your access token, click on the **Environment** button and select the **TecBeats**
environment. You will see the `access_token` environment variable to the right. Set the **CURRENT VALUE**
field with your access token.

![img_4](https://user-images.githubusercontent.com/8399767/155728194-1587a697-8e2b-4a5f-a8d3-b1205e0c924e.png)
