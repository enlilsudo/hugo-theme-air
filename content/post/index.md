# This is my portfolio.
On this site, you'll find

* My Biography
* My projects
* My resumé
# AWK Pogramming Language - A Tutorial


## Connection String URI Format
> "*The purpose statement is the soul of any technical article.*" (Orlando Nogueira)
>
Este documento descreve os formatos de URI para definir conexões entre aplicativos e instâncias do MongoDB.

> Analyse **purpose**

> Analyse **audience**

> Write **purpose statement**

# Connection String Formats

 - [ ] url-db
 - [ ]  Sentence outline
 - [ ] Draft
 - [ ] and final proof

## The 13 steps of technical writing
C4Context
     title System Context diagram for Internet Banking System
     Enterprise_Boundary(b0, "BankBoundary0") {
       Person(customerA, "Banking Customer A", "A customer of the bank, with personal bank accounts.")
       Person(customerB, "Banking Customer B")      
       Person_Ext(customerC, "Banking Customer C", "desc")            

       Person(customerD, "Banking Customer D", "A customer of the bank, <br/> with personal bank accounts.")

       System(SystemAA, "Internet Banking System", "Allows customers to view information about their bank accounts, and make payments.")  

       Enterprise_Boundary(b1, "BankBoundary") {

         SystemDb_Ext(SystemE, "Mainframe Banking System", "Stores all of the core banking information about customers, accounts, transactions, etc.")      

         System_Boundary(b2, "BankBoundary2") {  
           System(SystemA, "Banking System A")  
           System(SystemB, "Banking System B", "A system of the bank, with personal bank accounts. next line.")        
         }

         System_Ext(SystemC, "E-mail system", "The internal Microsoft Exchange e-mail system.")
         SystemDb(SystemD, "Banking System D Database", "A system of the bank, with personal bank accounts.")

         Boundary(b3, "BankBoundary3", "boundary") {  
           SystemQueue(SystemF, "Banking System F Queue", "A system of the bank.")        
           SystemQueue_Ext(SystemG, "Banking System G Queue", "A system of the bank, with personal bank accounts.")
         }
       }
     }

     BiRel(customerA, SystemAA, "Uses")
     BiRel(SystemAA, SystemE, "Uses")
     Rel(SystemAA, SystemC, "Sends e-mails", "SMTP")
     Rel(SystemC, customerA, "Sends e-mails to")

     UpdateElementStyle(customerA, $fontColor="red", $bgColor="grey", $borderColor="red")
     UpdateRelStyle(customerA, SystemAA, $textColor="blue", $lineColor="blue", $offsetX="5")
     UpdateRelStyle(SystemAA, SystemE, $textColor="blue", $lineColor="blue", $offsetY="-10")
     UpdateRelStyle(SystemAA, SystemC, $textColor="blue", $lineColor="blue", $offsetY="-40", $offsetX="-50")
     UpdateRelStyle(SystemC, customerA, $textColor="red", $lineColor="red", $offsetX="-50", $offsetY="20")

     UpdateLayoutConfig($c4ShapeInRow="3", $c4BoundaryInRow="1")
This procedure is called "writing systematically", which involves distributing the main systems of writing (13 steps) described above.

The systematic writing system will help us to get better in following aspects:

 - [ ] Speed
 - [ ] Time management
 - [ ] Coordination with staff and clients
 - [ ] Document quality


## Determine the audience's purpose for reading.
The audience is whoever uses the information in the document to achieve a purpose. The audience and its purpose determine document organization.

The four main audiences, and how each uses information:

 1. Experts give advice.
 2. Managers make decisions and plans.
 3. Operators follow instructions.
 4. General audience reads for information only.


## Identifying your purpose for writing
Try to answer, "what does the document do for you and your organization?" Consider the possibility that you may have more than one purpose for writing. If you have more than one purpose for writing, you most likely have more than one audience.

> **Warning**: Do not confuse the topic with your purpose for writing about it. *my purpose* is *to explain the functions of a new component* just discloses the topic. Instead, try to focus on what you achieve by explaning the topic: *I want the client to approve our set of functions, and I want the technical staff to develop a detailed design with the approved set of functions.

**Example**: There is an important difference between an *audience definition* and a *persona*. Many teams use personas to inform their design and development decisions. But a *persona* is a concrete characterization rather than a *well-defined audience type*. Both are valuable, but they are not the same thing.

Reliable and accessible documentation requires thorough product knowledge. It also, if not more, depends on knowing your audience.

Technical writers craft connections between an audience and a product. To build these connections, you need to identify your users as *clearly as possible* You also need to identify your user's goals: the problems they want to solve, the decisions they need to make, or the things they want to build.

Equipped with this audience awareness, you can write more accessible, well-situated, and supportive documentation. You can also help create *more satisfied customers*.

## How identifying audience can help a documentation team

Your documentation audience is likely composed of users with different experience levels, business roles, or use cases. You may be surprised at how many audiences use your documents.

Getting a clearer and more nuanced picture of who reads your documentation can help teams and individual authors in many ways, from defining team responsibilities to information architecture to editing a sentence.

Here are some areas where audience analysis and understanding can help you and your team.

## Team structure, expertise, and responsibilities

Knowing your audience can help the team decide which writers to recruit or to hire. Understanding the customers who you serve helps you identify the areas of expertise or experience you should seek when you are hiring.

Audience analysis can also help to identify learning opportunities for current team members. Writers might need to become more familiar with a certain kind of use case, external developer framework, or some aspect of the company's product line in order to better serve the users consulting the docs.

Audience can also play an important role when you're determining how to assign information development work. Certain writers might have particular familiarity with specific sections of the audience, such as app developers, data analysts, or system administrators, which will make them better suited to shape documentation structure and content for those users.  

# User testing and feedback
Your team might also conduct documentation user testing. Understanding your audience can help with identifying representative users to provide feedback on the docs.

User feedback can provide other important audience insights. Comments or questions can highlight particular use cases, business roles, or areas of interest among your readers.   

## Delivery format
Knowing your audience can influence the publication or delivery format for your users team's documentation. Your audience might comprise users who prefer online documentation, users who prefer printed versions, or both. Making a printable option available can make online documentation more accessible for all users.

If your team creates online documentation, audience awareness can also help with determining whether the UI and other aspects of the online suit users' needs. Are users satisfied with available options for navigating, searching, and reading the docs? If your audience includes users who consume the docs on desktop computers and mobile devices, is your content accessible and correctly formatted for both platforms?

## Information architecture and learning objectives

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file, and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication, which makes it easy for you to re-publish it. Once you have modified your file, and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```