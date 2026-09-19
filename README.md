# CampusBanter legal pages

`terms.html` and `privacy.html` are drafts with no personal details in them: the operator is "the CampusBanter team"
and the only contact is Support.ProjectZ@gmail.com. Have a lawyer review them before you publish — they are a starting
point, not legal advice.

## Host them free with GitHub Pages
1. Create a public GitHub repo (e.g. `campusbanter-legal`) and upload `terms.html` and `privacy.html`.
2. Repo → Settings → Pages → Deploy from branch `main` / root.
3. Your URLs will be `https://<your-username>.github.io/campusbanter-legal/terms.html` and `.../privacy.html`.
4. Put them in `CampusBanter/Services/AppConfig.swift` (`termsURL`, `privacyURL`) and in App Store Connect
   (Privacy Policy URL is required).

## App Store privacy labels (App Store Connect → App Privacy)
Declare, all "Linked to you", **not** used for tracking:
- Contact Info → Email Address (App Functionality)
- User Content → Other User Content (App Functionality)   (posts, comments, messages)
- Identifiers → User ID (App Functionality)
Everything else: "No". Update this if you later add analytics or crash reporting.
