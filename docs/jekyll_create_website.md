# Jekyll Setup

## Create Posts

### File name

The posts are edited in any text editor using the **markdown** syntax.  

filename:  DD-MM-YYYY-this-is-the-title  

file extension: .md

### Front matter

The **front matter** section is on the very top of the file containing various file informations.

#### Beginn and end of front matter section

---  In the first and in the last line of front matter three hyphens.  

#### Front matter file informations

The file information is located in key pairs (variable:value). It can be done in YAML or in JSON file format.  
Here an example in YAML:  
     ---  
     layout: post  
     title: "How to write a post"  
     date: 2021-11-01 19:25  
     categories: jekyll creation  
     ---  

## Create drafts

### _draft directory

If you want to write a new post but dont want to show them on your website until its is finished you can save it in the **_draft** directory.

You can name the draft file in any way. If you want to publish the file rename it in the way specified above and move it to the _posts directory.
