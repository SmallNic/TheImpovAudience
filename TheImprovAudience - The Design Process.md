### **Purpose**

The purpose is to provide users a way to get a random word, location, or relationship. Improvisers often practice without the benefit of an audience. The audience is what provides them with their suggestions off which they base their scene. This skill offers the improviser what the improv audience normally does.

### **What will the person be doing before, during, and after interacting with the skill?**

Before: getting ready to have an improv practice

During: listening

After: using the suggestion offered by the skill or reengaging with the skill to get new information

### **What will people get from the skill that they cannot get another way?**

Many users will be comfortable and able coming up with words, locations and relationship on their own. This helps them when they cannot. The skill will have a greater library of suggestions than the improviser's brain.

### **What can a user do or not do with the skill?**

A user can get:

* a random word
* a random location
* a random relationship

### **What information is the person expected to have available?**

The user only needs to know what information they want: word, location or relationship

### **What are the ways a user can invoke the skill?**

{suggestion} = word || location || relationship

**Alexa, ***Get* *a {suggestion} ***from** The Improv Audience

**Alexa, Ask** The Improv Audience *for a {suggestion}*

**Alexa**, C*an I get a {suggestion}* **from** The Improv Audience

**Alexa**, *I just need a {suggestion}* **from** The Improv Audience

**Alexa, Start/Talk to/Open **The Improve Audience

### **What features directly support the purpose?**

n/a

### **Is there information you need from other experiences?**

Undetermined. Possible options for suggestions:

* Hard-coded into the application
* Hard-coded as JSON into a site that AWS Lambda can access
* An API that generates random words.

### **Example Scripts:**

User: Alexa, Start/Talk to/Open** **The Improve Audience.

Alexa: Welcome to The Improv Audience. You can ask for a word, a location, or a relationship. Which Would you like?

User: A word/word || A location/location || A relationship/relationship

Alexa: Your {word/location/relationship} is {coffee/coffee shop/cashier and customer}. 

---

User: Alexa, Get a **{word/location/relationship}** from The Improv Audience

Alexa: Your **{word/location/relationship}** is **{coffee/coffee shop/cashier and customer}**

---

User**: **Alexa, Ask The Improv Audience for a **{word/location/relationship}**

Alexa: Your **{word/location/relationship}** is **{coffee/coffee shop/cashier and customer}***
*

---

User: Alexa, Can I get a **{word/location/relationship}** from The Improv Audience

Alexa: Your **{word/location/relationship}** is **{coffee/coffee shop/cashier and customer}**

---

User: Alexa, I just need a **{word/location/relationship}** from The Improv Audience

Alexa: Your** {word/location/relationship}** is **{coffee/coffee shop/cashier and customer}***
*

---

**Optional Followup**

Alexa: Your** {word/location/relationship}** is **{coffee/coffee shop/cashier and customer}**. Would you like a different **{word/location/relationship}**?

User: Yes 

Alexa: Your** {word/location/relationship}** is **{coffee/coffee shop/cashier and customer}**. Would you like a different **{word/location/relationship}**?

User: No

**
**

**
**

Note: In the Alexa app, you can give a word a thumbs up/down if you think it's a good improv audience suggestion

Note: Someday it would be cool to give a category and Alexa gives you items in that category: Alexa, ask The Improv Audience for a car/cereal/color.

### Develop the Flow

Outline the shortest route to completion

Outline alternate paths and decision trees

Outline behind-the-scenes decision the system logic will have to make

Outline how the skill will help the user

Outline the account linking process, if present











Returns:

* Word - API?
* Location - repo?
* Relationship - repo?

Do I want to come up with a repository of those things myself or outsource them to some sort of API?