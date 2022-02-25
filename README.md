# Go REST API Automation Postman Collection

This repository contains a Postman Collection and environment exports for the
API Automation of the Go REST site's `/users` endpoint. It covers tests for basic functionality
such as creating, updating, and deleting users, as well as error validations.
Once you get this collection, setting up the automation is easy. You'll only need
to retrieve an access token from Go REST.

## Installation

#### 1. Clone the repository

`> git clone git@github.com:AneudyM/gorest_postman_automation.git`

#### 2. Import the collection and environment variables to Postman

![img](https://user-images.githubusercontent.com/8399767/155727655-e97182bb-d7e5-4fdd-a7de-35d794709619.png)

Select _**Folder**_ and then _**Choose folder from your computer**_. You will have to navigate
to and select the folder of your cloned repository containing the collection and environment
variables.

![img_2](https://user-images.githubusercontent.com/8399767/155728057-8d3bb329-4d9a-424c-8c8e-bf9d57c046cb.png)

Postman will automagically pick both files for import. Just click on the _**Import**_ button.

![img_3](https://user-images.githubusercontent.com/8399767/155728154-f414f6fe-82bf-45e1-8d41-cc2d24d8272c.png)

#### 3. Request an access token from Go REST

To request an access token from Go REST you can use this url: `https://gorest.co.in/consumer/login`

#### 4. Configuring your access token

Once you obtain your access token, click on the _**Environment**_ button and select the _**TecBeats**_
environment. You will see the `access_token` environment variable to the right. Set the _**CURRENT VALUE**_
field with your access token.

![img_4](https://user-images.githubusercontent.com/8399767/155728194-1587a697-8e2b-4a5f-a8d3-b1205e0c924e.png)

Make sure to save your changes.

## Running the tests

To run the tests, select the _**TecBeats API Automation Challenge**_ collection from the list of
collections. Then, click on the _**Run**_ button to the right.

![img_5](https://user-images.githubusercontent.com/8399767/155729323-6c4aabc8-724d-438e-ab80-62ad51eb54c7.png)

The Test Runner should show all the available tests in the collection. You can select which ones
you want to include in the run. Click on _**Run TecBeats API Automation Challenge**_ button.

![img_6](https://user-images.githubusercontent.com/8399767/155731470-6e9fb2d2-d4a7-46b2-88d4-86678320b5f7.png)

Test results should look like the following:

![img_7](https://user-images.githubusercontent.com/8399767/155731532-6f140ebc-14de-409c-bccd-1d62a41f5939.png)

## Troubleshooting

1. Make sure you have the TecBeats Environment active

If you encounter the following error, please, make sure you have the TecBeats Environment
active.

![img_10](https://user-images.githubusercontent.com/8399767/155731668-9a248e6b-1a05-49bc-bc5d-8781ad05e346.png)

2. Make sure your access token has not expired, and it is set correctly

If all of your tests are failing, please, make sure your access token has not expired
and that it was set correctly in Postman.

![img_11](https://user-images.githubusercontent.com/8399767/155731678-04c27ffa-4a66-4e1a-9ffb-ca7f8aeeb084.png)
