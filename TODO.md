# Phantom Year - TODO List

## 1. Dynamic Next Sighting Feature

Write JavaScript code to automatically calculate and display the next Phantom Year date based on the current day.

**Requirements:**
- Calculate the next date where DD = YY
- Handle edge cases (e.g., February dates, end of range in 2031)
- Display in user-friendly format
- Update in real-time without page reload
- Show countdown or days remaining

**Implementation Notes:**
- Should work for dates from 2001-2031
- After 2031, display message about pattern ending
- Consider timezone handling

---

## 2. Phantom Year Calendar Visualization

Explore creating an interactive calendar that visualizes the entire Phantom Year pattern.

### Questions to Resolve:

**Organization:**
- Single view showing all 365 Phantom dates across 31 years?
- Year-by-year navigation (2001-2031)?
- Month-by-month view highlighting matching dates?
- Visual timeline/heatmap showing distribution?

**Month Naming:**
- Keep standard month names (January-December)?
- Create conceptual "Phantom Months" for the 365-day hidden year?
  - If so, how to organize 365 days into months?
  - 12 months? (Would need non-standard month lengths)
  - 13 months? (28 days each = 364, plus 1 extra day)
  - Something else entirely?

**Calendar Features to Consider:**
- Highlight dates that have already occurred vs. future dates
- Show which months contribute which dates to the Phantom Year
- Interactive: click a date to see its position in the pattern
- Visual representation of the 336-22-7 breakdown
- Export/share functionality

**Design Questions:**
- How to make it intuitive and visually striking?
- Should it emphasize the "scattered" nature or the "collected" year?
- Mobile-friendly vs. desktop experience?

---

## Future Ideas

- Add social sharing for upcoming Phantom dates
- Create downloadable calendar/reminder files (.ics)
- Visualize the pattern for other centuries (20th, 22nd, etc.)
- Educational content about calendar mathematics
- Compare with other calendar patterns/phenomena
