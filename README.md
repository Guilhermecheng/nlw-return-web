# nlw-return-web

### A functional feedback popup baloon!

Made with React, Vite, Typescript and tested with Jest. Front-end hosted in Vercel, and back-end hosted in Railway. Tested using Mailtrap.</br>
Web version of NLW Return project!

![image](https://user-images.githubusercontent.com/62719629/168478326-a8ff134f-7fef-4164-8463-503571a11802.png)

## Functionality

User must be able to give 3 types of feedback: a bug, an idea, or other

![image](https://user-images.githubusercontent.com/62719629/168478701-23505a7f-c01d-40db-abce-5fd1fbc8a408.png)

After feedback type is chosen, user can describe his feedback in the input area, and take a screenshot by clicking the camera button. He must provide a text in the input area to be able to send feedback.

![image](https://user-images.githubusercontent.com/62719629/168509563-02cc7ba9-58c8-42b3-ac43-85378d7d4b0c.png)

### Success message
After message is sent, if it was sucessfully, Success page will be delivered, with a button to send another feedback, if needed. It sends the user for the initial page of the popup

![image](https://user-images.githubusercontent.com/62719629/168509591-369d6243-6859-4048-b059-698096e421a0.png)

### The result

Message is sent to a back-end, hosted in Railway. Its function is to register the message in a database, and also sends an email to the page administrator. In this case, we are using a test email from Mailtrap.

Data saved in Railway database:</br>
![image](https://user-images.githubusercontent.com/62719629/168510435-4f4294f9-b8ac-4ed1-8825-2a20a55602b6.png)

Data sent in Mailtrap:</br>
![image](https://user-images.githubusercontent.com/62719629/168511067-4b7a4220-11dd-4d04-8be2-e1c2b9d5ef39.png)

