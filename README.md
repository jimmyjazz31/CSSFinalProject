# CSSFinalProject
Final Project with Design Patterns, ie Creational and Structural

### Creational Patterns : for this project I have used the following 2 creation design patterns: 
- Abstract Factory.  The use of this is for the construction of the portfolios.  The portfolios are suited to the Abstract factory since essentially this is creating families of related objects. Thus the two Advanced Portfolios (Summit, & Ascent) are part of the Portfolio family as is the Expedition Portfolio that sits under the Starter Portfolio interface.
- Singleton.  The use of this creational pattern is directly related to the role of the LeadPortfolioManager.  As this staff member has the ultimate responsibility for the notification process (to be described later in the Observer pattern) I have utilised this creation pattern in order to have that notification class rest only with the LeadPortfolioManager.  
