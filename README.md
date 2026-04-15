# plantain
I forget to water my plants. I also care about the intersection of nature and technology. It would be cool to have a whatsapp bot representing each of my house houseplants, and then based on the species it could text me reminders, when to water, replace the soil, etc. A dashboard ‘nursery’ would be useful so i can manage them all.

## Categorization for images TBD
- palms (and palmlike),
- ferns (and fernlike),
- succulents,
- cacti (huge variety of),
- orchids (huge variety of),
- houseplants (tropical, flowering and leafy; trees and treelike),
  - Dracaenas
  - Hoyas
  - Peperomias
  - Philodendrons
  - Pothos
  - Sansevierias
  - Succulents
  - Carnivorous
  - Miscellaneous
- vines (tropical, flowering and leafy),
- airplants, mossy plants (ie selaginella),
- bromeliads (huge variety of).

## Flow
1. visit 'plaintain.masonstahl.com'.
2. add your plants, filling out info about the species, est. age, window location, size...
3. optionally for plants to text you reminders, go to settings, customize what you want to be notified for, and enter your phone #. Make sure this # is connected to WhatsApp.
4. enjoy the growth! :greenthumbsup:

## Structure

Homepage = Nursery:

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

## Design
`Skuemorphic nursery` plants are handdrawn or hand svg created. 

If you would like to contribute with your own 2D art of a particular species: Upload to: 'plantain.masonstahl.com/upload' 

## Uploading
- 500x500px
- 3 colors max
- Understand while greatly appreciated, your design may not be used.
