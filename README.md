# WhatsApp Bot 🤖

## Introduction:

In this tutorial, we are going to use Twilio and WhatsApp to access a user's GitHub account. This bot will allow us to make queries easily and quickly through the WhatsApp platform by receiving a username from GitHub as a parameter and returning as the response the most active repository of that user as well as how many days in a row the given user has made a commit.

## Tools to use 🛠:

- Twilio functions

- Whatsapp


---
## Part 1: Twilio 📌
- Go to the [Twilio home page](https://www.twilio.com/) and access it.

- If you do not have an account, you will need to create one in order to start the project..

- Under **Products**, select **Programmable SMS**.

- Name the project and click create..

---

## Part 2: Twilio function 📝

- Creating a function.

- Go to the **Runtime** tab, located on the left hand side of the project Dashboard.

<p align="center"><img width="684" alt="captura de pantalla 2019-03-07 a la s 12 19 26 p m" src="https://user-images.githubusercontent.com/32177779/53975922-f093b580-40d3-11e9-9490-9ab0570d0069.png"></p>


- Within **Runtime**, you will see a sub-tab called **Functions**. 
Click on the **Create a Function** button.

<p align="center"><img width="653" alt="captura de pantalla 2019-03-07 a la s 12 19 52 p m" src="https://user-images.githubusercontent.com/32177779/53976106-584a0080-40d4-11e9-86ad-c407a48e0088.png"></p>

- Now, you must select a template, in this case we will be using the **Blank** template.
- Once the template is selected, click on the button called **Create**.

<p align="center"><img width="646" alt="captura de pantalla 2019-03-07 a la s 12 20 08 p m" src="https://user-images.githubusercontent.com/32177779/53976181-83345480-40d4-11e9-9977-dc30ec692f85.png"></p>

- Name the function and add the name to the PATH.

<p align="center"><img width="751" alt="captura de pantalla 2019-03-07 a la s 12 20 19 p m" src="https://user-images.githubusercontent.com/32177779/53976242-a232e680-40d4-11e9-858f-03b8f1e8e0f2.png"></p>

- Copy and save the PATH to use it later.
- Within our newly created function, we need to add the code in **answeringWhatsApp.js** file, copy and paste it in the space called **Code**.
- Save the function.
- Now with our code in our Twilio function, we must add the dependencies, for this, go to the sub-tab of **Functions** called **Configure** and add **axios** and **moment** in the space called **Dependencies**.

<p align="center"><img width="821" alt="captura de pantalla 2019-03-07 a la s 12 20 40 p m" src="https://user-images.githubusercontent.com/32177779/53976325-c8588680-40d4-11e9-8284-b3ad32cfd5d3.png"></p>

---
## Parte 3: SMS Programable 📤
- To make our bot work with WhatsApp we must go to **Programmable SMS**.

<p align="center"><img width="443" alt="captura de pantalla 2019-03-07 a la s 12 20 59 p m" src="https://user-images.githubusercontent.com/32177779/53976525-38670c80-40d5-11e9-819f-a37ae3931240.png"></p>

- Being in **Programmable SMS**, we must go to the sub tab called **WhatsApp**.

- Within the **WhatsApp** tab you will see a sub-tab called **Sandbox**, click on it.

<p align="center"><img width="736" alt="captura de pantalla 2019-03-07 a la s 12 21 12 p m" src="https://user-images.githubusercontent.com/32177779/53976550-43ba3800-40d5-11e9-9577-8b0cbcf92bd9.png"></p>

- Inside **Sandbox** you will have to paste the path of the function that you copied and saved before in the field called **WHEN A MESSAGE COMES IN**.

---
## Part 4: WhatsApp 📨
- To be able to use our bot in WhatsApp you must:

  - Add this number **+1 415 523 8886** as a contact.
  - Follow the steps inside the learn sub-tab inside of the **WhatsApp** tab to connect the sandbox with **WhatsApp**.
  
  **Steps inside the Learn tab:**
  
  **Step 1:**
  
  <p align="center"><img width="702" alt="Captura de pantalla 2019-03-11 a la(s) 1 11 46 p  m" src="https://user-images.githubusercontent.com/32177779/54147103-70d15800-43ff-11e9-8ee5-7077e3f2fdbc.png"></p>

  - You must send a message with the code. i.e. join cream.
  
   **Step 2:**
   
<p align="center"><img width="700" alt="Captura de pantalla 2019-03-11 a la(s) 1 11 57 p  m" src="https://user-images.githubusercontent.com/32177779/54147444-2bf9f100-4400-11e9-96cf-f5d200036c90.png"></p>
   
   - You can skip this step.
   
   **Step 3:**
   
  <p align="center"><img width="701" alt="Captura de pantalla 2019-03-11 a la(s) 1 12 19 p  m" src="https://user-images.githubusercontent.com/32177779/54147224-b8f07a80-43ff-11e9-8cd4-54e108254525.png"></p>
   
   - In this part you could send the GitHub username as test and you will receive the answer that you are specting.
   
   **Step 4:**
   
<p align="center"><img width="702" alt="Captura de pantalla 2019-03-11 a la(s) 1 12 37 p  m" src="https://user-images.githubusercontent.com/32177779/54147283-d1609500-43ff-11e9-96c3-b030d62749b2.png"></p>
 
  - You can skip this part because we added the function PATH in the **PART 3:Programmable SMS**.
  
  **Note:** Do not forget to follow the steps listed above, as this is to connect your sandbox with WhatsApp.
  After have done the configurations for the WhatsApp connection with our sandbox we can make use of the bot normally.
 ---
## The final result 🌈:

- Here we send the specific code of our **SandBox** and try sending a user of **GitHub**.

<p align="center"><img width="320" alt="captura de pantalla 2019-03-07 a la s 12 21 37 p m" src="https://user-images.githubusercontent.com/32177779/53976914-f68a9600-40d5-11e9-8e9c-8c7ab86d82f0.png"></p>
