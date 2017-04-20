#THOTHLabsAPP

ABOUTME: 
I am Malcolm Price. I am the Founder and CEO of THOTH LABS. It's a Liberal Arts & STEM Lab for the Holistic -"ADHD"- Researchers. We are a small startup, and we respect all walks of life.
We are experts at rapidly failing, and we believe in our talents ability to find solutions. I believe in open-source programming, and I am open all constructive feedback. Currently, we are fundraising for commercial real estate in San Diego California. Follow/connect with me at www.linkedin.com\in\malcolm-price

APPLICATION:
We are working on developing a Website and Application for THOTH LABS.

In order to create a cross-platform mobile application using xamarin-form, we have defined the following C# objectives:

  A) A Program that authenticates a user's via to with Google, Linkedin, or Facebook
    i- If authentication is successful then allow user access to three SQL Databases: "TLUser," "TLUserInfo," and "TLUserEntries."
    ii- Lookup "TLUserEmail" in "TLUser" database, if a user is not in the database, create a new "TLUserID" in "TLUser."
    NOTE- "TLUser" is a trinary (three-valued) database; 1) UserloginEmail, 2) TLUserID, 3) TLUserCreationDateTime
    iii- "TLUserInfo" is from captured data from the APIs of Google, Facebook, and Linkedin. 
    iv- Wrangle and define TLUserFName, TLLName, TLUserID.

   B) A Program to Count the Total Amount of "TLUsers."
    i- Calculate DonationsRaised = Highest(TLUserID)* $20
    ii- Calculate  DonationsNeeded = 1,000,000 - CountThothUser
    iii- Define DonationGOAL = $20,000,000
  
   C) A Program to post/modify a 140-character entry to an SQL database, "TLUserEntries" in the cloud.
    NOTE Database holds binary values: 1)TLUserID, and 2) and 140-character string
    i- Templated entries are $"[TLUserLN], [TLUserFN] donated $20 to THOTH Labs"
    ii- Allow user overwrite template, and overwrite the entry to database
    iii- Prompt user to share app to a friend.
