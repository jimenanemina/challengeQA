
# challengeQA Frontend
This is challenge oriented to understand the skills of an interviewee on frontend automation.



 # Requirements:
 
 - Internet access.
 - A Github account. If you dont have one, please create one, it will take a few minutes.https://github.com/join
 - You can use the IDE you feel most comfortable with, the same goes for programming language and for automation framework you should use Selenium Web Driver or Cypress. Code from framework recorders is not allowed.
 - Test cases should be written in Gherkin (not a must).
 - For assertions you can use Mocka and Chai, but if you prefer other assertion library, feel free to implement them.
 - You will need to deliver a testing project and upload it to this repository on a branch named after you. If you have issues pushing your results to Git you can send a zip file to your HHRR contact.

# What your test needs to do:

- Having the https://www.mercadolibre.com.ar/ web site as web application your test will need to do:

 1. Search a TERMO LUMILAGRO using the search box in the Home Page. (search query: termo lumilagro)
 2. Once you get a result list for termos lumilagro, select one which can be delivered tomorrow.
 3. Once you have clicked on an item page of the list that has the previous requirements, make the following assertions:
   - Title of the item being viewed must contain "termo lumilagro" on the title.
   - Arrival date for shipment must be tomorrow.
   - Item must have stock available. 
   
Here is a visual example:

https://user-images.githubusercontent.com/83258669/116177969-26002080-a6eb-11eb-84a3-aa92c1c2d63f.mp4



If you have any further questions please email: jnemina@santandertecnologia.com.ar


----------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------

#challenge QA Backend
This is challenge oriented to understand the skills of an interviewee in backend automation. Please read the instructions carefully before you begin.


# Target:
Write a singles test using the open Mercado Libre API and utilize the result of a search query to apply a set of assertion that will be provided. In case find more assertions that apply to your test, please feel free to add them.

 # Requirements:
 
 - Internet access.
 - A Github account. If you dont have one, please create one, it will take a few minutes.https://github.com/join
 - You can use the IDE you feel most comfortable with, the same goes for programming language and for automation framework you should use Postman, Cypress or Rest Assured. 
 - Test cases should be written in Gherkin (not a must).
 - For assertions you can use the library you feel most comfortable with.
 - You will need to deliver a testing project and upload it to this repository on a branch named after you. If you have issues pushing your results to Git you can send a zip file to your HHRR contact.

# What your test needs to do:

1. Using the Mercado Libre open API (Ítems y Búsquedas), perform a search using as query parameter “termoLumilagro”


  2. Once you have the response of the GET api call you made, make the following assertions:
   - Status code.
   - Key site_id should be MLA
   - Key query must be the same used in the api call parameter. 
   - Access the 3rd object from the results list and assert the key currendcy_id to be “ARS”.
   - Response should not be null or empty.


   If you have any further questions, please email: jnemina@santandertecnologia.com.ar or jrodriguezmendez@santandertecnologia.com.ar

#How do you send your work?:

You can either upload it to Git Hub or you can send it via email to the addresses listed above.

