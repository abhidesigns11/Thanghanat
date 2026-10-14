# Thanganat 2026 — items only the organisers can confirm

This is a working checklist, not legal advice. Have the Rotary Club of Vapi (and ideally a lawyer) approve the policy pages before launch.

## Confirm or fill in
1. **Contact email and full postal address (with PIN).** The policies currently give the helpdesk phone numbers and the ROFEL College Office address only. A written contact (email) and a named grievance person are strongly recommended under the DPDP Act and the IT Rules.
2. **Beneficiary and use of funds.** The site now says funds are "intended to support" Haria L.G. Rotary Hospital. Confirm this is accurate. The old "100% of proceeds" and 70/20/10 allocation claims contradicted each other and were removed. Only re-add a figure you can prove.
3. **Refund Policy defaults.** I drafted: no refund once issued, full refund if the festival is cancelled, per-night refund if a night is cancelled, 7 days to ask, 15 working days to pay. Replace with your real rules.
4. **Privacy defaults.** 90-day deletion after the festival, 30-day reply target. Replace with what you will really do.
5. **Governing court.** Terms say courts at Vapi, Gujarat. Confirm.
6. **District 3060 and the "club of" wording.** I could not verify this online. Confirm.
7. **Artists.** Get written permission or a booking confirmation to use each artist's name. I removed the "India's Got Talent runner-up" claim because I could not verify it.
8. **Safety and ground claims.** First aid, ambulance, parking, seating, drinking water and gate arrangements are still on the site in softened form. Remove any that will not actually be provided.
9. **Stall price.** Rs 40,000 — state whether GST/taxes are included.
10. **Judging criteria and prizes.** The 40/30/20/10 scoring is still shown. Confirm it is the real rule.

## Photos, videos and copyright (biggest remaining risk)
- All photos and reels show identifiable people, including children. No licence or consent record exists in the files (EXIF is stripped). Get consent or releases, or blur/remove images of children. Keep a record.
- Aerial footage is credited to **Sun Creators**. Get written permission to use it.
- Confirm who owns each photo and reel (photographer or videographer) and that the club may publish them.
- The logo uses the Gujarati word for Rotary. Check Rotary International's brand guidelines for club use of the name and emblem.

## Event-level risks (not website code)
- Music: a public Garba event usually needs IPRS and PPL licences for the songs played.
- Children's competition (under 14): collect parent/guardian consent for entry and photos.
- Event permissions: police, fire, and municipal/GIDC permission for the ground, crowd limits and insurance.
- Charity: if you mention tax benefits, you need valid 12A/80G registration. The site currently makes no tax claim.

## Deployment
- Google Fonts is still loaded from Google (visitors' IP goes to Google). To remove it, download the three font families, host them in `media/` and update the font link and CSP (`style-src`/`font-src`).
- `og:image` is a relative path. Use the full `https://your-domain/media/og.jpg` once the domain is known.
- If you ever add analytics, forms, maps or YouTube embeds: update the Privacy and Cookie policies, add a consent banner, and add consent text next to any form.
- If you add a form later, include this next to the submit button: an unticked checkbox "I agree to the Privacy Policy and consent to the Rotary Club of Vapi using my details to reply to this enquiry", plus only the fields you really need.

## DPDP Act, 2023 status (as of 14 Oct 2026)
The DPDP Rules were notified on 13 Nov 2025. Obligations switch on in phases (consent-manager rules around Nov 2026; most notice, consent, children and breach duties by about 13 May 2027). The policy is written to that standard already.
