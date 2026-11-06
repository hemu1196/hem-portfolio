# Hema Chandra — 10 Project Portfolio Showcase

## What changed
- Replaced the Projects section with a 10-project showcase inspired by the layout image.
- LifeLink is the first, wide featured project.
- Every project has its own sequence number, category, feature summary and technology stack.
- Repository and Live Demo actions are separate where a live demo URL was supplied.
- Existing overall portfolio sections and theme are retained.

## LifeLink
The LifeLink entry is based on the public repository README and source structure:
- React frontend
- FastAPI / Python backend
- Donor, hospital, blood-bank and admin experiences
- Emergency blood board, donor matching, eligibility/compatibility, inventory and analytics
- JWT-based authentication described in the README

GitHub: https://github.com/hemu1196/LifeLink

No public deployed LifeLink demo URL was listed in the repository README when this update was prepared. Therefore the card does not falsely claim that a live demo exists. The secondary action points to the repository and is labelled “Live demo unavailable”.

## Project screenshot assets
- `medguard-dashboard.png` is your real uploaded MEDGUARD screenshot.
- The other project preview PNGs are custom visual concepts generated for this portfolio. They are illustrative mockups, not verified screenshots of deployed applications.
- You can replace any illustrative preview PNG with a real project screenshot while retaining its filename.

## Useful screenshot capture list
- LifeLink: home/emergency board, donor dashboard, hospital request view, blood-bank inventory, analytics.
- MEDGUARD: home dashboard, SOS, AI assistant, Vault, medication screens.
- EventHub: home, event detail, registration/checkout, ticket screen.
- Construction Hub: approved dashboard / risk monitoring screenshots.
- Insurance prediction: Streamlit input and prediction output.
- Attendance: Admin dashboard and attendance list.
- Netwalk: gameplay.
- Robotics: real hardware photo.
- Hotel: booking/billing screen.
- University: role selection or dashboard.

## Deployment
Keep `index.html` and the `assets` folder together. Upload the whole directory to your static hosting provider.


## Image display correction
The latest CSS update uses `object-fit: contain` for all project previews,
preserving the complete screenshot without cropping or stretching. The project
grid uses three columns on wide screens, two on tablets, and one on phones.
The MEDGUARD portrait screenshot is kept in full.


## Compact thumbnail polish
Project preview images are intentionally displayed smaller and centered inside
a consistent preview stage. Images use contain sizing to avoid cropping,
stretching, or filling the card with enlarged blurry artwork. LifeLink uses a
compact featured preview; MEDGUARD's portrait screenshot remains uncropped.
