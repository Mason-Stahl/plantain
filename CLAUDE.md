# plantain webapp overview
A dashboard ‘nursery’ to manage houseplants, with a whatsapp bot representing and personifying each one; based on the species it texts reminders, when to water, replace the soil, etc. 

## Design
`Skuemorphic nursery` plants are handdrawn or hand svg created. Glassy greenhouse, wooden accents.  

## Structure

### Homepage = frontend/src/pages/Nursery:

`PlantCard`
plant{svg image}
pot{customizable}
'nickname' 
species

- age
- location
- last watered: # days
- water in: # days
- repot in: # days
- health
- `(species info - clickable text)`
    - Light level needed
    - Soil type
    - etc
- `(manage - button)`
  - change info: age, nickname, species, location, health?
  - delete
  - notifications

`filter` - species

`sort` - any of the categories bulleted in plantcard listed above.

`settings`
- manage notifications
- customizations
- account settings

Extra Components:

`health`
- yellowing, bugs, drooping, browning, etc.

## Bot Info
- One WhatsApp bot. Design cannot be customized, so start messages off with bold individual plant info ie.
**"nickname" or kitchen monstera says:** Dont forget to water me tomorrow. 

What can be customized:
- Frequencey (day of, or # of days before)
- Personality (minimal, sassy, informative, species specific, etc.)