APIARY



**Index:**
1.Creating an account for Apiary/using Github
2.Using the Editor
3.The Inspector
4.Linking project to Github
5.Testing Apiary with Swagger/Open API
6.Unit Testing using Dredd
7.Apiary Help



There are two ways to login/create an APIARY account.

Go to this link : https://apiary.io.

![image](https://user-images.githubusercontent.com/34638862/123772932-df48c580-d8e9-11eb-85f4-02701827b345.gif)

Option 1: 
Now if you already have a Github account you can use your git account credentials to login to Apiary.

![image](https://user-images.githubusercontent.com/34638862/123772983-ea035a80-d8e9-11eb-83d5-fdc8f333fa66.gif)

A 6 digit verification code will be sent to your email. Please enter the code to verify and Login. 

Option 2:
Incase you do not have a Github account you can use other ways to login by using the “Sign Up free with Email” option.
When you click on that option it takes you to this page. You can create a new account here.

![image](https://user-images.githubusercontent.com/34638862/123772962-e5d73d00-d8e9-11eb-924b-6fbe77024fa8.gif)

Click on Create a new API Project

![image](https://user-images.githubusercontent.com/34638862/123773046-fdaec100-d8e9-11eb-9b08-3aa32062c1ec.gif)

Now there are two ways to create an API in Apiary. We can use a API Blueprint that uses the markdown language to create apis. Click on “Show format example” option. 

A sample markdown code is shown below.

![image](https://user-images.githubusercontent.com/34638862/123773083-069f9280-d8ea-11eb-9187-f6a3d98b1dd8.gif)

Or, if you click on Swagger and then click on “Show format example” option. You will see a swagger example.

![image](https://user-images.githubusercontent.com/34638862/123773062-02737500-d8ea-11eb-8b9c-ae722e44ecc3.gif)

Lets select the option API Blueprint and click on “Save and start using apiary”.

**Using the Editor:**

You are already presented with a default api displayed on the left panel. On the right panel we will see the implementation of this api.

![image](https://user-images.githubusercontent.com/34638862/123773113-0d2e0a00-d8ea-11eb-81bb-2682be88326b.gif)

Now for our easy understanding we will use another simple api written in the markdown format.
Please download the file from this below Object Storage link:
https://objectstorage.ap-tokyo-1.oraclecloud.com/n/nr1gqrdncp4f/b/bir_training/o/customerList_API

After downloading please open the file, copy the code and replace it with the existing code as shown below in the left side panel.

Once the new code is pasted it would look like this:

![image](https://user-images.githubusercontent.com/34638862/123773152-13bc8180-d8ea-11eb-9375-5b3a929560fa.gif)

Click on the Save button on the top right corner to save the updated api code.

There is an option to use swagger/open api instead of using a markdown code. We will see that later.

Coming back to the Blueprint apiary “Editor” page. Click on the List All Questions options to load the Testing Console.

![image](https://user-images.githubusercontent.com/34638862/123773187-1a4af900-d8ea-11eb-814a-e7a16c5a20cb.gif)

Select the Mock Server from the list and click on “Call Resource”.

![image](https://user-images.githubusercontent.com/34638862/123773219-1fa84380-d8ea-11eb-9462-58b56c9fe219.gif)

This would display the response generated from the created API.

![image](https://user-images.githubusercontent.com/34638862/123773233-233bca80-d8ea-11eb-8783-8e486a76e602.gif)

Apiary has already provided us with a mock URL that can be tested to see if we are getting the correct response or not.

![image](https://user-images.githubusercontent.com/34638862/123773270-29ca4200-d8ea-11eb-901a-0fffd163fc0d.gif)

Sample: https://private-3e6c4a-customerlist2.apiary-mock.com/mylist
To test this request you can use your browser or any tool like Postman.


In Browser:
Paste this URL on a browser window and check if the response is returned.

![image](https://user-images.githubusercontent.com/34638862/123773324-38185e00-d8ea-11eb-9902-2fc1c26c7d7d.gif)

We can see that the response is being correctly returned. 

In Postman:

![image](https://user-images.githubusercontent.com/34638862/123773369-3ea6d580-d8ea-11eb-84ad-50780ee2bd1b.gif)

Now interestingly we can also generate code for different languages for the created API. To do that we click on the “Switch to Example” button.

This opens up a dark colored window where you have the option to select the language/code of your choice.
This supports all major code types like Javascript, node js, python, Perl, PHP etc.
 
You can directly copy the code from here and paste it into your working project.

![image](https://user-images.githubusercontent.com/34638862/123773419-46ff1080-d8ea-11eb-9e5e-77557d2060df.gif)

**The Inspector:**

We can click on the “Inspector” option on top to view the history of all calls made to any api.

![image](https://user-images.githubusercontent.com/34638862/123773463-4d8d8800-d8ea-11eb-8658-ab849f69c03a.gif)

We can click on any resource request to get more details on this request.

![image](https://user-images.githubusercontent.com/34638862/123773516-55e5c300-d8ea-11eb-8755-caac67d73811.gif)

**Linking your project to Github:**

We can link our project to Github by clicking on the “Link this project to Github” option on the top left.

![image](https://user-images.githubusercontent.com/34638862/123773558-5ed69480-d8ea-11eb-9ad8-f1380c1117da.gif)

This will take you to this Setting’s page. Navigate to the end of the settings page to find the Link this project to Github option.

![image](https://user-images.githubusercontent.com/34638862/123773587-65650c00-d8ea-11eb-85df-5b485f80f335.gif)

Now before Clicking on “Link this project to Github” button. We need to make sure we have an empty repository created in Github.

Go to your Github account and create an empty repository.

![image](https://user-images.githubusercontent.com/34638862/123773665-76158200-d8ea-11eb-8b4a-595991d90e8d.gif)

Search for that repo in “Link your Github repo” and your git repo should be visible as shown below.


Then we need to click on “Connect” and enter the commit message.

![image](https://user-images.githubusercontent.com/34638862/123773712-7ca3f980-d8ea-11eb-8697-d34cd4e1282b.gif)

Once done it will show a confirmation like this.

![image](https://user-images.githubusercontent.com/34638862/123773788-86c5f800-d8ea-11eb-9819-5b6660593984.gif)

If we now go to Github, we should be able to view our project. We can see a file called apiary.apib

![image](https://user-images.githubusercontent.com/34638862/123773830-8cbbd900-d8ea-11eb-93d0-74d8098b09f2.gif)

**Testing Apiary using Swagger/Open API.**

In this tutorial we will use an existing Swagger api to test the api generation.

Please download this formsapi YAML file from this Object Storage link: 
https://objectstorage.us-ashburn-1.oraclecloud.com/n/sehubjapacprod/b/OCI_Resources/o/lab_resources%2Fformsapi.yaml

Now in your APIARY create a new API called Forms API. 

![image](https://user-images.githubusercontent.com/34638862/123773875-95acaa80-d8ea-11eb-8a54-21f9cb246070.gif)

Copy paste the YAML file that you downloaded into the left panel. Like this:

![image](https://user-images.githubusercontent.com/34638862/123774082-b8d75a00-d8ea-11eb-8892-fe000f73408d.gif)

![image](https://user-images.githubusercontent.com/34638862/123774131-bffe6800-d8ea-11eb-8e82-59d2869bc8f7.gif)

Now as we have seen earlier apiary automatically creates mock api endpoints for us.

![image](https://user-images.githubusercontent.com/34638862/123774157-c7257600-d8ea-11eb-81c0-8b0891db7bd8.gif)

We can test any of these endpoints by selecting it and testing it using a mock server.

![image](https://user-images.githubusercontent.com/34638862/123774178-cc82c080-d8ea-11eb-9e62-55fb4b12fe85.gif)

We can copy the generated mock url and test it on Postman to see if working.

Go to Postman. Select request type as POST and paste the mock URL. We should get a 200 OK message.

![image](https://user-images.githubusercontent.com/34638862/123774201-d278a180-d8ea-11eb-9030-138164d1114d.gif)

This means that our generated service is working as expected.

**Unit Testing Using Dredd:** 

To unit test a code lets pick a simple code for now.

Create a new Api called “Hello World”.

![image](https://user-images.githubusercontent.com/34638862/123774244-db697300-d8ea-11eb-990f-5ce3baf583c5.gif)

Paste this code and click Save:
FORMAT: 1A
HOST: https://polls.apiblueprint.org/

# Hello World

Helloworld is a simple API allowing consumers to view helloworld.

# GET /
+ Response 200 (application/json; charset=utf-8)

            {"message": "Hello World!"}


![image](https://user-images.githubusercontent.com/34638862/123774320-ecb27f80-d8ea-11eb-9449-2e4e30330458.gif)

To Unit Test our code with Dredd, we need to navigate to the “Test” section in the main apiary page and then to the “Tutorial” section.

Run the below commands as shown.

![image](https://user-images.githubusercontent.com/34638862/123774345-f20fca00-d8ea-11eb-9c52-277b2b534c1d.gif)

Before running these commands we need to make sure we have node js and npm installed in our system.

Screenshot from Terminal:

![image](https://user-images.githubusercontent.com/34638862/123774367-f6d47e00-d8ea-11eb-9bb3-275980c96ab0.gif)

Create a file called api-description.apib and insert the following commands in the file.

FORMAT: 1A

# GET /
+ Response 200 (application/json; charset=utf-8)

      {"message": "Hello World!"}


Now create a app.js file and paste the following code.

var app = require('express')();

app.get('/', function(req, res) {
res.json({message: 'Hello World!'});
})
app.listen(3000);

Once done run these commands:
$ npm init
$ npm install express --save

Then run 
$ node app.js &

Type below command in your terminal or cmd prompt.
dredd api-description.apib http://127.0.0.1:3000

Ideally the folder structure would look like this after all installations:

![image](https://user-images.githubusercontent.com/34638862/123774413-018f1300-d8eb-11eb-8af3-c48bee36bf87.gif)

Finally type $ dredd to execute the test case run.

![image](https://user-images.githubusercontent.com/34638862/123774449-09e74e00-d8eb-11eb-846f-cde818655567.gif)

Above we can see that the test case has passed.

Now, If we navigate to the Apairy page we can see that the test case has passed and the required test details a displayed.

![image](https://user-images.githubusercontent.com/34638862/123774434-05bb3080-d8eb-11eb-8c62-318620f7de8d.gif)

Please follow this link for more info on dredd installation: https://dredd.org/en/latest/quickstart.html


This completes our Tutorial on APIARY.


APIARY Help:

To know more about APIARY please follow below links:

APIARY Help Page:
https://help.apiary.io

APIARY Info:
https://docs.oracle.com/cloud/apiary/index.html

Continuous Integration in APIARY:
https://www.ateam-oracle.com/continuous-integration-with-apiary-dredd-and-wercker
https://help.apiary.io/tools/automated-testing/testing-ci/







----x----
Created by Saikat Dey
Solution Engineering Hub, Oracle
