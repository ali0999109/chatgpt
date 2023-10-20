# Create playbook for ChatGPT from scratch in Azure cloud
- Search microsoft sentinel in azure > click on automation > create > playbook with incident trigger >
- 
  ![image](https://github.com/ali0999109/chatgpt/assets/145396907/0b1d4930-752f-49b5-b133-9bea136ce29e)
  -----
  ![image](https://github.com/ali0999109/chatgpt/assets/145396907/89752c92-f00d-4059-be90-4821c193c945)
  ---
 - Configuration of playbook > basic > playbook name ChatGPT > Enable diagnostic logs > Review and create

 - You will be redirected to a new page Logic app designer > click on new step > search for GPT > select GPT3 > to generate your api key go to https://platform.openai.com/account/api- 
   keys > type in Bearer(followed by your api key) > create
   
   ![image](https://github.com/ali0999109/chatgpt/assets/145396907/31c4f79d-d0c4-4189-8b3b-eadc6454e03b)
   ---

   - Prompt configuration > Promt how can i remediate > add dynamic content > Select Incident title > then type with description of in 
     the prompt > select incident description
     
     ![image](https://github.com/ali0999109/chatgpt/assets/145396907/2e90a5b8-1ef6-4ff8-8abb-670cc47d1049)
     ----

   - Select new step > search for add comment to incident and select
     
     ![image](https://github.com/ali0999109/chatgpt/assets/145396907/7a9f5a69-b2d6-492e-8699-572d9177df57)
     --

     - Incident ARM Id select Incident ARM id in the dynamic content
       
       ![image](https://github.com/ali0999109/chatgpt/assets/145396907/f4a504d2-b2ca-4fab-a314-32ea07ae273f)
       ---

       -Incident comment message go to the dynamic content and select see more > select text > click on save
       ![image](https://github.com/ali0999109/chatgpt/assets/145396907/8265a56a-3949-4b2f-ac92-a8d80bd198b1)



     

      


  




# Assign permissions to ChatGPT




# How to run ChatGPT on Cybersecurity incidents





# Make adjustments to ChatGPT




# How to create automation in SIEM with ChatGPT





# Create cybersecurity incident in SIEM





# Complex integration of AI with SIEM




# Alternative option for ChatGPT integration with SIEM






# Cleaning up Microsoft Sentinel to achieve zero cost
