***Software Modelling***

***Use Case Description***

![](media/image1.png){width="6.322916666666667in"
height="2.736561679790026in"}

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Use name:**               Create a profile for Crownpass ID
  --------------------------- ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Description:**            A Crownpass Holder uses a third-party website to register for a Crownpass ID

  **Participating Actor:**    Crownpass Holder

  **Preconditions:**          The Crownpass Holder must have access to the internet in order to access the third-party website to create a profile for the Crownpass ID so they can register.

  **Postconditions:**         A request to create and generate a Crownpass ID will be recorded in the system or if the user fails to follow the photo upload guidelines or does not enter the mandatory details, then the system will display an error message and will not allow the Crownpass Holder to create a profile for registration.

  **Basic Flow:**             -   Crownpass Holder goes to third-party website
                              
                              -   System displays third-party website
                              
                              -   Crownpass Holder clicks on Register
                              
                              -   System displays Registration form for Crownpass ID
                              
                              -   Crownpass Holder enters personal information
                              
                              -   Crownpass Holder uploads photo using guidelines
                              
                              -   Crownpass Holder completes form
                              
                              -   If Crownpass Holder does not fill out mandatory details, then the system will display an error message
                              
                              -   Crownpass Holder submits form for verification
                              
                              -   If verification has failed, then they have to re-submit the form following the notes provided by the system
                              
                              -   If verification has passed, then the system will generate a Crownpass ID number
                              
                              -   Once the Crownpass ID number has been generated, it will display a list of options on how the Crownpass Holder can get their Crownpass. This will be Scan, Print, Email or Download.
                              
                              

  **Exceptional flows:**      -   Instead of ‘Submit Form for Verification’, crownpass holder might click on ‘cancel registration’
                              
                              In this case, the form and the information inside the form will not be stored.

  **Special requirements:**   -   Following on from successful verification, generated Crownpass ID number must be delivered within 10 seconds
                              
                              
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***Use Case Model***

Below is the Use Case Diagram which was created using Eclipse’s tool
called Papyrus for the Crownpass Holder who is creating a profile to get
a Crownpass ID.

![](media/image3.jpg){width="6.270833333333333in"
height="4.519409448818898in"}

***Activity Model***

Below is the Activity Diagram which was created using Eclipse’s tool
called Papyrus for the Crownpass Holder who is creating a profile to get
a Crownpass ID.

![](media/image2.jpg){width="6.270833333333333in"
height="3.7137806211723534in"}

Need to add object flow and activity node

***UML Structural Model***

***Behavioural Model***
