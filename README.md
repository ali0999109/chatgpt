[Incident+Examples.txt](https://github.com/ali0999109/chatgpt/files/13061808/Incident%2BExamples.txt)# Create playbook for ChatGPT from scratch in Azure cloud
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
 - Go to the resource group where you deployed Microsoft Sentinel > click on access control (IAM) > add > add role assignment > search for Microsoft Sentinel > Select Microsoft sentinel 
  responder > Members > assign access to > managed identity > select members > look for your logic app > review and assign

 ![image](https://github.com/ali0999109/chatgpt/assets/145396907/39d9a563-782d-447c-952e-bb3d1b530379)

 


# How to run ChatGPT on Cybersecurity incidents
- Go to the incident tab in Microsoft Sentinel > click on one of the incidents > actions > run playbook preview > click run > go down and click view full details > Activity Log will 
  show you chatGPT recommendations if you look closely chatGPT wasn't able to finish the last point which we will fix in the next section
  
  ![image](https://github.com/ali0999109/chatgpt/assets/145396907/e4579f05-1960-432e-8b53-def5b75e7a14)
  -------
  ![image](https://github.com/ali0999109/chatgpt/assets/145396907/b7969651-e0f8-477f-af1b-6f318af12790)







# Make adjustments to ChatGPT
- Search for logic apps > select your playbook > logic app designer > Click GPT3 > Max tokens 300 > move back to Microsoft sentinel and try again you should be able to a full response 
 from chatGPT now
 ![image](https://github.com/ali0999109/chatgpt/assets/145396907/9dee8b08-d1e7-4d5d-9b26-5d09a86b32c3)




# How to create automation in SIEM with ChatGPT
- Go to Microsoft sentinel > automation > create > automation rule > Trigger when incident is created > Conditions select all > Actions run playbook > select your playbook > Rule expiration > order 5 > apply
- automation rule should be created shortly
  
![image](https://github.com/ali0999109/chatgpt/assets/145396907/e5022911-499d-45b0-be16-30ab9f152ef1)





# Create cybersecurity incident in SIEM
- Go to Microsoft sentinel > Incidents > Create incident > give it a name > description [Uploading Incident+Examples.txt…]()







# Complex integration of AI with SIEM




# Alternative option for ChatGPT integration with SIEM






# Cleaning up Microsoft Sentinel to achieve zero cost
