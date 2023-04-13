#Lab: ChatGPT API & Unity Demo
##Objective
Create a ChatGame in Unity using C# and chatGPT API.

##Description
In this lab, you will learn how to create a chatbot in Unity using the OpenAI API and C#. The chatbot will use the OpenAI GPT-3 model to generate responses based on the user's input.

##Prerequisites
Basic knowledge of C#.
Unity installed on your computer.
An OpenAI API key.

##Steps

###Set up your environment variables
To communicate with OpenAI, you need an account on openai.com and an API key that they provide. Save the API key in your environment variables so that it is not saved in your source code. Refer to the tutorial on how to add your OpenAI API key to system environment variables.

###Get the OpenAI C# wrapper
Download the open-source OpenAI C#/.NET SDK from OkGoDoIt/OpenAI-API-dotnet: An unofficial C#/.NET SDK for accessing the OpenAI GPT-3 API on GitHub.
Go to the releases page and choose a version. Download the source folder in .zip format and extract the contents somewhere (the download folder works fine).

###Configure your Unity project
Create a new Unity project if you don't already have one in progress. Create a new folder in the Assets directory called "ThirdParty" and create a new folder inside called "OkGoDoIt". Drag the README and the OpenAI_API folder from the folder you unzipped in the previous step into the OkGoDoIt folder.

###Add resources
In this project, you will use some free resources from the Unity Asset Store. These are optional but recommended to make the chatbot more interesting. Search for and download the "Dog Knight PBR Polyart" and "Fortress Gate" resources and import them into your Unity project.
Dog Knight PBR Polyart | 3D Animals | Unity Asset Store
Fortress Gate | 3D Fantasy | Unity Asset Store

###Add UI elements
Set up a few UI elements for display and user interaction:
A TextMeshPro text area.
A TextMeshPro text input field.
A TextMeshPro button.

###Create the OpenAIController.cs script and add the following code.
