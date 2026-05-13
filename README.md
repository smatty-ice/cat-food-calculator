# Kiki & Rainier Food Calculator

Daily food portion calculator for two cats — Kiki (14.2 lb, 6 yrs) and Rainier (8.7 lb, 2 yrs) — eating a combination of dry kibble and one wet can per day.

**Live:** https://smatty-ice.github.io/cat-food-calculator/

## Food

- **Dry:** Purina Pro Plan LiveClear Salmon & Rice — 561 kcal/cup, 133 g/cup
- **Wet:** Purina Pro Plan Complete Essentials Chicken & Turkey gravy variety — ~72 kcal per 3 oz can

## Math

Daily kcal target uses the standard veterinary RER formula:

```
RER = 70 × kg^0.75
Daily kcal = RER × (goal factor) × (activity factor)
```

Goal/activity multipliers:

| Goal     | Low | Med | High |
|----------|-----|-----|------|
| Loss     | 0.8 | 0.9 | 1.0  |
| Maintain | 1.0 | 1.2 | 1.4  |
| Gain     | 1.2 | 1.4 | 1.6  |

Dry portion = (daily kcal − wet kcal) ÷ 561 kcal/cup.

## Notes

- 14.2 lb is on the heavy side for a domestic shorthair. Flip Kiki's goal to "Weight loss" if her body condition score suggests it.
- Weigh dry food on a kitchen scale (≈40–50 g) for accuracy. Measuring cups vary a lot.
- Treats not included — budget separately, ideally <10% of daily kcal.

Not a substitute for vet advice.
