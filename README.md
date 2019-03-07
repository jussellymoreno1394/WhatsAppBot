# WhatsApp Bot 🤖

## Introduction:

Bot that receives as a parameter a GitHub username and returns as response the most active repository of that user and also how many days in  a row  has made a Commit.

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

<p align="center"><img width="684" alt="captura de pantalla 2019-03-07 a la s 12 19 26 p m" src="https://user-images.githubusercontent.com/32177779/53975922-f093b580-40d3-11e9-9490-9ab0570d0069.png"></p>


- Within **Runtime**, you will see a sub-tab called **Functions** and inside you will see a button called **Create a Function**, click on it to create the function you need for this project.

<p align="center"><img width="653" alt="captura de pantalla 2019-03-07 a la s 12 19 52 p m" src="https://user-images.githubusercontent.com/32177779/53976106-584a0080-40d4-11e9-86ad-c407a48e0088.png"></p>

- Now, you must select a template, in this case the **Blank**.
- Once the template is selected, click on the button called **Create**.

<p align="center"><img width="646" alt="captura de pantalla 2019-03-07 a la s 12 20 08 p m" src="https://user-images.githubusercontent.com/32177779/53976181-83345480-40d4-11e9-9977-dc30ec692f85.png"></p>

- Now with our created function, give a name to the function and also to the PATH.

<p align="center"><img width="751" alt="captura de pantalla 2019-03-07 a la s 12 20 19 p m" src="https://user-images.githubusercontent.com/32177779/53976242-a232e680-40d4-11e9-858f-03b8f1e8e0f2.png"></p>

- Copy and save the PATH to use it later.
- Being within our function, we will give life to our bot by adding the following code in the space called **Code**.
- Save the function.
- Now with our code in our Twilio function, we must add the dependencies, for this, go to the sub-tab of **Functions** called **Configure** and add **axios** and **moment** in the space called **Dependencies**.

<p align="center"><img width="821" alt="captura de pantalla 2019-03-07 a la s 12 20 40 p m" src="https://user-images.githubusercontent.com/32177779/53976325-c8588680-40d4-11e9-8284-b3ad32cfd5d3.png"></p>

## Parte 3: SMS Programable 📤
- To make our bot work with WhatsApp we must go to **Programmable SMS**.

<p align="center"><img width="443" alt="captura de pantalla 2019-03-07 a la s 12 20 59 p m" src="https://user-images.githubusercontent.com/32177779/53976525-38670c80-40d5-11e9-819f-a37ae3931240.png"></p>

- Being in **Programmable SMS**, we must go to the sub tab called **WhatsApp**.

- Within the **WhatsApp** tab you will see a sub-tab called **Sandbox**, click on it.

<p align="center"><img width="736" alt="captura de pantalla 2019-03-07 a la s 12 21 12 p m" src="https://user-images.githubusercontent.com/32177779/53976550-43ba3800-40d5-11e9-9577-8b0cbcf92bd9.png"></p>

- Inside **Sandbox** you will have to paste the path of the function that you copied and saved before in the field called **WHEN A MESSAGE COMES IN**.

## Part 4: WhatsApp 📨
- To be able to use our bot in WhatsApp you must:

  - Add this number **+1 415 523 8886** as a contact.
  - You must send a message with the code.
  
    <p align="center"><img width="620" alt="captura de pantalla 2019-03-07 a la s 12 37 34 p m" src="https://user-images.githubusercontent.com/32177779/53976845-d3f87d00-40d5-11e9-96a9-fa47f49d4c38.png"></p>
    
## The final result 🌈:

- Here we send the specific code of our **SandBox** and try sending a user of **GitHub**.

<p align="center"><img width="320" alt="captura de pantalla 2019-03-07 a la s 12 21 37 p m" src="https://user-images.githubusercontent.com/32177779/53976914-f68a9600-40d5-11e9-8e9c-8c7ab86d82f0.png"></p>
