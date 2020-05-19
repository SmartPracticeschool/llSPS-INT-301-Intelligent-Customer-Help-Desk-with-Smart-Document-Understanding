# llSPS-INT-301-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding

<b>Youtube explanation video Link :</b> https://youtu.be/I0X5m3YdSkw

<b>Node Red Dashboard Link :</b> https://node-red-arindom-smartbridge.eu-gb.mybluemix.net/ui/#!/0?socketid=CqjftvQKEMM_HyQTAAAM

This is repositroy build Using the Watson Discovery Smart Document Understanding (SDU) feature, we will enhance the Discovery model so that queries will be better focused to only search the most relevant information found in a typical owner's manual and Using Watson Assistant, we will use a standard customer care dialog to handle a typical conversation between a custmomer and a company representitive. When a customer question involves operation of a product, the Assistant dialog will communicate with the Discovery service using a webhook.The webhook will be created by defining a web action using IBM Cloud Functions


<h1>Introduction:</h1>
This project is build with the help of IBM Watson Assistant, Watson Discovery, Cloud Function and Node Red app of IBM Cloud. It is made with the regard of partial fulfillment of Smartinternz Internship Program at smartbrigde.

<h1>Skills Required:</h1>
Python,IBM Cloud,IBM Watson

<h1>Project Description :</h1>
The typical customer care chatbot can answer simple questions, such as store locations and hours, directions, and maybe even making appointments. When a question falls outside of the scope of the pre-determined question set, the option is typically to tell the customer the question isn’t valid or offer to speak to a real person.

In this project, there will be another option. If the customer question is about the operation of a device, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the device’s owners manual. So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the owners manual to help solve our customers’ problems.

To take it a step further, the project shall use the Smart Document Understanding feature of Watson Discovery to train it on what text in the owners manual is important and what is not. This will improve the answers returned from the queries.


<h2>Contents in Repository:</h2>

1.Cloud Function Code

2.Node RED Flow Code

3.Watson Assistant Skill

4.Watson Discovery Document

5.Project Explanation Video link

6.Project Report
