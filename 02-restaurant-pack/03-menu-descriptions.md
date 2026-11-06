---
name: menu-descriptions
description: Write short, tasty menu descriptions for dishes, drinks and desserts, for a printed menu, website, or delivery app. Use when you add a new dish, when a dish does not sell, when your menu is just names and prices, or when you update delivery app listings.
---

# Menu Descriptions — help a dish sell itself

A dish with a clear, tasty line sells more than the same dish with only a name. Guests cannot ask the menu questions. The description answers for you.

## How it works

```
┌──────────────────────────────────────────────────────────┐
│  WORKS ALONE                                              │
│  ✓ List dishes + what is in them. Get descriptions.       │
├──────────────────────────────────────────────────────────┤
│  BETTER WITH                                              │
│  + Voice Card  + which dishes you want to sell more       │
└──────────────────────────────────────────────────────────┘
```

## What I need from you

For each dish: name, main ingredients, how it is cooked, spicy level (if any), portion size. Mark the dishes you want to sell most.

## Steps

**Step 1.** Write each description with this formula: **taste word + main ingredient + how it is made + one extra detail.**

**Step 2.** Match length to where it appears:

| Where | Max words |
|---|---|
| Printed menu | 15 |
| Website | 25 |
| Delivery app | 30 (include portion and spice level) |

**Step 3.** Mark anything that could be an allergen or diet claim for you to check.

## Output

```
[DISH NAME] — $[price]
Menu (15 words): [text]
Website (25 words): [text]
Delivery app (30 words): [text]
Check: [allergens / claims I did not verify]
```

## Rules (and why)

- **Say what is in the dish.** "Chef's special" tells the guest nothing. "Slow-cooked goat with onion and whole spices" tells them everything.
- **Use real taste words:** crispy, creamy, smoky, tangy, fresh, hot. Avoid "delicious", "amazing", "authentic". Every restaurant says them.
- **Spice level in plain words:** mild, medium, hot. Guests hate surprises.
- **Never write allergen claims I did not get from you.** I will list "contains / may contain" only from your words. Wrong claims can hurt people.
- **Do not invent history.** "Grandmother's recipe" only if true.
- **Keep the dish name as is.** Guests know it, and the staff say it.

## Worked example

Messy input: *"chicken tikka masala - chicken, tomato cream sauce, we marinate overnight, mild, comes with rice. 14.99"*

Output:
```
CHICKEN TIKKA MASALA — $14.99
Menu (15 words): Overnight-marinated chicken in creamy tomato sauce, served with rice. Mild.
Website (25 words): Chicken marinated overnight, grilled, then simmered in a creamy tomato sauce. Served with basmati rice. Mild spice, easy for everyone.
Delivery app (30 words): Tender chicken, marinated overnight and simmered in creamy tomato sauce. Comes with rice. Mild spice. One generous portion.
Check: "basmati" — you said "rice" only. "Contains dairy" (cream) — please confirm.
```

## Tips

- Rewrite the 3 dishes that sell least. A good line moves a dish more than a price cut.
- Add "Most ordered" only if your POS shows it is true.
- Read the line aloud. If you would not say it to a guest, change it.

## Quick paste version for ChatGPT

> You write menu descriptions for my restaurant. For each dish I give you, write 3 lengths: printed menu (max 15 words), website (max 25), delivery app (max 30, with spice level and portion). Formula: taste word + main ingredient + how it is made + one extra detail. Avoid words like delicious, amazing, authentic. Do not invent history or ingredients. Never state allergen or diet claims unless I gave them; list anything to check at the end.

---
*LeadsLift free skill pack. Want help setting it up with a real teacher? See the classes: leadslift.io/classes*
