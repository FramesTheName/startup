# startup
This repository hosts a startup WebApplication for CS260 <br>
# Main Pages
## index.html
### Summary
## dashboard.html
### Summary
## profile.html
### Summary
## projects.html
### Summary
## personas.html
### Summary
## persona.html
### Summary
## empathize.html
### Summary
## problems.html
### Summary
## problem.html
### Summary
## insights.html
### Summary
## insight.html
### Summary
## about.html
### Summary

# Data Structures
## User
| Object  | Data Type |
| ------------- | ------------- |
| ID  | const UUID  |
| username  | string  |
| password  | string  |
| picutre  | img  |
| projects  | [projectID]  |

## Project
| Object  | Data Type |
| ------------- | ------------- |
| ID  | const UUID  |
| owner  | userID  |
| users  | [userID]  |
| personas  | [persona]  |

## Persona
| Object  | Data Type |
| ------------- | ------------- |
| ID  | const UUID  |
| name  | string  |
| picture  | img  |
| project  | projectID  |
| insights  | [insight]  |
| problems  | [problem]  |

## Insight
| Object  | Data Type |
| ------------- | ------------- |
| ID  | const UUID  |
| name  | string  |
| summary  | string  |
| comments  | [string]  |

## Problem
| Object  | Data Type |
| ------------- | ------------- |
| ID  | const UUID  |
| name  | string  |
| summary  | string  |
| comments  | [string]  |
| painpoints  | [string]  |

For more information on specific technologies used see [notes](notes.md)
