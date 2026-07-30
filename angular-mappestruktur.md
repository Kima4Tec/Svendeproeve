# Angular

Angular er meget framework-baseret, så strukturen bliver ofte ens fra projekt til projekt.

```
src/
│
├── app/
│   │
│   ├── core/
│   │   ├── guards/
│   │   ├── interceptors/
│   │   ├── services/
│   │   └── models/
│   │
│   ├── shared/
│   │   ├── components/
│   │   ├── directives/
│   │   ├── pipes/
│   │   └── interfaces/
│   │
│   ├── features/
│   │   │
│   │   ├── auth/
│   │   │   ├── components/
│   │   │   ├── pages/
│   │   │   ├── services/
│   │   │   └── auth.routes.ts
│   │   │
│   │   ├── whisky/
│   │   │   ├── components/
│   │   │   ├── pages/
│   │   │   ├── services/
│   │   │   └── whisky.routes.ts
│   │   │
│   │   └── review/
│   │       ├── components/
│   │       ├── pages/
│   │       ├── services/
│   │       └── review.routes.ts
│   │
│   ├── app.component.ts
│   ├── app.config.ts
│   └── app.routes.ts
│
├── assets/
└── environments/
```
