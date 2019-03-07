# WhatsApp Bot 🤖

## Introduction:

This is a bot created with the functions of Twilio with support for WhatsApp.

You can consult this bot for any user of GitHub and he will return in response how many consecutive days Commits has made and which is the most active repository of that user.

## Tools to use 🛠:

- Twilio functions

- Whatsapp

## Part 1: Twilio 📌
- Go to the [Twilio home page](https://www.twilio.com/) and access it.

- If you do not have an account you will have to create one in order to start the project.

- Select in **Products**  and then **Programmable SMS**.

- Give the project a name and believe it.


## Part 2: Twilight function 📝

- We will create a function.

- Go to the **Runtime** tab, located on the left hand side of the project Dashboard.

<p align="center"><img width="684" alt="captura de pantalla 2019-03-07 a la s 12 19 26 p m" src="https://user-images.githubusercontent.com/32177779/53975922-f093b580-40d3-11e9-9490-9ab0570d0069.png">


- Within **Runtime**, you will see a sub-tab called **Functions** and inside you will see a button called **Create a Function**, click on it to create the function you need for this project.
- Now, you must select a template, in this case the **Blank**.
- Once the template is selected, click on the button called **Create**.
- Now with our created function, give a name to the function and also to the PATH.
- Copy and save the PATH to use it later.
- Being within our function, we will give life to our bot by adding the following code in the space called **Code**.
- Save the function.
- Now with our code in our Twilio function, we must add the dependencies, for this, go to the sub-tab of **Functions** called **Configure** and add **axios** and **moment** in the space called **Dependencies**.

## Parte 3: SMS Programable 📤
- Para hacer que nuestro bot funcione con WhatsApp debemos ir a **Programmable SMS**.
- Save the function
- Now with our code in our Twilio function, we must add the dependencies, for this, go to the sub-tab of **Functions** called **Configure** and add **axios** and **moment** in the space called **Dependencies**.
- Inside **Sandbox** you will have to paste the path of the function that you copied and saved before in the field called **WHEN A MESSAGE COMES IN**.

## Part 4: WhatsApp 📨
- To be able to use our bot in WhatsApp you must:

- Add this number **+1 415 523 8886** as a contact.
- You must send a message with the code.
