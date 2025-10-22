# CE RPG Character Sheet for Roll20

A dark fantasy character sheet for CE RPG (Cinematic Engine Role Playing Game), designed for Roll20 with modern web standards and a gothic aesthetic inspired by sword and sorcery settings.

## Features

### 🎭 Core Character Elements
- **Five Primary Attributes**: Might, Finesse, Wits, Will, and Vigor
- **Derived Stats**: Automatically calculated Wounds, Sanity, Plot Armor, Defense, and Initiative
- **Resource Management**: Cunning, Breath, Pips, and Narrative Points
- **Dynamic Traits System**: Bidding traits for narrative control
- **Special Abilities**: Magicka, combat techniques, and unique powers
- **Equipment System**: "Ninja Gear" with trait-based die mechanics

### 🎨 Design & Aesthetics
- **Dark Fantasy Theme**: Gothic color scheme with golden accents
- **Responsive Layout**: Three-column design that adapts to different screen sizes
- **Interactive Elements**: Hover effects, focus animations, and smooth transitions
- **Accessibility**: High contrast ratios and keyboard-friendly navigation
- **Print-Friendly**: Optimized print styles for physical copies

### ⚙️ Roll20 Integration
- **Modern HTML5/CSS3**: Uses current web standards, no deprecated features
- **Automated Calculations**: Worker script handles derived stats automatically
- **Roll Templates**: Custom templates for dice rolls and actions
- **Repeating Sections**: Dynamic lists for traits, abilities, and equipment
- **Macro Support**: Compatible with Roll20's macro system

## File Structure

```
├── ce-rpg-character-sheet.html    # Main character sheet HTML
├── ce-rpg-character-sheet.css     # Stylesheet with dark fantasy theme
└── README.md                      # This documentation file
```

## Installation in Roll20

### For Game Masters:
1. Create a new campaign in Roll20
2. Go to Campaign Settings → Character Sheet Template
3. Select "Custom" from the dropdown
4. Copy the contents of `ce-rpg-character-sheet.html` into the HTML tab
5. Copy the contents of `ce-rpg-character-sheet.css` into the CSS tab
6. Save the changes

### For Players:
- Your GM will need to set up the custom character sheet
- Once set up, you can create characters using the new sheet interface

## Character Creation Guide

### Step 1: Basic Information
- **Character Name**: Your character's name (displayed prominently)
- **Player Name**: Your real name
- **Origin**: Your character's background or homeland
- **Calling**: Your character's profession or life path
- **Experience**: Current experience points

### Step 2: Attributes (1-12 scale)
- **Might**: Physical strength and power
- **Finesse**: Dexterity, agility, and grace
- **Wits**: Intelligence, cunning, and perception
- **Will**: Mental fortitude and determination
- **Vigor**: Health, endurance, and constitution

### Step 3: Derived Stats (Auto-calculated)
- **Wounds**: Might + Vigor (physical damage capacity)
- **Sanity**: Will + Wits (mental damage capacity)
- **Plot Armor**: Protection from certain death (default: 3)
- **Defense**: 10 + Finesse (difficulty to hit you)
- **Initiative**: Finesse + Wits (action order)

### Step 4: Resources
- **Cunning**: Spend to act twice in a round
- **Breath**: Spend to immediately go to Limbo
- **Pips**: Change something in the past (spend 5 to gain a trait)
- **Narrative Points**: Change something in the present

### Step 5: Traits
Define your character through descriptive traits that can be "bid" for narrative advantage:
- Click "BID" to use a trait in the story
- Traits color your actions and provide mechanical benefits
- More evocative traits are generally more useful

### Step 6: Abilities
Special powers beyond normal human capability:
- **Magicka**: Supernatural spells and enchantments
- **Combat**: Advanced fighting techniques
- **Social**: Extraordinary interpersonal skills
- **Utility**: Useful supernatural or exceptional abilities
- **Upgrades**: Increase effectiveness (0-5 scale)

### Step 7: Equipment ("Ninja Gear")
- **Gear Name**: What the item is called
- **Traits**: Number of descriptive qualities (1-5, determines die type)
- **Description**: What the gear does and how it works
- **Bid Gear**: Use equipment to gain extra dice in challenges

## Game Mechanics

### The Throw Down
The core resolution mechanic involves rolling:
- **Action Die**: Always a d10
- **Aspect Die**: Varies based on the trait or ability used (d4-d12)
- **Success Threshold**: Set by the GM based on difficulty
- **Successes**: 4-7 = 1 success, 8+ = 2 successes

### Using the Sheet
1. **Bidding Traits**: Click the "BID" button next to any trait to use it
2. **Throw Down**: Use the "THROW DOWN" button for major actions
3. **Initiative**: Roll initiative at the start of combat
4. **Resource Spending**: Manually track and adjust resources
5. **Equipment**: Bid gear for additional dice on relevant actions

### Roll Templates
The sheet includes custom roll templates for:
- **Throw Down**: Shows Action and Aspect dice results
- **Trait Bidding**: Displays which trait is being used
- **Gear Usage**: Shows equipment being employed
- **Basic Rolls**: General purpose rolling template

## Customization Options

### Color Themes
The CSS uses CSS custom properties (variables) for easy color customization:
- `--primary-bg`: Main background color
- `--text-accent`: Gold accent color for highlights
- `--border-accent`: Bronze/brown accent for borders
- Modify these in the `:root` section for different themes

### Layout Modifications
- **Responsive Breakpoints**: 1200px and 768px for different screen sizes
- **Grid Layout**: Easy to modify column arrangements
- **Section Ordering**: Rearrange sections by moving HTML blocks

### Additional Features
- **Font Selection**: Uses 'Cinzel' Google Font with fallbacks
- **Animation Effects**: Glow effects on focus, hover transitions
- **Print Optimization**: Clean black-and-white print styles

## Technical Details

### Browser Compatibility
- **Modern Browsers**: Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
- **Mobile Support**: Responsive design works on tablets and phones
- **Roll20 Compatibility**: Tested with Roll20's current platform

### Performance
- **Lightweight**: Minimal JavaScript, CSS-driven animations
- **Fast Loading**: Optimized for Roll20's environment
- **Memory Efficient**: Uses CSS Grid and Flexbox for layout

### Accessibility
- **High Contrast**: Dark theme with sufficient color contrast
- **Keyboard Navigation**: All interactive elements are keyboard accessible
- **Screen Reader Support**: Proper semantic HTML structure
- **Focus Indicators**: Clear visual focus states for all inputs

## Troubleshooting

### Common Issues
1. **Sheet Not Loading**: Ensure all HTML and CSS is properly copied
2. **Styling Issues**: Check that CSS is in the CSS tab, not HTML tab
3. **Roll Templates Not Working**: Verify template names match exactly
4. **Responsive Issues**: Clear browser cache and refresh

### Support
- Check Roll20 forums for custom character sheet help
- Ensure your Roll20 subscription supports custom character sheets
- Test in a private campaign before using in active games

## License and Credits

This character sheet is created for the CE RPG system using Roll20's custom character sheet framework. It follows Roll20's terms of service for custom content and is provided for community use.

### Acknowledgments
- **Roll20**: For providing the custom character sheet platform
- **CE RPG Community**: For inspiration and game mechanics
- **Gothic/Medieval Design**: Inspired by dark fantasy aesthetics
- **Modern Web Standards**: Built with HTML5, CSS3, and ES6

## Version History

### v1.0.0 (Current)
- Initial release with complete character sheet functionality
- Dark fantasy theme with responsive design
- Full Roll20 integration with roll templates
- Automated calculation system
- Comprehensive trait and equipment systems

---

*For the latest updates and community discussion, visit the CE RPG community forums or Roll20's custom character sheet repository.*
