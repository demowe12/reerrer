# Manoj's Business - Amazon Clone Specification

## Project Overview
- **Project Name**: Manoj's Business
- **Type**: E-commerce single-page application
- **Core Functionality**: Product browsing, shopping cart with working calculations
- **Target Users**: Demo e-commerce showcase

## Visual Specification

### Design Theme
- **Style**: Glassmorphism (frosted glass effect)
- **Background**: Dark gradient with blur effects (deep purple to blue)
- **Color Palette**:
  - Primary: #667eea (Purple-blue)
  - Secondary: #764ba2 (Deep purple)
  - Accent: #f093fb (Pink highlight)
  - Glass: rgba(255, 255, 255, 0.1) with backdrop blur
  - Text: #ffffff (white)

### Layout
- **Header**: Logo, search bar, navigation, cart icon with badge
- **Hero Section**: Promotional banner with glass effect
- **Product Grid**: 4-column responsive grid with glass cards
- **Cart Sidebar**: Slide-out panel showing cart items
- **Footer**: Simple footer

## Features

### Product Display
- 8 demo products with:
  - Product image (placeholder from picsum.photos)
  - Product name
  - Price (displayed in ₹ INR)
  - Rating (star display)
  - "Add to Cart" button

### Shopping Cart
- Add/remove items
- Quantity adjustment (+/-)
- Real-time price calculation
- Running total display
- Cart badge showing item count

### Calculations
- Per-item total = price × quantity
- Cart subtotal = sum of all item totals
- Tax = subtotal × 18% (GST)
- Grand Total = subtotal + tax
- All calculations precise to 2 decimal places

## Technical Specification
- Single HTML file with embedded CSS and JavaScript
- No external frameworks (vanilla JS only)
- CSS backdrop-filter for glass effect
- CSS Grid for product layout
- LocalStorage for cart persistence (optional)

## Acceptance Criteria
1. Page loads with glassmorphism aesthetic
2. All 8 products display correctly
3. Add to cart increments badge count
4. Cart sidebar shows correct items and quantities
5. Price calculations are mathematically correct
6. Remove item works correctly
7. Quantity adjustment updates totals correctly
