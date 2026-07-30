# React / Next.js

React er mere fleksibelt end Angular.

En typisk struktur ser sådan ud.

```
app/
│
├── layout.tsx
├── page.tsx
│
├── login/
│   └── page.tsx
│
├── reviews/
│   ├── page.tsx
│   ├── new/
│   │   └── page.tsx
│   └── [id]/
│       └── page.tsx
│
├── whiskies/
│   ├── page.tsx
│   └── [id]/
│       └── page.tsx
│
└── profile/
    └── page.tsx

components/
│
├── layout/
│   ├── Navbar.tsx
│   ├── Footer.tsx
│   └── Sidebar.tsx
│
├── review/
│   ├── ReviewHeader.tsx
│   ├── ReviewDetails.tsx
│   ├── ReviewImage.tsx
│   ├── ReviewNotes.tsx
│   ├── ReviewRatings.tsx
│   └── ReviewScore.tsx
│
├── whisky/
└── ui/

lib/
│
├── api.ts
├── auth.ts
├── helpers.ts
└── validation.ts

services/
│
├── reviewService.ts
├── whiskyService.ts
└── authService.ts

types/
│
├── review.ts
├── whisky.ts
└── user.ts

hooks/
│
├── useAuth.ts
└── useReview.ts

context/
│
└── AuthContext.tsx
```
