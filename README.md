# Bloom Laser Clinic: Homepage Redesign Concept

An unofficial UX and UI redesign concept for the homepage of Bloom Laser Clinic, a doctor-led laser, skin and wellness clinic in Halifax, Nova Scotia.

**This is a portfolio project. It is not affiliated with, endorsed by, or commissioned by Bloom Laser Clinic.**

Live page: `https://ariq-lab.github.io/bloom-laser-clinic-redesign/`

## The problem

The clinic is highly qualified. Its lead dermatologist has 30 years of experience, and the clinic holds a 4.6 Google rating from 149 reviews. The current website doesn't show that. It has outdated content, hidden credentials, no online booking, prices for only a few services, and navigation organized by machine names instead of the problems people want treated.

## Goals

- **Business goal:** turn visitors into booked consultations
- **User goal:** quickly answer three questions: Can they help me? Can I trust them? How do I book?
- **Design goal:** premium, clean, calm and medical, not a beauty spa

## Process

1. **Website audit** of services, pricing, credentials, content and UX issues
2. **Proto-personas** built from site evidence: an anti-aging client, a hair and tattoo removal client, a skin condition patient, and a chronic pain patient
3. **Information architecture:** navigation reorganized by client concern
4. **Sitemap and wireframes** in Relume, then a first design pass in Lovable
5. **Critique and iteration:** simplified navigation and hero, clearer hierarchy, more white space, photo-led treatment cards, a dedicated before and after section, and a trust section built on outside proof
6. **Final build** in HTML and CSS with brand colours and motion inspired by modern Framer templates

## Key design decisions

- **Doctor-led message first.** The hero states what the clinic does and shows trust (rating, experience, awards) right next to the booking button
- **Treatments by concern.** Four categories with verified starting prices
- **Proof before asking.** Doctor credentials, before and after results, and real Google review excerpts appear before the final booking section
- **One primary action.** "Book a Consultation" is always reachable, including a sticky bar on mobile
- **Accessible by default.** Readable text sizes, strong contrast, zoom allowed, and all motion turns off for people who choose reduced motion

## Content notes

- **Prices** come from the clinic's public website. Services without published prices are marked "Pricing at consultation"
- **Review excerpts** are short, unedited quotes from public Google reviews. Surnames are shortened to initials
- **Images:** the doctor portrait, hero photo and before and after photos are AI-generated or stock images used as stand-ins. They do not show real Bloom patients or staff. The treatment card and avatar photos are stock images
- The clinic name and logo belong to Bloom Laser Clinic and are used here only to present this concept

## Tech

A single self-contained `index.html` file. HTML, CSS and a small amount of vanilla JavaScript, with no build step. Fonts from Google Fonts.

## Author

Ariq Ahmed Chowdhury, UI/UX designer
