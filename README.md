# Barber Shop Website 🪒✂️

## Live Demo (GitHub Pages)
**[Admin Dashboard](https://roch-r.github.io/barber-shop/)** - Login: `admin` / `1234`
- Manage bookings, users, banned list, schedule, vacation dates, staff, hairstyles, GCash settings

**[Public Landing](https://roch-r.github.io/barber-shop/public-index.html)**
**[User Booking](https://roch-r.github.io/barber-shop/auth.html)**

## Setup GitHub Pages
1. Go to https://github.com/Roch-R/barber-shop/settings/pages
2. Source: **Deploy from branch** → **main** → **/ (root)**
3. Save → Site live at https://roch-r.github.io/barber-shop

## Features
### Admin Dashboard (`index.html`)
- ✅ Login (admin/1234)
- ✅ Bookings CRUD (approve/cancel)
- ✅ Users list + ban/unban
- ✅ Schedule management (opening/closing/slot duration)
- ✅ Vacation dates with calendar picker
- ✅ Staff management
- ✅ Hairstyles gallery CRUD
- ✅ GCash settings (QR/payment link)

### User Site (`auth.html`)
- ✅ Login/Register
- ✅ Hairstyles gallery (admin-updated)
- ✅ Date picker (schedule/vacation aware)
- ✅ Service picker modal
- ✅ Time slots (availability aware)
- ✅ GCash modal with QR/deep links
- ✅ Responsive booking flow

### Public Landing (`public-index.html`)
- ✅ Services showcase
- ✅ Links to booking

## Local Development
```
# Open files directly (updated 2026)
index.html        # Admin dashboard - v2.1.0
auth.html         # User booking site - v2.1.0  
public-index.html # Public landing - v2.1.0
```

## Data Storage
All data in **browser localStorage** (no backend required):
```
users          # Registered users
bookings       # User appointments
bannedUsers    # Suspended accounts
schedule       # Shop hours/slot duration
vacationDates  # Closed dates
staff          # Barbers list
kertHairstyles # Gallery (admin overrides)
kertGcash      # Payment settings
```

## Tech Stack
- Vanilla HTML/CSS/JS (no framework)
- localStorage (persistent data)
- Responsive design (mobile-first)
- Custom modals/date pickers/calendars
- Real-time admin ↔ user sync via localStorage

⭐ **Production ready** - Deploy & use immediately!

