# ThoughtfulDesign.click
### Elevator Pitch
In the 1960's the term 'wicked problems' was first coined. To combat these wicked problems design thinking has been implemented by university business schools across the nation including BYU,Stanford,and IDEO. At the heart of design thinking is collaboration and this webapp helps schools move past physical barriers and into an online envoriment. ThoughtfulDesign.click creates an online playground that allows students and researchers to colloborate using design thinking. Users can quickly create different projects with personas to help identify problems, and gather key insights. 
## Main Pages
### index.html
#### Summary
The index page allows individuals to login or create account.
#### design
### dashboard.html
#### Summary
The dashboard page allows an individual to quickly see the projects and personas they are working with.
#### design
### profile.html
#### Summary
The profile page allows users to view their profile information and make any updates or changes.
#### design 
### projects.html
#### Summary
The projects page displays a list of all the project a user is currently joined to.
#### design
### project.html
#### Summary
The project page lists allows users to quickly view all of the personas and users that are currently in the project. This page also allows project owners to create new personas as well as add and remove editors.
#### design
### personas.html
#### Summary
The personas page gives a quick look at all of the personas currently made in a project.
#### design
### persona.html
#### Summary
The persona page allows users to quickly view a persona along with an empathy map, insights, and problems related that persona.
#### design
### empathize.html
#### Summary
The empathize page allows users to add points to an empathy map as well as add insights to a persona.
#### design
### problems.html
#### Summary
The problems page allows users to quickly view all of the problems associated with a persona.
#### design
### problem.html
#### Summary
The problem page allows users to view at add pain points associated with a problem.
#### design
### insights.html
#### Summary
The insights page allows users to quickly view all of the insights associated with a persona.
#### design
### insight.html
#### Summary
The insight page allows users to view a specific insight and add comments to that insight.
#### design
### about.html
#### Summary
The about page gives overall information about thoughtfuldesign.click
#### design

## Data Structures
### user
| Object  | Data Type |
| ------------- | ------------- |
| ID  | const UUID  |
| username  | string  |
| password  | string  |
| picutre  | img  |
| projects  | [projectID]  |
| notifications  | [notification]  |

### notification
| Object  | Data Type |
| ------------- | ------------- |
| user  | userID  |
| title  | string  |
| content  | string  |

### project
| Object  | Data Type |
| ------------- | ------------- |
| ID  | const UUID  |
| owner  | userID  |
| users  | [userID]  |
| personas  | [persona]  |

### persona
| Object  | Data Type |
| ------------- | ------------- |
| ID  | const UUID  |
| name  | string  |
| picture  | img  |
| project  | projectID  |
| empathyMap  | empathyID  |
| insights  | [insight]  |
| problems  | [problem]  |

### empathyMap
| Object  | Data Type |
| ------------- | ------------- |
| ID  | const UUID  |
| persona  | personaID  |
| did  | [empathyPoint]  |
| said  | [empathyPoint]  |
| felt  | [empathyPoint]  |
| thought  | [empathyPoint]  |

### empathyPoint
| Object  | Data Type |
| ------------- | ------------- |
| name  | [string]  |
| content  | [string]  |

### insight
| Object  | Data Type |
| ------------- | ------------- |
| ID  | const UUID  |
| creator  | userID  |
| editors  | [userID]  |
| name  | string  |
| content  | string  |
| comments  | [string]  |

### problem
| Object  | Data Type |
| ------------- | ------------- |
| ID  | const UUID  |
| creator  | userID  |
| editors  | [userID]  |
| name  | string  |
| summary  | string  |
| comments  | [string]  |
| painpoints  | [string]  |

## Main Deliverables
### HTML deliverable
### CSS deliverable
### JavaScript deliverable
### Database deliverable
### Login deliverable
### WebSocket deliverable
### React deliverable

For more information on specific technologies used see [notes](notes.md)
