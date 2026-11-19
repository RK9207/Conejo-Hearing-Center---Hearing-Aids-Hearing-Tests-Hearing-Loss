# IMAGE_PROMPTS.md

**Conejo Hearing Center · Hearing Tests & Hearing Aids landing page · Step 4B · November 19, 2026**

This file covers the four intentional placeholders in `index.html`. Search the file for `data-img-id` to find them. The Services, Reviews, FAQ, final CTA, and footer sections have no placeholders by design, so they have no prompts here.

If Step 5 changes a section's layout or visual purpose, update that entry here as well, so the file doesn't go stale.

| ID | Section | Source decision | Recommended option |
|---|---|---|---|
| IMG-HERO-01 | Hero | AI lifestyle/editorial appropriate. Check the licensed clinic stock first. | Option 1: Dinner-table conversation |
| IMG-PROVIDER-01 | Meet Your Audiologists | **REAL PROVIDER IMAGE REQUIRED** | Option 1: AI edit of the existing real headshot |
| IMG-PROVIDER-02 | Meet Your Audiologists | **REAL PROVIDER IMAGE REQUIRED** | Same option chosen for PROVIDER-01 |
| IMG-CLINIC-01 (optional) | Location | **REAL CLINIC / GBP IMAGE PREFERRED** | Option 1, or remove the frame |

---

## Global rules for every image on this page

**Authenticity rules** come from DESIGN_SYSTEM and CONTENT_DIRECTION.
- Never generate a face that will be presented as Christine Wilson, Dr. Roya Razin, staff, or real patients.
- Never generate an image that will be presented as the real office, interior, or equipment.
- AI lifestyle imagery is allowed only as a generic illustration of everyday conversation.
- No image may imply a guaranteed outcome. Hero scenes show everyday listening moments, not "before and after" results.
- Hearing aids may appear subtly, but not as a hero product shot. No visible brand marks.

**Palette harmony** follows DESIGN_SYSTEM.
- The page uses navy `#0b3951`, pale blue `#e4eef7`, sky `#38aae8`, and white, with lime `#aad23c` reserved for the call button.
- Images should lean warm-neutral, with soft blues, denim, and cream.
- Avoid large areas of saturated lime or yellow-green, which would compete with the CTA.
- Avoid heavy orange casts.

**Shared negative prompt.** Append this to every AI prompt:
> no text, no letters, no logos, no brand names, no watermarks, no signage added, no medical charts on screen, no stethoscopes, no hospital beds, no surgical masks, no exaggerated laughter, no grimacing or visible distress, no hands cupped to ears, no direct eye contact with the camera, no plastic or airbrushed skin, no extra or merged fingers, no warped glassware or cutlery, no duplicated faces, no fisheye distortion, no HDR look, no oversaturated colors

**Export**
- Generate at roughly 2× the placeholder size, then export WebP at the placeholder dimensions listed in each entry.
- Keep the file names matched to the IDs, for example `img-hero-01.webp`.
- Set `width` and `height` attributes on the `<img>`. The page code comments already include them.

---

## IMG-HERO-01 - Hero

### Placeholder purpose

The hero image sits beside the H1 "Hearing Tests & Hearing Aids in Westlake Village" on desktop, and appears after the call actions on mobile. It needs to make the hero lead line feel familiar: "Missing words at dinner, or turning up the TV to follow the dialogue?"

The image shows **why getting checked matters**: ordinary conversation with people you care about. It must feel warm, local, and real, and should support the call action rather than compete with it. It doesn't need to carry copy, because no text sits on top of it.

### Recommended source type

AI-generated lifestyle/editorial image appropriate.

Before generating anything, check whether the clinic's licensed stock can be reused on this landing page. RESEARCH §9 lists `shut-hear-be-heard.jpg` (dinner toast) and `shut-why-hearing-tested.jpg` (couple on couch). If those licenses cover this use and the crops work at 5:4, they are an acceptable alternative.

### Recommended composition

- **Aspect ratio:** 5:4 landscape. Final export 1200 × 960. Generate around 2400 × 1920.
- **Subject placement:** Primary faces in the left-center to center of the frame, angled slightly toward the left so they turn toward the headline and copy column on desktop. Keep the primary faces within the middle 60% of the frame.
- **Negative space:** None is needed for copy. Keep some soft, uncluttered background at the right and top edges so the image breathes next to the dense hero text column.
- **Crop:** At mobile width (about 350px), the frame renders roughly 350 × 280. At that size, two faces must still read clearly. That means a maximum of three people, with two primary faces large enough to read. Avoid wide group shots.
- **Desktop vs mobile:** The 12px rounded corners will trim the edges slightly. Keep hands, glasses, and faces at least 6% inside each edge.

### Option 1 - Dinner-table conversation (everyday moment)

> Warm, candid editorial lifestyle photograph, 5:4 landscape. Three adults share an unhurried weeknight dinner at a home dining table in a light-filled Southern California home. The main subject is a woman in her late 60s with natural silver hair, seated center-left. She leans slightly toward a man in his early 70s across the corner of the table, attentively following what he's saying, with a soft, genuine half-smile. He is mid-sentence, gesturing lightly with one hand. A third adult in their 40s sits partly out of focus at the right edge, adding a sense of family. Faces are angled three-quarter toward the left of the frame. Wardrobe is relaxed and real: a soft cream knit sweater, a chambray shirt, a muted navy cardigan. On the table is a simple home-cooked meal, water glasses, and a linen napkin, with nothing staged or abundant. Late-afternoon window light comes from the left, warm but natural, with gentle falloff into a soft-focus background of a plain light wall and a hint of greenery through a window. Shot on a 50mm lens at f/2.8, eye-level, shallow depth of field with both main faces sharp. The color mood is warm neutrals with muted denim blues, with realistic skin texture and natural wrinkles. The emotional tone is connection and attentiveness, not celebration. Healthcare advertising editorial style, photorealistic, unposed. No text, no logos, no visible hearing devices.

### Option 2 - Parent and adult child in the kitchen (family-helper angle)

> Natural editorial photograph, 5:4 landscape. In a bright, lived-in home kitchen, a man in his mid-70s sits on a stool at a kitchen island, turned toward his daughter, a woman in her late 40s, who stands beside him holding a coffee mug. She is speaking warmly. He leans in slightly with his head turned a little to catch her words, looking engaged and relaxed rather than struggling. Both are positioned left-of-center, faces in three-quarter profile, clear and sharp. Wardrobe is everyday: a soft gray crewneck and khakis for him, a light blue button-down with rolled sleeves for her. Soft morning daylight comes from a window behind and to the right, giving a gentle rim light. Clean but realistic countertops with a fruit bowl and a folded dish towel, without staging. Shot on a 35mm–50mm lens at f/3.2, waist-up framing, shallow depth of field so the cabinets fall into soft cream and pale blue tones. The color mood is airy whites, pale blue, and natural wood. The emotional tone is a quiet, caring moment between family, conveying "let's look into this together." Photorealistic, candid, healthcare lifestyle advertising. No text, no logos, no visible hearing devices.

### Option 3 - Evening TV and conversation in the living room (premium editorial)

> Premium editorial lifestyle photograph, 5:4 landscape. A couple in their late 60s sit together on a comfortable linen sofa in a calm, tastefully simple living room at early evening. The woman, seated center-left, has turned away from the television (out of frame to the right) to answer something her husband said. They share an easy, amused look at each other, with relaxed shoulders and natural posture. A single small behind-the-ear hearing aid is barely visible on the man's left ear, neutral beige, no logo. It's an incidental detail, not the focus. Wardrobe is a soft oatmeal sweater and a navy quarter-zip. Warm practical lamp light mixes with cool blue dusk light from a window, giving a gentle two-tone mood that echoes the page's navy and pale blue palette. Shot on an 85mm lens at f/2.2, seated eye-level, faces sharp, background softly blurred with a bookshelf and a plant. No TV screen visible. Muted, sophisticated color grade with fine film-like grain and realistic skin. The emotional tone is comfort and ease at home. Photorealistic, unposed, high-end healthcare editorial. No text, no logos, no brand marks on any device.

### Recommended option

**Option 1: Dinner-table conversation.**

It mirrors the hero lead line ("Missing words at dinner") directly, and it fits PAGE_STRATEGY's call for "one warm conversation image." It shows the everyday listening moment that motivates a test, without implying a hearing aid outcome. The three-quarter left-facing composition also turns the subjects toward the headline and call button on desktop.

Option 2 is the strongest alternative if the Ads team confirms family members as a major audience. Option 3 includes a visible device, so use it only if Step 5 decides the hero should lean toward hearing aid shoppers. Even then, keep the device incidental.

### Real-image note

AI is appropriate here because the image is a generic illustration of everyday conversation, not a depiction of real patients or the clinic. Two conditions apply:
- Don't present the people as Conejo Hearing Center patients in alt text or captions.
- Check the clinic's licensed Shutterstock images first, since already-licensed, on-brand stock keeps the landing page visually consistent with conejohearingcenter.com.

Suggested alt text: *Older adults sharing a relaxed conversation over dinner at home.*

---

## IMG-PROVIDER-01 - Meet Your Audiologists (Christine Wilson, M.S., CCC-A)

### Placeholder purpose

This image puts a real, recognizable face to "Owner and Audiologist, licensed since 1999." Per DESIGN_SYSTEM, the provider portraits are the page's second visual peak. They need to make a phone call feel like contacting a person the visitor has already "met."

Reviews on the page name Christine directly ("especially Christine"), so an authentic photo lets visitors connect the review with the person.

### Recommended source type

Real provider/team image preferred. In practice, a real image is **required**. Pull the existing headshot from `conejohearingcenter.com/team/christine-wilson/` or the WordPress Media Library, or schedule a new photo.

The three options below are not prompts to invent her likeness. Each one is an AI edit instruction applied to her real photo, a shoot brief for a real photo, or a background plate for compositing her real photo. Any AI edit must leave her face, features, skin, age, hair, and expression unchanged.

### Recommended composition

- **Aspect ratio:** 4:5 portrait. Final export 800 × 1000.
- **Display size:** About 260px wide on desktop and 240px on mobile.
- **Subject placement:** Head and shoulders, centered horizontally. Eyes at roughly the upper third (35–38% from the top). Leave about 8–10% headroom above the hair, and crop mid-chest.
- **Negative space:** A minimal, even, soft background with no busy detail. The name and credentials sit as text below the image, not on it.
- **Crop:** Must match IMG-PROVIDER-02 exactly: same eye line, head size (head roughly 40–45% of frame height), background tone, and lighting direction. The two are shown side by side at equal weight.
- **Desktop vs mobile:** The same crop works for both. Avoid tight crops that clip the hair at small sizes.

### Option 1 - AI edit of the existing real headshot (recommended workflow)

> Image-editing instruction (use with the real headshot of Christine Wilson as the input image; do not generate a new person). Preserve the subject's face, facial features, skin texture, age, hairstyle, hair color, glasses if present, expression, and clothing exactly as in the original photograph. Do not smooth, slim, de-age, or beautify. Recompose to a 4:5 portrait, head-and-shoulders, centered, with eyes at about 36% from the top and modest headroom. Extend the canvas naturally if needed, continuing the existing clothing realistically. Replace the background with a soft, evenly lit, slightly out-of-focus studio backdrop in pale blue-gray close to #e4eef7, with a very gentle lighter glow behind the head. Balance the lighting to soft, flattering frontal window light from camera left, matching the original direction. Neutral, true-to-life color, realistic skin tones, crisp eyes. No text, logos, or added accessories.

### Option 2 - Real environmental portrait shoot brief (in-office)

> Photography brief for a real portrait session at the Westlake Village office. Subject: Christine Wilson, owner and audiologist. Setting: her own consultation room or a quiet hallway with soft natural light. The background should be plain and softly blurred, with no visible patient information, screens, paperwork, or equipment branding. Wardrobe: her usual professional clinic attire. A solid mid-tone or navy top suits the page palette. Avoid busy patterns and bright lime or green. Pose: seated or standing at a slight three-quarter angle toward camera left, shoulders relaxed, a natural, approachable closed- or slightly open-mouth smile, looking just past or into the lens. Lighting: large window or softbox at 45° camera left, white bounce camera right, no harsh shadows. Lens: 85mm at f/2.8, chest height, background at least 1.5m behind the subject. Capture several frames, then crop to 4:5 with the eyes at the upper third. The same setup, distance, and framing must be repeated for Dr. Razin.

### Option 3 - AI background plate for compositing real cut-outs

> Generate an empty background plate with no people, 4:5 portrait, 1600 × 2000. A softly defocused, calm professional office interior suggesting a modern audiology practice without any identifiable equipment: a warm white wall, a hint of a pale blue-gray accent wall, a blurred potted olive tree or soft greenery at one edge, and gentle natural window light from the left. Very shallow depth of field, as if shot at 85mm f/1.8, so everything is creamy bokeh with no readable shapes. Color palette is pale blue #e4eef7, warm white, and soft sage. Even exposure across the center, where a head-and-shoulders subject will be composited. No text, no logos, no medical devices, no furniture edges crossing the center. Photorealistic. (Composite Christine's real cut-out photo onto this plate, then reuse the identical plate for Dr. Razin.)

### Recommended option

**Option 1: AI edit of the existing real headshot.**

It's the fastest path that keeps the image authentic, uses a photo the clinic already approved, and makes it easy to produce a matching pair with Dr. Razin through the same background and crop treatment.

Use Option 2 if the existing headshots are low-resolution, outdated, or shot in mismatched styles. Option 3 is a fallback for matching two very different source photos.

### Real-image note

**REAL PROVIDER IMAGE REQUIRED.**

A generated face presented as a named, credentialed audiologist would misrepresent the provider, so it is never acceptable here. A real photo also builds more trust: visitors may meet Christine in person, and patients mention her by name in reviews.

Get the clinic's approval of the final edited version before publishing.

Suggested alt text: *Christine Wilson, M.S., CCC-A, owner and audiologist at Conejo Hearing Center.* Never title her "Dr."

---

## IMG-PROVIDER-02 - Meet Your Audiologists (Dr. Roya Razin, Au.D.)

### Placeholder purpose

This image gives equal visual weight to the second audiologist, so visitors know they may see either provider. It reinforces the "Doctor of Audiology" credential with a real face. It must read as a matched pair with IMG-PROVIDER-01, so the section feels like one team rather than two unrelated photos.

### Recommended source type

Real provider/team image preferred. In practice, a real image is **required**. Pull the existing headshot from `conejohearingcenter.com/team/roya-razin/` or the Media Library, or photograph her in the same session as Christine. The options below follow the same rules as PROVIDER-01: edit, shoot brief, or plate only, with no invented likeness.

### Recommended composition

- **Aspect ratio:** 4:5 portrait. Final export 800 × 1000.
- **Matching:** Identical framing rules to IMG-PROVIDER-01: eyes at about 36% from the top, head about 40–45% of frame height, same background tone and light direction.
- **Treatment:** Whichever option is chosen for PROVIDER-01 must be used here too. Don't mix an in-office shot with a studio backdrop.
- **Pair balance:** If the two source photos differ in brightness or color temperature, correct this one to match PROVIDER-01, not the other way around.
- **Desktop vs mobile:** Shown side by side on desktop and stacked on mobile, so consistent head size matters most on desktop.

### Option 1 - AI edit of the existing real headshot (matched to PROVIDER-01)

> Image-editing instruction (use with the real headshot of Dr. Roya Razin as the input image; do not generate a new person). Preserve the subject's face, facial features, skin texture, age, hairstyle, hair color, glasses or jewelry if present, expression, and clothing exactly as photographed. No retouching beyond minor exposure and color balance. Recompose to a 4:5 head-and-shoulders portrait matching the reference crop of IMG-PROVIDER-01: eyes at about 36% from the top, same head size and headroom. Extend the canvas naturally if required. Replace the background with the same soft, evenly lit pale blue-gray studio backdrop (#e4eef7) with a gentle lighter glow behind the head, identical to the PROVIDER-01 edit. Match the lighting direction (soft window light from camera left), contrast, and white balance to PROVIDER-01 so the two portraits read as one set. Realistic skin tones, sharp eyes, no text, no logos.

### Option 2 - Real portrait in the same session (pair-consistent shoot)

> Photography brief, same session and setup as Christine Wilson. Subject: Dr. Roya Razin, audiologist. Use the identical location, backdrop distance, light positions (key at 45° camera left, bounce camera right), lens (85mm at f/2.8), camera height (chest level), and white balance as the PROVIDER-01 shoot, with settings recorded and locked between subjects. Wardrobe: professional clinic attire in a solid tone that differs from Christine's but sits in the same family, for example a soft blue or charcoal if Christine wears navy. Avoid bright greens, busy prints, and large logos. Pose: a slight three-quarter angle, mirrored toward camera right, so the pair face gently inward toward each other on desktop. Relaxed shoulders and a warm, natural expression. Crop to 4:5 with matching eye line and head size, and review both portraits side by side before choosing frames.

### Option 3 - Shared AI background plate (composite consistency)

> Use the exact background plate generated for IMG-PROVIDER-01 Option 3, unchanged. If generating fresh, use this identical prompt and seed: an empty 4:5 portrait background plate, 1600 × 2000, a softly defocused calm professional office interior, warm white wall with a hint of pale blue-gray accent, blurred greenery at the right edge (mirrored from PROVIDER-01's left-edge greenery for a facing-pair effect), gentle natural window light, extremely shallow depth of field at 85mm f/1.8, palette pale blue #e4eef7, warm white, and soft sage, no people, no text, no logos, no medical equipment, nothing crossing the center. Photorealistic. Composite Dr. Razin's real cut-out with the same scale, eye line, and edge feathering as Christine's.

### Recommended option

**Option 1, matched to PROVIDER-01.**

Consistency between the two portraits matters more than which treatment is chosen. Using the same edit pipeline on both existing headshots produces an equal-weight pair quickly. If a new shoot happens for either provider, shoot both together using Option 2.

### Real-image note

**REAL PROVIDER IMAGE REQUIRED.**

Same reasoning as PROVIDER-01. A generated likeness of a named doctor is not acceptable, and visitors expect the face they see to be the person they'll meet.

Suggested alt text: *Dr. Roya Razin, Au.D., audiologist at Conejo Hearing Center.*

---

## IMG-CLINIC-01 - Location (optional)

### Placeholder purpose

This image helps a first-time visitor **recognize the building and entrance** at 699 Hampshire Road, Suite 215, so arriving feels easy. It also adds local authenticity next to the address, hours, and map, reassuring visitors that there's a real, reachable office.

The placeholder is optional. The location section works without it, and the code comment says to remove the frame if no authentic photo exists.

### Recommended source type

Real clinic/GBP image preferred.

RESEARCH §9 notes that no exterior or interior photos exist on the client site. The Google Business Profile and Yelp listings show photos, so request authorized GBP images from the client.

### Recommended composition

- **Aspect ratio:** 16:9 landscape. Final export 1200 × 675.
- **Display size:** About 430px wide on desktop (beside a 4:3 map) and full container width on mobile.
- **Subject:** The building entrance or a recognizable façade, centered to slightly left. Include the walkway or approach so visitors understand where to go. Real building signage may appear if it exists, but nothing should be added.
- **Negative space:** Some sky or landscaping at the top and edges is fine. No text overlays.
- **Crop:** Keep the entrance within the center 70%, because the 12px rounded corners trim the edges. Avoid parked cars with readable license plates. Blur or crop out any people who are identifiable.
- **Desktop vs mobile:** At full width on mobile the image becomes more prominent. Check that the entrance is still the clear focal point.

### Option 1 - AI clean-up and recrop of the real GBP exterior photo

> Image-editing instruction (use the client-authorized Google Business Profile photo of the Conejo Hearing Center building as input; do not invent architecture). Keep the building, entrance, windows, landscaping, real signage, and surroundings exactly as photographed, with no added, removed, or altered signage, text, or architectural features. Recompose to 16:9 landscape with the main entrance centered to slightly left and the approach walkway visible. If the original is too tight, extend sky or ground naturally. Correct the perspective so vertical lines are straight. Balance the exposure to a bright, clear midday Southern California look with true-to-life color, slightly lifting shadows under overhangs. Remove only temporary distractions such as a trash bin, parking cones, or a lens flare. Blur any identifiable people and license plates. Photorealistic, no added text or logos.

### Option 2 - Real arrival-view photography brief

> Photography brief for the client or a local photographer. Location: 699 Hampshire Road, Westlake Village, the building that houses Suite 215. Shot: the view a first-time patient sees when walking from the parking area to the entrance they should use. Time: mid-morning on a clear weekday during office hours (9:00 a.m.–4:30 p.m.), with soft, even sun and no harsh noon shadows across the door. Camera at standing eye level, 24–35mm lens, f/8 for full sharpness, with verticals kept straight. Frame in 16:9 with the entrance centered to slightly left and a short stretch of walkway leading in from the lower edge. Include existing building signage or the suite directory only if it's real and permanent. Avoid identifiable people and readable license plates. If there's a lobby directory or elevator, take one extra frame of it for possible use in directions, but don't publish parking, floor, or accessibility details until the client confirms them.

### Option 3 - Generic "arriving for an appointment" lifestyle fallback (not presented as the clinic)

> Editorial lifestyle photograph, 16:9 landscape. A woman in her late 60s walks unhurriedly along a sunlit, landscaped walkway toward a low-rise, contemporary professional office building, accompanied by her adult son in his 40s. They're seen from a three-quarter rear angle, faces partly visible, chatting easily. The setting suggests suburban Southern California: drought-tolerant plantings, a mature oak or olive tree, warm stucco and glass, soft golden-hour light, and a calm blue sky. The building is generic and anonymous, with no signage, no text, no logos, no suite numbers, and no recognizable landmark. Shot on a 35mm lens at f/4, subjects slightly left of center, generous space ahead of them toward the right. Warm, natural color grade with soft blues. The mood is calm, practical, and reassuring. Photorealistic, not staged. Use only as a generic illustration, never captioned or alt-tagged as Conejo Hearing Center's office.

### Recommended option

**Option 1: clean-up of the real GBP exterior,** or Option 2 if no usable GBP photo exists.

The job of this image is recognition, so only the real building can do it. If neither real source is available before launch, **remove the frame** rather than using Option 3.

A generic building next to a specific street address could make visitors expect a different-looking office. Treat Option 3 as a last-resort mood image only if Step 5 decides the location column visually needs it. If it's used, its alt text must stay generic.

### Real-image note

**REAL CLINIC / GBP IMAGE PREFERRED.**

Visitors use this image to find the office, so an AI building would actively mislead them. Real GBP photos also match what searchers see on Google Maps, which reinforces that the page and the listing are the same trusted practice.

Confirm the client's rights to any GBP photos uploaded by users rather than by the owner.

Suggested alt text (real photo): *Entrance to the Conejo Hearing Center office building on Hampshire Road, Westlake Village.*
Option 3 fallback: *An older woman and her son walking toward an office building.*

---

## Open items for Step 5

1. Confirm the reuse license for the clinic's Shutterstock and Getty images (RESEARCH §9) before generating the hero.
2. Obtain the provider headshot files, and confirm the clinic approves AI background and crop edits to them.
3. Request authorized GBP exterior photos. Decide whether IMG-CLINIC-01 stays or the frame is removed.
4. If Step 5 adds an optional fitting or Real Ear Measurement visual to the Services section (DESIGN_SYSTEM allows one "sparingly" when it improves comprehension), add a new entry here first. A real in-clinic photo, or an accurate diagram reviewed by the audiologist, is required. Don't use an AI-generated "procedure in progress" image.
