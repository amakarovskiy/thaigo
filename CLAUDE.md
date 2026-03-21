# Monte Rehab — Complete Website Redesign Brief
# Version: FINAL (all 16 pages, all texts, all images)

---

## HOW TO USE THIS BRIEF

1. You have three reference files:
   - `CLAUDE.md` — this file (content + rules)
   - `mockup-home.html` — exact visual template for `index.html`
   - `mockup-inner.html` — exact visual template for all other 15 pages

2. Your job: produce 16 `.html` files.
   - `index.html` → copy CSS/layout from `mockup-home.html`, fill in content from this brief
   - All other 15 files → copy CSS/layout from `mockup-inner.html`, fill in content from this brief

3. **Do not invent any design.** Reuse the CSS variables, typography, component classes, and layout structure from the mockups exactly. Only swap out content.

---

## DESIGN TOKENS (already in mockups — do not change)

```css
--sage: #6b9478;  --sage-mid: #7fa88c;  --sage-light: #a3bfaa;
--sage-pale: #eaf2ec;  --sage-xpale: #f3f8f4;
--warm: #c8a066;  --warm-light: #f2e8d5;  --earth: #6b5540;
--ink: #1a2318;  --ink-mid: #2d3d2f;  --mist: #f8f6f2;  --white: #ffffff;
Headings: Cormorant Garamond (300/400/500/italic)
Body: DM Sans (300/400)
```

---

## SHARED NAV (identical on all 16 pages)

```
Logo: MonteRehab   (Monte in ink, Rehab in --sage)

Nav links:
- Home → index.html
- Eating Disorders ▾
    Residential treatment → residential_treatment.html
    Group therapy online  → group_therapy.html
- Addiction ▾
    Alcohol addiction              → alcohol_addiction.html
    Drug addiction                 → drug_addiction.html
    Medical detox                  → medical_detox.html
    Behavioural addiction treatment → behavioural_addiction_treatment.html
    Dual diagnosis                 → dual_diagnosis.html
- Mental Health ▾
    Anxiety treatment       → anxiety_treatment.html
    Depression treatment    → depression_treatment.html
    Executive burnout       → executive_burnout.html
    Insomnia treatment      → insomnia_treatment.html
    Mood disorder treatment → mood_disorder_treatment.html
    PTSD and trauma treatment → ptsd_and_trauma_treatment.html
- Pricing    → pricing.html
- Contact us → contacts.html

Right side:
  EN | RU | ME
  +382 69 621 111  (tel:+38269621111, sage serif)
  [Get in touch]   → contacts.html  (btn-sage)
```

---

## SHARED MESSENGER ICONS (original Tilda assets — use on all pages)

```
WhatsApp: https://thb.tildacdn.com/tild6237-6666-4037-a363-386236386262/-/resize/40x/whatsapp.png
Telegram: https://thb.tildacdn.com/tild3062-3034-4539-b463-313364613266/-/resize/40x/TG.png
Viber:    https://thb.tildacdn.com/tild6161-6534-4930-b165-363338373665/-/resize/40x/pngwingcom.png
```

---

## SHARED CONTACT FORM (id="enquiry", on all 16 pages)

```
Heading:    Contact us and start your recovery journey today
Subheading: Please input your name and e-mail address and we will be in touch
Fields:     Name (text input), E-mail (email input)
Checkbox:   I agree to share my details with monterehab.com
Button:     Submit
```

---

## SHARED FOOTER SEO LINKS (4 columns, identical on all 16 pages)

```
Col 1 — REHABILITATION PROGRAM FOR ALCOHOLICS
  Treatment of addictions → /addiction_treatment
  Treatment of chronic alcoholism → /chronic_alcoholism
  Treatment of binge alcoholism → /conclusion_from_drinking
  Treatment of secret alcoholism → /secret_alcoholism
  Treatment of beer alcoholism → /beer_alcoholism
  Treatment of female alcoholism → /female_alcoholism
  Treatment of domestic alcoholism → /household_alcoholism
  Permanent alcoholism → /permanent_alcoholism

Col 2 — REHABILITATION PROGRAM OF NON-CHEMICAL ADDICTIONS
  Treatment of Internet addiction → /internet_addiction
  Treatment of gaming addiction → /gaming_addiction
  Treatment of gambling addiction → /gambling_addiction
  Treatment of sexual, love addiction — sexaholism → /sexual_obsession
  Treatment of shopaholism → /shopaholism

Col 3 — REHABILITATION FOR EATING DISORDERS
  Treatment of anorexia → /anorexia
  Treatment of bulimia → /bulimia
  Treatment of addiction to sweets → /sugar_addiction
  Treatment of dependence on stimulating and energy drinks → /energy_drink_addiction

Col 4 — REHABILITATION PROGRAM FOR DRUG ADDICTS
  Treatment of heroin addiction → /heroin_addiction
  Treatment of codeine addiction → /codeine_addiction
  Treatment of methadone addiction → /methadone_addiction
  Treatment of cocaine addiction → /cocaine_addiction
  Treatment of substance abuse → /substance_abuse
  Treatment of marijuana addiction → /marijuana_addiction
  Treatment of spice addiction → /spice_addiction
  Treatment of drug addiction → /drugs_addiction
  Treatment of salt addiction → /salt_addiction
  Treatment of amphetamine addiction → /amphetamine_addiction
  Drug addiction → /narco_addiction
  Clinic for the treatment of drug addiction and alcoholism → /clinic_drug_alcoholism
  Rehabilitation center for drug addicts → /drug_rehabilitation_center
  Drug Addiction Assistance Center → /addiction_treatment_center
  Addiction Treatment Clinic → /addiction_treatment_clinic
  Ecstasy Treatment → /ecstasy_addiction
  Treatment for tramadol → /tramadol_addiction
  Treatment of hashish addiction → /hashish_addiction
  Treatment of LSD addiction → /lsd_addiction
  Treatment for opiates → /opiate_addiction

Footer bottom:
  © All rights reserved    Privacy Policy → /privacy
```

---

## COMPLETE IMAGE REFERENCE TABLE

All Tilda CDN images — replace `/resize/20x/` with `/resize/800x/` for full resolution.

| File | Hero image URL (800px) |
|------|------------------------|
| index.html | https://images.unsplash.com/photo-1504701954957-2010ec3bcec1?w=1600&q=85 |
| residential_treatment.html | https://thb.tildacdn.com/tild6231-3738-4265-b133-336336636661/-/resize/800x/-.jpg |
| group_therapy.html | https://thb.tildacdn.com/tild6330-6664-4566-b634-313639353232/-/resize/800x/-_1.jpg |
| alcohol_addiction.html | https://thb.tildacdn.com/tild6535-3965-4636-b333-393762366530/-/resize/800x/3.jpg |
| drug_addiction.html | https://thb.tildacdn.com/tild3462-3633-4834-b931-366565616433/-/resize/800x/-.jpg |
| medical_detox.html | https://thb.tildacdn.com/tild3931-3162-4334-b563-643134396664/-/resize/800x/5.jpg |
| behavioural_addiction_treatment.html | https://thb.tildacdn.com/tild3463-6264-4566-b838-623162313561/-/resize/800x/photo.jpg |
| dual_diagnosis.html | https://thb.tildacdn.com/tild3562-3061-4465-a166-316633356234/-/resize/800x/3.jpg |
| anxiety_treatment.html | https://thb.tildacdn.com/tild3939-3731-4233-a461-376464363361/-/resize/800x/anxiety.jpeg |
| depression_treatment.html | https://thb.tildacdn.com/tild6334-6363-4932-b039-303062313130/-/resize/800x/deepr.jpeg |
| executive_burnout.html | https://thb.tildacdn.com/tild3437-3831-4635-a136-376162353131/-/resize/800x/burnout.jpeg |
| insomnia_treatment.html | https://thb.tildacdn.com/tild6630-3766-4266-b365-636533646334/-/resize/800x/insomnia.jpeg |
| mood_disorder_treatment.html | https://thb.tildacdn.com/tild3932-3364-4139-a162-353233626565/-/resize/800x/mood.jpeg |
| ptsd_and_trauma_treatment.html | https://thb.tildacdn.com/tild3837-6430-4666-b235-353432663466/-/resize/800x/ptsd.jpeg |
| pricing.html | https://images.unsplash.com/photo-1566073771259-6a8506099945?w=1600&q=85 |
| contacts.html | https://images.unsplash.com/photo-1506905925346-21bda4d32df4?w=1600&q=85 |

---

## PAGE CONTENT

---

### FILE 1: index.html
Template: mockup-home.html
Page title: Clinic for Addiction Treatment in Montenegro — MonteRehab

#### HERO
```
Headline:   Free life without addictions
Subline:    Let us help you get there
Button 1:   Let's start!         → #enquiry
Button 2:   Why it really works  → #rec836031031
```

#### SECTION: About (id="rec836031031")
```
H1: Rehabilitation center for addiction treatment in Montenegro
H2: We know your problem - It's not your fault

P1: If you are struggling with an addiction, it can feel like there is no way out. But that is not true! Many people have successfully overcome their addictions, and so can you. The most important thing is to never give up hope and to trust the experts at the rehabilitation center.

P2: The professionals at the center understand the complexities of addiction and can provide you with the skills and support you need to get better. With their help, you can break free from the chains of addiction and get back to living a healthy, productive life.

P3: So don't lose hope; reach out and get the help you need to get back on the path of recovery. The road may be tough and there may be bumps along the way, but with the support and guidance of the experts at the rehabilitation center, you can make it to the other side.
```

#### SECTION: How can we help?
```
Section heading: How can we help?

CARD 1 — Residential treatment:
  Our team will help you define your personal goals before you get started.
  Daily 1-to-1 therapy sessions lay the foundations for permanent positive change and help develop self-regulation skills.
  We conduct a full medical examination upon admission and provide individual support for comorbidities.
  We offer safe and intimate group classes online and offline to support recovery from rehabilitation and relapse prevention.
  CTA: Find out more → residential_treatment.html

CARD 2 — Online-therapy:
  Based on evidence-based best practices worldwide and 10 years of our own experience in treating ED, we present a unique online program.
  In just 3 years, 1,500 people completed the course, and 83% of them solved their problem and, as a result, significantly improved their quality of life.
  We have developed the first ED treatment solution that can replace traditional rehabs and residential centers.
  All you have to do is follow our expert advice and share your feedback with the team, we'll take care of the rest.
  CTA: Find out more → group_therapy.html
```

#### SECTION: Chemical addiction
```
Tag:  If you have a chemical addiction
H2:   We know what you have been through - and we are here to help

P1: The motto of our approach to addiction treatment is changing through acceptance, support, and professionalism.

P2: Every member of our rehab team has at least 6 years of professional experience. Another unique feature of our approach is that we work with people who know addiction from the inside, so we do not end up telling you how it should be, we understand the essence of your personal tragedy and help you get out of the maze of your own delusions, while holding your hand through it.

P3: XXI century is the time of medical, cognitive, and humanitarian technologies, so everything you need to do in order to get rid of your addiction is to get tired of it and start wanting to solve it.

P4: Montenegro Rehab is a safe space where you will be carefully surrounded by an atmosphere of comfort and acceptance.

Links (pill buttons):
  Alcohol addiction → alcohol_addiction.html
  Drug addiction → drug_addiction.html
  Medical detox → medical_detox.html
  Behavioural addiction treatment → behavioural_addiction_treatment.html
```

#### SECTION: Mental health
```
H2: Mental health
H3: Find the way to the real you and learn to love yourself again

P1: Our brain has never been subjected to such emotional stress in the history of mankind. While the human brain is probably the only device in the world right now that does not come with an instruction manual.

P2: Anxiety, depressions, and other mental health issues are signals our body sends to us, saying that we make our consciousness works in extreme modes. We all need to develop unique sets of rules in order to interact with our consciousness carefully.

P3: Our mental health experts will help you get your emotions, thoughts, and desires to meet with social attitudes that control your behaviour. The key to happiness and joy is to make one's conscious and subconscious move in the same direction.

Links (pill buttons):
  Anxiety treatment → anxiety_treatment.html
  Depression treatment → depression_treatment.html
  Executive burnout → executive_burnout.html
  Insomnia treatment → insomnia_treatment.html
  Mood disorder treatment → mood_disorder_treatment.html
  PTSD and Trauma treatment → ptsd_and_trauma_treatment.html
```

#### SECTION: Prices
```
H2: Prices

CARD 1:
  Title: Eurostandard (double occupancy)
  Price: from €6,000 / month
  • First month – €6,000, second and subsequent – €5,000
  • If you pay with a package of 3 months – the cost of the package is €15,000
  • Weekly boat trips, mountain tours and excursion
  CTA: Learn more → #enquiry

CARD 2:
  Title: Eurostandard (single occupancy)
  Price: from €9,000 / month
  • If you pay for 3 months – the cost of the package is €24,000
  • More than 8 hours of psychotherapy daily
  • 4 hours of family psychotherapy as a gift
  CTA: Learn more → #enquiry

CARD 3:
  Title: Individual program "Intensive"
  Price: from €12,000 / month
  • Accommodation in single apartments
  • Daily Personal Psychotherapy with a Program Manager
  • Accommodation on the territory of the center or independently in the nearest city
  • Daily attendance at compulsory events and meeting with the curator
  CTA: Learn more → #enquiry

CARD 4:
  Title: Resocialization and education
  Price: from €3,500 / month
  • Support in the process of education and employment
  • The ability to combine recovery with remote work
  CTA: Learn more → #enquiry
```

#### SECTION: Contact block (above form)
```
Address:  Sveti Stefan, Blizikuće 85315, Montenegro
Phone:    +382 69 621 111
Email:    montenegrorehab@gmail.com
WhatsApp: https://wa.me/38269621111
Telegram: https://t.me/+38269621111
Viber:    viber://chat?number=+38269621111
Maps:     https://maps.app.goo.gl/UnAUP4sconp1owWi9
```

---

### FILE 2: pricing.html
Template: mockup-inner.html (adapt: wider layout, no sidebar — full-width pricing cards, 2×2 grid)
Breadcrumb: Home → Pricing
Page title (hero h1): Pricing

```
CARD 1:
  Title: Eurostandard (double occupancy)
  Price: from €6,000 / month
  • First month – €6,000, second and subsequent – €5,000
  • If you pay with a package of 3 months – the cost of the package is €15,000
  • Weekly boat trips, mountain tours and excursion
  CTA: Learn more → #enquiry

CARD 2:
  Title: Eurostandard (single occupancy)
  Price: from €9,000 / month
  • If you pay for 3 months – the cost of the package is €24,000
  • More than 8 hours of psychotherapy daily
  • 4 hours of family psychotherapy as a gift
  CTA: Learn more → #enquiry

CARD 3:
  Title: Individual program "Intensive"
  Price: from €12,000 / month
  • Accommodation in single apartments
  • Daily Personal Psychotherapy with a Program Manager
  • Accommodation on the territory of the center or independently in the nearest city
  • Daily attendance at compulsory events and meeting with the curator
  CTA: Learn more → #enquiry

CARD 4:
  Title: Resocialization and education
  Price: from €3,500 / month
  • Support in the process of education and employment
  • The ability to combine recovery with remote work
  CTA: Learn more → #enquiry
```

---

### FILE 3: contacts.html
Template: mockup-inner.html (adapt: no sidebar — two-column layout: left=contact info, right=map)
Breadcrumb: Home → Contact us
Page title (hero h1): Contact us

```
LEFT COLUMN — Contact info:

  Heading: Contact us:
  Phone: +382 69 621 111  (tel: link)
  Email: montenegrorehab@gmail.com  (mailto: link)

  Messengers (use original Tilda icons):
    WhatsApp → https://wa.me/38269621111
    Telegram → https://t.me/RehabMontenegro
    Viber    → viber://chat?number=+38269621111

  Transfer info:
    From Europe: transfer 1000€ + transportation costs.
    From Montenegro: Free transfer.

  Legal information:
    D.o.o "ProfReab"
    Roman Konevichev
    UL. SVETOSAVSKA BB, BLIZIKUĆE BUDVA
    Registarski broj 50945727
    PIB 03332381

  Address: Sveti Stefan, Blizikuće 85315, Montenegro

RIGHT COLUMN — Map:

  Google Maps embed iframe:
    src: https://maps.google.com/maps?q=42.2527278,18.9060491&output=embed
    width: 100%, height: 400px, border: none

  Button below map:
    Text: Get directions
    URL: https://www.google.com/maps/dir//MonteRehab,+Sveti+Stefan,+Blizikuce,+Montenegro/@42.2527278,18.9060491,15z

NOTE: Footer on this page uses the same English SEO links as all other pages.
NOTE: No sidebar (pricing teaser, related links) — contacts page is standalone.
```

---

### FILE 4: residential_treatment.html
Template: mockup-inner.html
Breadcrumb: Home → Eating disorders → Residential treatment
Hero h1: Residential treatment
Hero image: (see image table)

```
LEAD PARAGRAPH:
You will be under the supervision of our team of professional and caring therapists in this full-cycle program.

P1: We offer an extremely rich psychotherapy program comparable to 3 years of ordinary supportive psychotherapy. The goal of treating any behavioral disorder is to change behavior patterns.

P2: Principles of the brain suggest that new patterns are most effectively developed when we find ourselves in a radically new environment, so our residential program is specially designed in a way you would feel comfortable to absorb everything we will be teaching you.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Group therapy online, Alcohol addiction, Drug addiction, Medical detox

---

### FILE 5: group_therapy.html
Template: mockup-inner.html
Breadcrumb: Home → Eating disorders → Group therapy online
Hero h1: Group therapy online
Hero image: (see image table)

```
LEAD PARAGRAPH:
We are confident our online Eating Disorders program is one-of-a-kind replacement for residential programs. It is not a once-time event or an online marathon but instead a systematic clinical activity.

P1: This type of treatment has its advantages and these can be very significant. In addition to the attractive price, which is more than 80% less than our residential program, this online program is inclusively integrated into your daily life which means when you finish, you will not have to integrate and socialize your new skills from scratch because the recovery process will already be organically developed.

P2: All you will need is the desire to do it along with some self-discipline, we will take care of the rest.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Residential treatment, Alcohol addiction, Drug addiction, Medical detox

---

### FILE 6: alcohol_addiction.html
Template: mockup-inner.html
Breadcrumb: Home → Addiction → Alcohol addiction
Hero h1: Alcohol addiction
Hero image: (see image table)

```
LEAD PARAGRAPH:
Any person with an alcohol addiction can be helped. Patients of varying degrees of motivation are accepted for the main program in our rehabilitation center.

P1: In addition to detox and psychotherapy, in our center you will receive all the necessary support in order to feel safe and go through difficult periods of emotional instability in the most comfortable and careful conditions.

P2: If you or your family member is experiencing doubt, uncertainty about the prospects for recovery, you can take a separate short express program with a motivational psychologist.

SUBHEADING: Alcohol addiction consultants, psychologists, psychotherapists, psychiatrists, narcologists, life coaches, as well as massage therapists, fitness trainers, as well as organizers of cultural events will be at your disposal 24/7

CALLOUT: Contact us to get an answer to the question you are interested in

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Drug addiction, Medical detox, Behavioural addiction treatment, Dual diagnosis

---

### FILE 7: drug_addiction.html
Template: mockup-inner.html
Breadcrumb: Home → Addiction → Drug addiction
Hero h1: Drug addiction
Hero image: (see image table)

```
LEAD PARAGRAPH:
There is nothing easier than to make a drug addict sober, even with the use of the most severe drugs on modern medical equipment, the state of physical sobriety is achieved within 48 hours.

P1: The main difficulty is that the absence of physical traces of drug use in the body does not cure a person, there is a huge gap between the state of physiological sobriety here and now and the skills to stay sober throughout the rest of life, and there is no such person on the planet who could overcome this gap by willpower.

SUBHEADING: Our team consists of experienced certified and licensed specialists who have been engaged in psychotherapy of dependent behavior for many years

P2: The problem of drug addiction remained unsolvable for many years, because the creation of recovery technology required huge progress in physiology, psychology, cognitive sciences and understanding of the subtle processes of the brain.

P3: And only in the last few decades, we can say with confidence that we understand about the problem of drug addiction, to be sure that with the assistance of patients we can guarantee the result.

P4: At least half of the team are people who know the problem from the inside, have personal experience of recovering from drug addiction and remain clean and happy for at least 6 years.

P5: You can be sure that by contacting us for help you will receive all the necessary support, and our team of professionals will do everything possible to take you step by step, comfortably and safely along an effective recovery route.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Alcohol addiction, Medical detox, Behavioural addiction treatment, Dual diagnosis

---

### FILE 8: medical_detox.html
Template: mockup-inner.html
Breadcrumb: Home → Addiction → Medical detox
Hero h1: Medical detox
Hero image: (see image table)

```
LEAD PARAGRAPH:
When people stop using alcohol or drugs, they usually describe their physical and emotional state as "unbearable". The withdrawal symptoms are the results of a lack of vitamins, minerals and nutrients caused by substance abuse. This leads to deficiency of amino acids which are used by our brain to build neurotransmitters.

P1: To illustrate what the deficit of neurotransmitters is like, just imagine driving a car with a manual transmission and you are only able to use first gear. It is technically possible to move but it's slow, uncomfortable, and increases fuel consumption.

P2: To get rid of abstinence, return the nervous system to the standard mode and begin the recovery process, it is necessary to go through medical detox procedures.

SUBHEADING: Residents of Monte Rehab are offered all the necessary qualified assistance to overcome the abstinence stage under the supervision of experienced narcologists and therapists.

SUBHEADING 2: Depending on the severity and duration of alcohol abuse, withdrawal may be more severe, causing symptoms such as:

SYMPTOM LIST (render as feature-list):
  • Hallucinations
  • Convulsions
  • High blood pressure
  • Quickening of the pulse
  • Heat
  • Profuse sweating
  • Delirium tremens (DC)

CLOSING: In our center, residents can receive all the necessary qualified assistance to complete the path of abstinence as safely, comfortably and carefully as possible.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Alcohol addiction, Drug addiction, Behavioural addiction treatment, Dual diagnosis

---

### FILE 9: behavioural_addiction_treatment.html
Template: mockup-inner.html
Breadcrumb: Home → Addiction → Behavioural addiction treatment
Hero h1: Treatment of food and behavioral addictions   ← EXACT title from site
Hero image: (see image table)

```
SUBHEADING: There are a huge number of behavioral addictions:

LIST:
  • Eating disorders
  • Gambling addiction / ludomania
  • Internet addiction
  • Sexual addiction

P1: Despite the fact that the object of addiction is different actions (food, sex, play), all behavioral addictions are based on a common phenomenology, scenario of development and existence.

SUBHEADING: Only after discovering and working out the original reason for launching a destructive scenario can you start controlling your own behavior again.

P2: If a person compulsively overeats, the intuitive solution will be to limit himself in food, if this does not help, then at least overeat with non-harmful products, if this does not help, try to switch entirely to a healthy diet, if difficulties arise here, then so be it - overeat, but not every day.

P3: In all the cases described, this is nothing more than an attempt to find a superficial compromise that will affect the effect, not the cause.

SUBHEADING: A similar scenario goes through the stage of a patient with gambling addiction.

LIST:
  • I will stop playing at all,
  • I will play within the allotted amount,
  • I will play for everything except money, which I desperately need,
  • to hell with it, I'll lose everything I have, and then I'll stop right away.

P4: In all cases, we will have to admit that in all cases intuitive solutions do not work and it is necessary to move to counter intuitive solutions.

P5: It is important to understand that the symptom is not identical to the disease. It is impossible to cure bronchitis by helping a patient to cough, it is impossible to cure skin itching by inventing original ways to scratch the sore spot. In the first case, you will have to take pills, in the second, smear with special ointments. And the main problem is that the effect will not be instantaneous and will be delayed in time.

SUBHEADING: The strategy of recovery from behavioral addictions includes 6 points:

LIST:
  • give up volitional efforts
  • accept that this is a consequence of the cause of tension
  • legalize the way of responding
  • detect and work through the original cause
  • accepting the fact that your command to you is beyond your control and the problem cannot be solved by volitional efforts and restrictions
  • accepting that compulsive behavior is the brain's response to serious internal tensions and problems that have not been solved for a long time

P6: If you forbid a person to react to this tension in this way, the consequences can be even more catastrophic. All attempts at a mechanical solution to the problem in 100% of cases lead to an aggravation of the situation.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Alcohol addiction, Drug addiction, Medical detox, Dual diagnosis

---

### FILE 10: dual_diagnosis.html
Template: mockup-inner.html
Breadcrumb: Home → Addiction → Dual diagnosis
Hero h1: Dual diagnosis
Hero image: (see image table)

```
LEAD PARAGRAPH:
The human brain is extremely complicated and over time it has gained many genetic mutations, some which affect metabolism. Even a small change in DNA can cause a defect in the production of proteins, neurotransmitters and neurohormones. These changes in brain chemistry affect the way people perceive reality.

P1: This can lead to people experiencing the surrounding world in a special way, they may feel derealization and depersonalization. These people doubt the world or even they themselves exist. Most of them find it unbearable to live in such a subjective reality which leads to constant uncertainty, anxiety, and fear.

P2: Many of those who were not diagnosed in time and did not receive help they need, find a solution in illegal psychotropic and psychoactive substances that help them to feel fine for a short period of time.

SUBHEADING: Nearly half of all alcohol and drug users have a dual diagnosis. These illegal substances help them to deal with stress and basically live their lives as normal human beings.

P3: The human brain is extremely complicated and over time it has gained many genetic mutations, some which affect metabolism. Even a small change in DNA can cause a defect in the production of proteins, neurotransmitters and neurohormones. These changes in brain chemistry affect the way people perceive reality.

P4: This can lead to people experiencing the surrounding world in a special way, they may feel derealization and depersonalization. These people doubt the world or even they themselves exist. Most of them find it unbearable to live in such a subjective reality which leads to constant uncertainty, anxiety, and fear.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Alcohol addiction, Drug addiction, Medical detox, Behavioural addiction treatment

---

### FILE 11: anxiety_treatment.html
Template: mockup-inner.html
Breadcrumb: Home → Mental Health → Anxiety treatment
Hero h1: Anxiety treatment
Hero image: (see image table)

```
LEAD PARAGRAPH:
Anxiety is a normal secondary response to stress. The problem is not anxiety itself, but attempts to ignore it, because in this case the brain fails to form effective coping strategies.

P1: The source of the problem is a state of uncontrollable stress, when a person feels his own helplessness over and over again, because all attempts to adapt to the surrounding reality fail.

P2: The state of uncontrolled stress forms a background feeling of anxiety in a person, then the entire body and nervous system begins to rebuild its functioning under an extreme regime.

SUBHEADING: Psychotherapy helps to eliminate the internal source of stress, develop an effective way to adapt to changes, harmonize internal neurophysiological processes and help the body switch from extreme to normal operations.

P3: As soon as people find themselves in stressful situations for themselves, the first action they take is to try to suppress this condition, which later causes more serious consequences. Apathy, panic attacks, nervousness and tension, insomnia and much more are signs of anxiety.

P4: If you do not eliminate this problem in time, then with each subsequent day you will only feel worse and this can affect not only your career, personal relationships, and your children, but can also lead to serious health problems, such as stomach ulcers, cardiovascular problems, diabetes mellitus, concomitant addiction.

P5: People who want to lose weight, first of all, try to replace harmful products with less harmful ones, increase the amount of physical activity, stop eating altogether, but all this does not contribute to weight loss or a person gets a short-term result that will soon make him break down again, while experiencing a feeling of anger towards himself, dissatisfaction with his own result, to annoyance.

P6: Sooner or later you will have to realize that the problem concerns not only food consumption, but also internal conflicts that have not been worked out.

P7: The complex work of our specialists contributes to a speedy recovery under the constant supervision of professionals.

P8: In our center you will be able not only to undergo full-fledged therapy, but also to relax from stress, relax, restore your resource and acquire harmony and balance.

P9: Contact our center if you want to get professional, qualified and careful help, and learn how to cope with life situations on your own.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Depression treatment, Executive burnout, Insomnia treatment, PTSD and trauma treatment

---

### FILE 12: depression_treatment.html
Template: mockup-inner.html
Breadcrumb: Home → Mental Health → Depression treatment
Hero h1: Depression treatment
Hero image: (see image table)

```
LEAD PARAGRAPH:
It is normal to feel a bad mood or be upset by something, it is also quite normal to have a desire to be alone or spend the evening with your personal experiences. But this is normal, provided that you do not experience a feeling of complete despair, hopelessness and can not satisfy your needs with the help of the usual things for you.

CALLOUT: Most likely, these may be symptoms of depression.

P1: If the question "Tell us about any pleasant memory?", You dig into your head for a long time to find positive moments, this is an occasion to seriously think about your mental health.

SUBHEADING: Depression is a disorder that negatively affects not only your inner state and attitude, but also your personal and sexual relationships, your work and relationships with colleagues and friends, and has a bad effect on your daily life and the performance of everyday activities.

P2: If a person is sick with gastritis, he feels discomfort in the abdomen, pain and other symptoms and it is impossible to help him simply by stroking his stomach. Similarly, depression can be cured only if you provide a person with specialized care, and not indulge his complaints and suffering.

P3: We conduct a personal assessment of the mental state with our specialists, which helps to choose the methods of treatment and careful restoration of your condition, until complete recovery and finding harmony with yourself.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Anxiety treatment, Executive burnout, Insomnia treatment, Mood disorder treatment

---

### FILE 13: executive_burnout.html
Template: mockup-inner.html
Breadcrumb: Home → Mental Health → Executive burnout
Hero h1: Executive burnout
Hero image: (see image table)

```
LEAD PARAGRAPH:
It can be difficult to track the first signs of burnout, because a person enters this state gradually.

SUBHEADING: Symptoms of burnout include:

LIST:
  • Tension
  • No pleasure from business
  • Touchiness, toxicity
  • and so on...

P1: Burnout is accompanied by an unwillingness to get up in the morning to work, to perform their usual affairs, there is not enough desire and energy to move on.

SUBHEADING: Loss of interest in work, constant fatigue and insomnia, conflicts with colleagues, friends and relatives, irritability to environmental factors, emotional exhaustion, etc. - these are exactly the consequences that can arise as a result of ignoring the treatment of burnout.

P2: If you scoop soup from a pot, it will run out sooner or later, but just banging on an empty pot won't solve the problem of resuming the amount of food in the dishes. Or if you squeeze the juice out of an orange, sooner or later there will be one peel that will not be able to fill the glass with freshly squeezed fresh juice, no matter how much you press on it. It's the same situation with burnout. If your emotional resource is depleted, then even greater oppression of it will not help to achieve harmony and balance with yourself and your emotional state.

P3: Only a special atmosphere, proper rest, work with professionals and an individual approach to each client contribute to the careful restoration of emotional burnout. In the recovery program, each day is fully scheduled with activities specifically designed to restore the state of your balance.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Anxiety treatment, Depression treatment, Insomnia treatment, Mood disorder treatment

---

### FILE 14: insomnia_treatment.html
Template: mockup-inner.html
Breadcrumb: Home → Mental Health → Insomnia treatment
Hero h1: Insomnia treatment
Hero image: (see image table)

```
LEAD PARAGRAPH:
Imagine that morning has come, you have counted all the sheep of this universe, but you have not been able to sleep. This insomnia is a neurological disorder that requires professional intervention.

P1: It would seem that this is a problem that has a simple solution and is temporary, so you do not need to undergo examinations and dive into a comprehensive solution to this issue. But this is not the case.

P2: Insomnia is a disease that requires attention as well as diabetes mellitus, stomach ulcer, impotence, etc. The cause of insomnia is depression, stress, drug use, etc.

SUBHEADING: Only a comprehensive examination and individual work with specialists contributes to a rapid recovery and finding peace of mind.

P3: We provide an opportunity not only to say goodbye to your anxiety, tension, torment, but also to get rest, relaxation and recovery, to restore balance and harmony.

P4: We take care of our clients, so we develop individual treatment methods that help improve lifestyle, renew energy and instill healthy habits.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Anxiety treatment, Depression treatment, Executive burnout, Mood disorder treatment

---

### FILE 15: mood_disorder_treatment.html
Template: mockup-inner.html
Breadcrumb: Home → Mental Health → Mood disorder treatment
Hero h1: Mood disorder treatment
Hero image: (see image table)

```
LEAD PARAGRAPH:
From time to time everyone will experience a feeling of sadness, sorrow, and melancholy. For example, you may have recently broke up with your partner, had a family conflict, or missed a project deadline. All these negative emotions are temporary and will soon be replaced by positive life situations.

P1: But if negative emotions prevail, nothing pleases you for months and you will not find harmony with the world around you. These are symptoms of a mood disorder.

P2: Depressive disorder, seasonal affective disorder, bipolar disorder, adjustment disorder, and anxiety, etc, are all varieties of mood disorder to which there was no timely response.

SUBHEADING: Mood disorder is not just a time in your life when negative emotions dominate, it is a disease that affects your condition and your health in different ways and has its varieties.

P3: Over time, mood disorders can lead to disadaptation, or to the loss of the ability to adapt to the surrounding reality. Inadequate emotional reactions destroy personal relationships and make it impossible to work productively.

P4: In addition, a mood disorder leads to health deterioration, irritation, apathy, lethargy, loss of appetite, lack of motivation, feeling of hopelessness, etc.

P5: We provide a special environment that will give you an opportunity to work out your personal experiences, take a break from your everyday routine, replenish your live energy and teach you how to deal with challenges, develop healthy habits, and control your emotions.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Anxiety treatment, Depression treatment, Executive burnout, PTSD and trauma treatment

---

### FILE 16: ptsd_and_trauma_treatment.html
Template: mockup-inner.html
Breadcrumb: Home → Mental Health → PTSD and trauma treatment
Hero h1: PTSD and Trauma treatment
Hero image: (see image table)
NOTE: The original site has a breadcrumb error (says "Anxiety treatment") — correct it to "PTSD and trauma treatment"

```
LEAD PARAGRAPH:
Domestic violence, verbal violence by parents, divorce, severe punishment, parents' use of alcohol or drugs, experience of depression by one of the parents, experience of suicide in parents, imprisonment of close relatives, sexual and physical violence.

P1: This and similar adverse experiences lead to the formation of emotional disturbances and often force people even in adulthood to protect themselves from the possible repetition of unpleasant episodes.

P2: For obvious reasons, PTSD can form at a later age, if a person has been abused, had an accident, became a participant in hostilities.

SUBHEADING: In most cases, all traumatic events about the present are linked by our brains to traumatic experiences from the past.

P3: All of the above affects your world perception, makes you feel shame and guilt, apathy, and exhaustion.

P4: Working with qualified psychotherapists and a team of certified specialists will help not only get rid of disturbing thoughts, fear, depression and other symptoms, but will also give you the opportunity to return to a healthy harmonious state of mind, feel the desired relief and learn to experience positive emotions again without plunging into the negative past.

CTA button: Sign Up now → #enquiry
```

SIDEBAR related links: Anxiety treatment, Depression treatment, Mood disorder treatment, Executive burnout

---

## TECHNICAL RULES

### Every file must:
- Be fully self-contained (CSS in `<style>`, JS in `<script>`)
- Include Google Fonts CDN link
- Use NO external frameworks (no Bootstrap, Tailwind, jQuery)
- All `<img>` must have `loading="lazy"`
- All internal links use relative paths (e.g. `href="pricing.html"`)
- Have a correct `<title>` tag (use the page's H1 + " — Monte Rehab")

### JS required in every file:
- IntersectionObserver scroll-reveal (class `.reveal` → `.visible`)
- Nav dropdown: hover on desktop, click on mobile
- Mobile hamburger toggles nav drawer
- Nav background appears on scroll > 60px

### Responsive breakpoints:
- ≥1100px: full desktop layout
- 769–1099px: tablet (2-col grids)
- ≤768px: mobile (1 col) + sticky bottom CTA bar showing at all times
  - Left button: "📞 Call now" → tel:+38269621111
  - Right button: "Write to us" → #enquiry

### Sidebar on inner pages (mockup-inner.html pattern):
- Contact card (phone, email, messengers)
- Related services (4 links, per-page list above)
- Pricing teaser (3 tiers + "View all pricing" → pricing.html)

---

## FILE CHECKLIST

| # | File | Template | Status |
|---|------|----------|--------|
| 1 | index.html | mockup-home.html | ✓ content ready |
| 2 | pricing.html | mockup-inner.html (no sidebar) | ✓ content ready |
| 3 | contacts.html | mockup-inner.html (no sidebar) | ✓ content ready |
| 4 | residential_treatment.html | mockup-inner.html | ✓ content ready |
| 5 | group_therapy.html | mockup-inner.html | ✓ content ready |
| 6 | alcohol_addiction.html | mockup-inner.html | ✓ content ready |
| 7 | drug_addiction.html | mockup-inner.html | ✓ content ready |
| 8 | medical_detox.html | mockup-inner.html | ✓ content ready |
| 9 | behavioural_addiction_treatment.html | mockup-inner.html | ✓ content ready |
| 10 | dual_diagnosis.html | mockup-inner.html | ✓ content ready |
| 11 | anxiety_treatment.html | mockup-inner.html | ✓ content ready |
| 12 | depression_treatment.html | mockup-inner.html | ✓ content ready |
| 13 | executive_burnout.html | mockup-inner.html | ✓ content ready |
| 14 | insomnia_treatment.html | mockup-inner.html | ✓ content ready |
| 15 | mood_disorder_treatment.html | mockup-inner.html | ✓ content ready |
| 16 | ptsd_and_trauma_treatment.html | mockup-inner.html | ✓ content ready |

---
---
---

# ═══════════════════════════════════════
# LANGUAGE ARCHITECTURE
# ═══════════════════════════════════════

The site has three full language versions. Each is a complete independent set of 16 HTML files.

```
📁 project root/
   ├── index.html                        ← EN home
   ├── pricing.html
   ├── contacts.html
   ├── residential_treatment.html
   ├── group_therapy.html
   ├── alcohol_addiction.html
   ├── drug_addiction.html
   ├── medical_detox.html
   ├── behavioural_addiction_treatment.html
   ├── dual_diagnosis.html
   ├── anxiety_treatment.html
   ├── depression_treatment.html
   ├── executive_burnout.html
   ├── insomnia_treatment.html
   ├── mood_disorder_treatment.html
   ├── ptsd_and_trauma_treatment.html
   │
   ├── ru/
   │   ├── index.html                    ← RU home (URL: home_ru on original)
   │   ├── pricing.html
   │   ├── contacts.html
   │   ├── residential_treatment.html
   │   ├── group_therapy.html
   │   ├── alcohol_addiction.html
   │   ├── drug_addiction.html
   │   ├── medical_detox.html
   │   ├── behavioural_addiction_treatment.html
   │   ├── dual_diagnosis.html
   │   ├── anxiety_treatment.html
   │   ├── depression_treatment.html
   │   ├── executive_burnout.html
   │   ├── insomnia_treatment.html
   │   ├── mood_disorder_treatment.html
   │   └── ptsd_and_trauma_treatment.html
   │
   └── me/
       ├── index.html                    ← ME home (URL: home_me on original)
       ├── pricing.html                  ← ME: cijene_me on original
       ├── contacts.html                 ← ME: kontakti_me on original
       ├── stacionarno_leenje.html
       ├── grupna_terapija_online.html
       ├── zavisnost_od_alkohola.html
       ├── zavisnost_od_droga.html
       ├── medicinska_detoksikacija.html
       ├── leenje_ponaajnih.html
       ├── dvojna_dijagnoza.html
       ├── leenje_anksioznosti.html
       ├── leenje_depresije.html
       ├── izgaranje_na_poslu_kod_rukovodilaca.html
       ├── leenje_nesanice.html
       ├── leenje_poremeaja_raspoloenja.html
       └── leenje_ptsp.html
```

## Language switcher links (in nav on all pages)

Every page has EN | RU | ME switcher. Rules:
- EN pages link to: `../index.html`, `../ru/index.html`, `../me/index.html` (adjust relative paths per depth)
- RU pages link to equivalent EN and ME page
- ME pages link to equivalent EN and RU page
- The current language is shown as active/bold

---

## RU SHARED NAV

```
Logo: MonteRehab

Nav links:
- О клинике → ru/index.html
- Пищевое поведение ▾
    Реабилитационная программа → ru/residential_treatment.html
    Групповая онлайн-терапия   → ru/group_therapy.html
- Зависимости ▾
    Алкоголизм                          → ru/alcohol_addiction.html
    Наркомания                          → ru/drug_addiction.html
    Детоксикация                        → ru/medical_detox.html
    Лечение поведенческой зависимости   → ru/behavioural_addiction_treatment.html
    Двойной диагноз                     → ru/dual_diagnosis.html
- Душевное здоровье ▾
    Лечение тревоги                     → ru/anxiety_treatment.html
    Лечение депрессии                   → ru/depression_treatment.html
    Выгорание на работе                 → ru/executive_burnout.html
    Лечение бессонницы                  → ru/insomnia_treatment.html
    Лечение расстройства настроения     → ru/mood_disorder_treatment.html
    Лечение ПТСР и травм                → ru/ptsd_and_trauma_treatment.html
- Стоимость  → ru/pricing.html
- Контакты   → ru/contacts.html

Right side:
  EN | RU | ME
  +382 69 621 111
  [Связаться] → ru/contacts.html
```

## RU SHARED FORM

```
Heading:    Свяжитесь с нами и начните путь к выздоровлению сегодня
Subheading: Введите ваше имя и e-mail, и мы свяжемся с вами
Fields:     Имя (text), E-mail (email)
Checkbox:   Я согласен предоставить свои данные сайту monterehab.com
Button:     Отправить
```

## RU SHARED FOOTER SEO

```
Кол 1 — РЕАБИЛИТАЦИОННАЯ ПРОГРАММА ДЛЯ АЛКОГОЛИКОВ
  Лечение зависимостей → /ru/addiction_treatment
  Лечение хронического алкоголизма → /ru/chronic_alcoholism
  Лечение запойного алкоголизма → /ru/conclusion_from_drinking
  Лечение тайного алкоголизма → /ru/secret_alcoholism
  Лечение пивного алкоголизма → /ru/beer_alcoholism
  Лечение женского алкоголизма → /ru/female_alcoholism
  Лечение бытового алкоголизма → /ru/household_alcoholism
  Перманентный алкоголизм → /ru/permanent_alcoholism

Кол 2 — РЕАБИЛИТАЦИОННАЯ ПРОГРАММА НЕХИМИЧЕСКИХ ЗАВИСИМОСТЕЙ
  Лечение интернет-зависимости → /ru/internet_addiction
  Лечение игромании: игровой зависимости → /ru/gaming_addiction
  Лечение зависимости от азартных игр → /ru/gambling_addiction
  Лечение сексуальной, любовной зависимости - сексоголизма → /ru/sexual_obsession
  Лечение шопоголизма → /ru/shopaholism

Кол 3 — РЕАБИЛИТАЦИЯ ПРИ РАССТРОЙСТВАХ ПИЩЕВОГО ПОВЕДЕНИЯ
  Лечение анорексии → /ru/anorexia
  Лечение булимии → /ru/bulimia
  Лечение зависимости от сладкого → /ru/sugar_addiction
  Лечение зависимости от стимулирующих и энергетических напитков → /ru/energy_drink_addiction

Кол 4 — РЕАБИЛИТАЦИОННАЯ ПРОГРАММА ДЛЯ НАРКОЗАВИСИМЫХ
  Лечение героиновой зависимости → /ru/heroin_addiction
  Лечение кодеиновой зависимости → /ru/codeine_addiction
  Лечение метадоновой зависимости → /ru/methadone_addiction
  Лечение кокаиновой зависимости → /ru/cocaine_addiction
  Лечение токсикомании → /ru/substance_abuse
  Лечение зависимости от марихуаны → /ru/marijuana_addiction
  Лечение зависимости от СПАЙСов → /ru/spice_addiction
  Лечение лекарственной зависимости → /ru/drugs_addiction
  Лечение солевой зависимости → /ru/salt_addiction
  Лечение амфетаминовой зависимости → /ru/amphetamine_addiction
  Наркотическая зависимость → /ru/narco_addiction
  Клиника лечения наркомании и алкоголизма → /ru/clinic_drug_alcoholism
  Реабилитационный центр для наркоманов → /ru/drug_rehabilitation_center
  Центр помощи наркозависимым → /ru/addiction_treatment_center
  Клиника лечения наркомании → /ru/addiction_treatment_clinic
  Лечение от экстази → /ru/ecstasy_addiction
  Лечение от трамадола → /ru/tramadol_addiction
  Лечение гашишной зависимости → /ru/hashish_addiction
  Лечение зависимости от LSD → /ru/lsd_addiction
  Лечение от опиатов → /ru/opiate_addiction

Footer bottom: © Все права защищены | Политика конфиденциальности
```

---

# ═══════════════════════════════════════
# RU PAGE CONTENT
# ═══════════════════════════════════════

## RU IMAGE TABLE (same Tilda CDN images, same 800px resolution)

| File | Hero image URL |
|------|----------------|
| ru/index.html | https://images.unsplash.com/photo-1504701954957-2010ec3bcec1?w=1600&q=85 |
| ru/residential_treatment.html | https://thb.tildacdn.com/tild3330-6137-4638-a433-653235393033/-/resize/800x/-.jpg |
| ru/group_therapy.html | https://thb.tildacdn.com/tild3464-6264-4634-b965-306436663131/-/resize/800x/-.jpg |
| ru/alcohol_addiction.html | https://thb.tildacdn.com/tild6430-3136-4639-b366-353964303731/-/resize/800x/3.jpg |
| ru/drug_addiction.html | https://thb.tildacdn.com/tild3337-3431-4138-b966-653535663364/-/resize/800x/-.jpg |
| ru/medical_detox.html | https://thb.tildacdn.com/tild3833-3562-4137-a535-313334396661/-/resize/800x/2.jpg |
| ru/behavioural_addiction_treatment.html | https://thb.tildacdn.com/tild6430-3237-4562-b664-343736333762/-/resize/800x/photo.jpg |
| ru/dual_diagnosis.html | https://thb.tildacdn.com/tild6232-6266-4631-b230-393533386533/-/resize/800x/DeWatermark-min.png |
| ru/anxiety_treatment.html | https://thb.tildacdn.com/tild3939-3731-4233-a461-376464363361/-/resize/800x/anxiety.jpeg |
| ru/depression_treatment.html | https://thb.tildacdn.com/tild6334-6363-4932-b039-303062313130/-/resize/800x/deepr.jpeg |
| ru/executive_burnout.html | https://thb.tildacdn.com/tild3437-3831-4635-a136-376162353131/-/resize/800x/burnout.jpeg |
| ru/insomnia_treatment.html | https://thb.tildacdn.com/tild6630-3766-4266-b365-636533646334/-/resize/800x/insomnia.jpeg |
| ru/mood_disorder_treatment.html | https://thb.tildacdn.com/tild3932-3364-4139-a162-353233626565/-/resize/800x/mood.jpeg |
| ru/ptsd_and_trauma_treatment.html | https://thb.tildacdn.com/tild3837-6430-4666-b235-353432663466/-/resize/800x/ptsd.jpeg |
| ru/pricing.html | https://images.unsplash.com/photo-1566073771259-6a8506099945?w=1600&q=85 |
| ru/contacts.html | https://images.unsplash.com/photo-1506905925346-21bda4d32df4?w=1600&q=85 |

---

### RU FILE 1: ru/index.html
Template: mockup-home.html
Page title: Клиника лечения зависимостей в Черногории — MonteRehab

#### HERO
```
Headline:   Свобода от зависимостей
Subline:    Просто доверьтесь, и мы вам поможем
Button 1:   Созвониться → #enquiry
Button 2:   Как и почему это работает → #rec836031031
```

#### SECTION: About (id="rec836031031")
```
H1: Реабилитационный центр для лечения зависимостей в Черногории
H2: Мы знаем, что ваша проблема - это не ваша вина

P1: Если вы боретесь с зависимостью, может показаться, что выхода нет. Но это неправда! Многие люди успешно преодолели свои пагубные привычки, и вы тоже можете. Самое главное - никогда не терять надежду и доверять специалистам реабилитационного центра.

P2: Профессионалы в центре понимают сложности зависимости и могут предоставить вам навыки и поддержку, необходимые для выздоровления. С их помощью вы можете освободиться от цепей зависимости и вернуться к здоровой, продуктивной жизни.

P3: Так что не теряйте надежды; протяните руку и получите необходимую вам помощь, чтобы вернуться на путь выздоровления. Дорога может быть трудной, и на пути могут быть ухабы, но при поддержке и руководстве специалистов реабилитационного центра вы сможете перебраться на другую сторону.
```

#### SECTION: Как мы можем помочь?
```
Section heading: Как мы можем помочь?

CARD 1 — Стационарное лечение:
  Наша команда поможет вам определить ваши личные цели, прежде чем вы начнете.
  Ежедневные сеансы терапии 1 к 1 закладывают основы для постоянных позитивных изменений и помогают развить навыки саморегуляции.
  Мы проводим полное медицинское обследование при поступлении и оказываем индивидуальную поддержку при сопутствующих заболеваниях.
  Мы предлагаем безопасные и интимные групповые занятия онлайн и оффлайн для поддержки восстановления после реабилитации и предотвращения рецидива.
  CTA: Узнать больше → ru/residential_treatment.html

CARD 2 — Онлайн-терапия:
  Основываясь на лучших мировых практиках, основанных на фактических данных, и 10-летнем нашем собственном опыте в лечении ЭД, мы представляем уникальную онлайн-программу.
  Всего за 3 года курс прошли 1500 человек, и 83% из них решили свою проблему и в результате значительно улучшили качество своей жизни.
  Мы разработали первое решение для лечения ЭД, которое способно заменить традиционные реабилитационные центры и жилые центры.
  Все, что вам нужно сделать, это следовать нашим экспертным рекомендациям и делиться своими отзывами с командой, мы позаботимся обо всем остальном.
  CTA: Узнать больше → ru/group_therapy.html
```

#### SECTION: Зависимости
```
Tag:  Зависимости
H2:   Мы знаем, через что вы прошли, и мы здесь, чтобы помочь

P1: Наш девиз — изменения через принятие, поддержку и профессионализм.

P2: Каждый член нашей команды имеет многолетний стаж и колоссальный профессиональный опыт. У нас работают люди, знакомые с зависимостью изнутри. Мы не рассуждаем как нужно жить, мы даем пошаговую инструкцию и способны настоять на её внедрении. Мы протягиваем руку помощи и помогаем выбраться из лабиринта заблуждений.

P3: Наши специалисты знают все, что необходимо, чтобы вы избавились от зависимости, от вас требуется только желание и присутствие, остальное — наша забота.

P4: Montenegro Rehab — это безопасное пространство, где вы будете в бережной атмосфере комфорта и принятия.

Links:
  Алкоголизм → ru/alcohol_addiction.html
  Наркомания → ru/drug_addiction.html
  Детоксикация → ru/medical_detox.html
  Пищевые и поведенческие зависимости → ru/behavioural_addiction_treatment.html
```

#### SECTION: Душевное здоровье
```
H2: Душевное здоровье
H3: Найдите путь к настоящему себе и научитесь любить себя снова

P1: Наш мозг никогда не подвергался такому эмоциональному напряжению в истории человечества. В то время как человеческий мозг, вероятно, является единственным устройством в мире прямо сейчас, которое не поставляется с инструкцией по эксплуатации.

P2: Тревога, депрессии и другие проблемы с психическим здоровьем являются сигналами, которые наше тело посылает нам, говоря, что мы заставляем наше сознание работать в экстремальных режимах. Мы все должны разработать уникальные наборы правил, чтобы тщательно взаимодействовать с нашим сознанием.

P3: Наши эксперты по психическому здоровью помогут вам получить ваши эмоции, мысли и желания, чтобы встретиться с социальными установками, которые контролируют ваше поведение. Ключ к счастью и радости заключается в том, чтобы заставить свое сознание и подсознание двигаться в одном направлении.

Links:
  Лечение тревоги → ru/anxiety_treatment.html
  Лечение депрессии → ru/depression_treatment.html
  Выгорание на работе → ru/executive_burnout.html
  Лечение бессонницы → ru/insomnia_treatment.html
  Лечение расстройства настроения → ru/mood_disorder_treatment.html
  Лечение ПТСР и травм → ru/ptsd_and_trauma_treatment.html
```

#### SECTION: Стоимость
```
H2: Стоимость

CARD 1:
  Title: Евростандарт (двухместное размещение)
  Price: от €6,000 / месяц
  • Первый месяц — €6,000, второй и последующие — €5,000
  • При оплате пакетом 3 месяца — стоимость пакета €15,000
  • Еженедельные морские прогулки, горные туры и экскурсии
  CTA: Узнать больше → #enquiry

CARD 2:
  Title: Евростандарт (одноместное размещение)
  Price: от €9,000 / месяц
  • При оплате за 3 месяца — стоимость пакета €24,000
  • Более 8 часов психотерапии ежедневно
  • 4 часа семейной психотерапии в подарок
  CTA: Узнать больше → #enquiry

CARD 3:
  Title: Индивидуальная программа "Интенсив"
  Price: от €12,000 / месяц
  • Размещение в одноместных апартаментах
  • Ежедневная личная психотерапия с руководителем программы
  • Проживание на территории центра или самостоятельно в ближайшем городе
  • Ежедневное посещение обязательных мероприятий и встреча с куратором
  CTA: Узнать больше → #enquiry

CARD 4:
  Title: Ресоциализация и образование
  Price: от €3,500 / месяц
  • Сопровождение в процессе получения образования и трудоустройства
  • Возможность совмещать выздоровление с удалённой работой
  CTA: Узнать больше → #enquiry
```

---

### RU FILE 2: ru/pricing.html
Template: mockup-inner.html (no sidebar, full-width cards)
Breadcrumb: О клинике → Стоимость
Hero h1: Стоимость
```
[4 ценовые карточки — идентично разделу Стоимость выше]
```

---

### RU FILE 3: ru/contacts.html
Template: mockup-inner.html (no sidebar)
Breadcrumb: О клинике → Контакты
Hero h1: Контакты
```
Свяжитесь с нами:
Телефон: +382 69 621 111
Email: montenegrorehab@gmail.com

Из Европы: трансфер за 1000€ + дорожные расходы.
Из Черногории: Бесплатный трансфер.

WhatsApp → https://wa.me/38269621111
Telegram → https://t.me/RehabMontenegro
Viber    → viber://chat?number=+38269621111
Построить маршрут → https://www.google.com/maps/dir//MonteRehab...

Юридическая информация:
D.o.o "ProfReab"
Roman Konevichev
UL. SVETOSAVSKA BB, BLIZIKUĆE BUDVA
Registarski broj 50945727
PIB 03332381

Адрес: Sveti Stefan, Blizikuće 85315, Montenegro
```

---

### RU FILE 4: ru/residential_treatment.html
Breadcrumb: О клинике → Пищевое поведение → Стационарное лечение
Hero h1: Стационарное лечение
Hero image: (см. таблицу)
```
LEAD:
В рамках этой программы полного цикла вы будете находиться под наблюдением нашей команды профессиональных и заботливых терапевтов.

P1: Мы предлагаем чрезвычайно насыщенную программу психотерапии, сравнимую с 3 годами обычной поддерживающей психотерапии. Целью лечения любого поведенческого расстройства является изменение моделей поведения.

P2: Принципы работы мозга предполагают, что новые паттерны наиболее эффективно вырабатываются, когда мы оказываемся в радикально новой среде, поэтому наша программа обучения специально разработана таким образом, чтобы вам было удобно усваивать все, чему мы вас будем учить.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 5: ru/group_therapy.html
Breadcrumb: О клинике → Пищевое поведение → Групповая психотерапия
Hero h1: Групповая психотерапия
Hero image: (см. таблицу)
```
LEAD:
Уникальность этой программы в том, что она является полноценной заменой нахождению в реабилитационном центре и это не разовое мероприятие, это системная клиническая работа.

P1: По сравнению с реабилитационным центром у групповой онлайн терапии есть свои достоинства. Помимо привлекательной цены, более чем на 80% ниже у реабилитационной программы, эта программа инклюзивно встраивается в вашу повседневную жизнь и это значит, что, когда она закончится вам не придется с нуля социализировать новые навыки, потому что процесс выздоровления будет органично развиваться.

P2: Для того чтобы все описанное стало возможным вам понадобится желание и небольшой объем самодисциплины, дальше мы сделаем все за вас.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 6: ru/alcohol_addiction.html
Breadcrumb: О клинике → Зависимости → Лечение алкоголизма
Hero h1: Лечение алкоголизма
Hero image: (см. таблицу)
```
LEAD:
Любому человеку с алкогольной зависимостью можно помочь. На основную программу в наш реабилитационный центр принимаются пациенты разной степени мотивированности.

P1: Помимо детокса и психотерапии в нашем центре вы получите всю необходимую поддержку для того, чтобы почувствовать себя в безопасности и пройти тяжелые периоды эмоциональной нестабильности в максимально комфортных и бережных условиях.

P2: Если вы или ваш родственник испытываете сомнение, неуверенность по поводу перспектив выздоровления, вы можете пройти отдельную короткую экспресс-программу с мотивационным психологом.

SUBHEADING: В вашем распоряжении 24/7 будут консультанты по алкогольной зависимости, психологи, психотерапевты, психиатры-наркологи, лайф коучи, а также массажисты, фитнес-тренеры, а также организаторы культурных мероприятий.

CALLOUT: Свяжитесь с нами, чтобы получить ответ на вопрос, который вас интересует.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 7: ru/drug_addiction.html
Breadcrumb: О клинике → Зависимости → Лечение наркомании
Hero h1: Ты можешь победить зависимость – и мы тебе в этом поможем
Hero image: (см. таблицу)
```
LEAD:
Скажи честно: как часто ты думал, что выхода нет? Как часто ты говорил себе: «Все кончено, я не справлюсь»? А теперь посмотри вокруг. Ты здесь. Ты ищешь решение. Это значит, что внутри тебя живет сила. И эта сила приведет тебя к победе над зависимостью.

P1: В Монте Рехаб мы точно знаем: нет ничего невозможного. Каждый человек, обратившийся к нам за помощью, однажды думал, что его жизнь закончена. Но они победили! Они вернулись к нормальной жизни, и ты сможешь тоже. Да, будет трудно. Но результат того стоит. И мы будем рядом с тобой на каждом шаге.

H2: Лечение наркомании в Монте Рехаб

P2: Ты заслуживаешь лучшего. Ты заслуживаешь жизни без зависимости, жизни, где ты — главный герой, а не жертва обстоятельств. В реабилитационном центре Монте Рехаб мы предлагаем не просто лечение — мы даем надежду, знания и инструменты, которые помогают вернуть контроль над своей жизнью.

P3: Наш подход уникален, потому что мы работаем на всех уровнях:

LIST:
  • Физическом. Полное очищение организма (детоксикация) — первый шаг, чтобы ты снова почувствовал себя живым.
  • Психологическом. Психотерапия помогает разобраться в корнях проблемы и заложить фундамент новой, счастливой жизни.
  • Социальном. Мы учим жить заново, жить в мире, полном соблазнов, но без зависимости.

P4: Каждую программу мы подбираем индивидуально, потому что ты — уникален. Здесь нет шаблонов, есть только твоя история и твой путь к свободе.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 8: ru/medical_detox.html
Breadcrumb: О клинике → Зависимости → Детоксикация наркозависимых
Hero h1: Детоксикация наркозависимых
Hero image: (см. таблицу)
```
LEAD:
Когда люди перестают употреблять алкоголь или наркотики, они обычно описывают свое физическое и эмоциональное состояние как "невыносимое".

P1: Чтобы проиллюстрировать, на что похож дефицит нейротрансмиттеров, просто представьте, что вы ведете автомобиль с механической коробкой передач, и вы можете использовать только первую передачу.

P2: Чтобы избавиться от абстиненции, вернуть нервную систему в стандартный режим и начать процесс восстановления, необходимо пройти медицинские процедуры детоксикации.

SUBHEADING: Для того, чтобы избавить себя от абстиненции, позволить нервной системе функционировать стандартно и начать путь выздоровления, необходимо пройти медицинские процедуры детокса под наблюдением опытных врачей-наркологов.

SUBHEADING 2: В зависимости от тяжести и продолжительности злоупотребления алкоголем абстиненция может быть более тяжелой, вызывая такие симптомы, как:

LIST:
  • Галлюцинации
  • Судороги
  • Высокое кровяное давление
  • Учащение пульса
  • Жар
  • Обильное потоотделение
  • Белая горячка (ДЦ)

CLOSING: В нашем центре резиденты могут получить всю необходимую квалифицированную помощь, чтобы пройти путь абстиненции максимально безопасно, комфортно и бережно.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 9: ru/behavioural_addiction_treatment.html
Breadcrumb: О клинике → Зависимости → Лечение расстройств поведения
Hero h1: Лечение расстройств поведения
Hero image: (см. таблицу)
```
SUBHEADING: Существует огромное количество поведенческих зависимостей:

LIST:
  • Расстройства пищевого поведения
  • Игромания / лудомания
  • Интернет-зависимость
  • Сексуальная зависимость

P1: Несмотря на то что объектом зависимости выступают разные действия (еда, секс, игра), все поведенческие зависимости имеют в своей основе общую феноменологию, сценарий развития и существования.

SUBHEADING: Только обнаружив и проработав первоначальную причину запуска разрушительного сценария можно опять начать управлять собственным поведением.

P2: Если человек компульсивно переедает интуитивным решением будет ограничить себя в еде, если это не поможет, тогда хотя бы переедать не вредными продуктами, если и это не поможет, постараться целиком перейти на здоровое питание, если и тут возникнут сложности, то так и быть - объедаться, но не каждый день.

P3: Во всех описанных случаях — это не что иное, как попытка найти поверхностный компромисс, который будет затрагивать следствие, а не причину.

SUBHEADING: Аналогичный сценарий проходит этап больной игроманией.

LIST:
  • Я перестану играть вообще,
  • Я буду играть в рамках отведенной суммы,
  • Я буду играть на всё кроме денег, которые мне остро необходимы,
  • черт с ним, проиграю всё что есть, а потом сразу перестану.

P4: Во всех случаях придется признать, что во всех случаях интуитивные решения не работают и необходимо перейти к контр интуитивным решениям.

P5: Важно понять, что симптом не тождественен заболеванию. Нельзя вылечить бронхит помогая больному кашлять, нельзя вылечить кожный зуд, придумывая оригинальные способы чесать больное место.

SUBHEADING: Стратегия выздоровления от поведенческих зависимостей включает в себя 6 пунктов:

LIST:
  • отказаться от волевых усилий
  • принять что это следствие причины напряжения
  • легализовать способ реагирования
  • обнаружить и проработать первоначальную причину
  • принять что команда самому себе неподвластна и проблема не решается волевыми усилиями и ограничениями
  • принять что компульсивное поведение — это реакция мозга на серьезные внутренние напряжения и нерешенные проблемы

P6: Если запретить человеку реагировать на это напряжение таким способом, последствия могут быть еще более катастрофическими. Все попытки механического решения проблемы в 100% случаев приводят к обострению ситуации.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 10: ru/dual_diagnosis.html
Breadcrumb: О клинике → Зависимости → Двойной диагноз
Hero h1: Двойной диагноз
Hero image: (см. таблицу)
```
LEAD:
Человеческий мозг чрезвычайно сложен, и со временем он приобрел множество генетических мутаций, некоторые из которых влияют на обмен веществ. Даже небольшое изменение ДНК может вызвать дефект в производстве белков, нейротрансмиттеров и нейрогормонов.

P1: Это может привести к тому, что люди по-особенному воспринимают окружающий мир, они могут ощущать дереализацию и деперсонализацию. Большинству из них невыносимо жить в такой субъективной реальности, которая приводит к постоянной неуверенности, беспокойству и страху.

P2: Многие из тех, кто не был вовремя диагностирован и не получил необходимой им помощи, находят решение в незаконных психотропных и психоактивных веществах, которые помогают им чувствовать себя прекрасно в течение короткого периода времени.

SUBHEADING: Почти половина всех потребителей алкоголя и наркотиков имеют двойной диагноз. Эти незаконные вещества помогают им справляться со стрессом и в основном жить своей жизнью как нормальные люди.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 11: ru/anxiety_treatment.html
Breadcrumb: О клинике → Душевное здоровье → Лечение тревожности
Hero h1: Лечение тревожности
Hero image: (см. таблицу)
```
LEAD:
Знакомо ли вам чувство тревоги, это всепоглощающее беспокойство, мешающее жить полноценной жизнью? Тревожный человек переживает постоянный страх, переутомляется из-за попыток все контролировать, испытывает неуверенность в себе и своем будущем, плохо спит из-за невозможности расслабиться.

P1: Парадокс этого состояния заключается в том, что сама по себе тревога — это не враг, а своеобразный сигнал SOS нашей психики. Чаще всего он говорит о наличии чувств, которые трудно распознать и разграничить, или о невыносимости текущей ситуации. Попытки загнать тревогу внутрь и игнорировать этот симптом — путь к нарастанию психологических проблем.

P2: Специалисты медицинского центра Монте Рехаб занимаются диагностикой и лечением всех видов тревожных состояний. Наша задача заключается в том, чтобы разобраться с причинами тревоги, обучить каждого пациента навыкам саморегуляции и дать инструменты, которые позволят справляться с тревожностью в повседневной жизни.

H2: Причины тревожности

P3: Тревожность может возникнуть в ответ на самые разнообразные жизненные обстоятельства и внутренние переживания.

P4: Одной из частых причин появления тревоги является эмоциональный стресс. Это могут быть чрезмерные профессиональные нагрузки, проблемы в отношениях с близкими, финансовые трудности и т.п. Изменения в обществе тоже создают ощущение нестабильности и вызывают страх перед будущим. Постоянный поток информации и событий может привести к перенапряжению нервной системы и тревожным состояниям различной степени интенсивности.

P5: Кроме того, повышенная тревожность может быть обусловлена наследственными особенностями и индивидуальными чертами личности. Люди с повышенной чувствительностью, склонностью к перфекционизму и низкой самооценкой часто становятся заложниками тревожного мышления. В таких случаях тревога возникает даже при отсутствии явных внешних причин, проявляясь в виде хронического беспокойства или панических атак.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 12: ru/depression_treatment.html
Breadcrumb: О клинике → Душевное здоровье → Лечение депрессии
Hero h1: Ты справляешься. Но зачем продолжать бороться в одиночку?
Hero image: (см. таблицу)
```
LEAD:
Депрессия – это не просто плохое настроение или усталость. Это состояние, которое подкрадывается незаметно и превращает даже самые простые задачи в невыносимую тяжесть. Возможно, ты чувствуешь себя одиноким. Возможно, тебе кажется, что никто не понимает, через что ты проходишь. Но это состояние можно победить.

P1: Ты можешь справиться сам. Может быть, у тебя получится. Но есть другой путь – путь, где ты не один. Где с тобой работают профессионалы, которые знают, что делают. Где ты можешь наконец-то оставить свою борьбу и просто почувствовать, что тебя поддерживают.

H2: Что такое депрессия

P2: Депрессия – это болезнь, и она не спрашивает, готов ли ты. Она забирает энергию, крадет радость и заставляет чувствовать себя бессильным.

P3: Ты можешь считать, что справишься сам. Или, может быть, тебе говорили: "просто улыбнись", "отвлекись", "соберись". Но давай будем честными: без профессиональной помощи вырваться из этого круга почти невозможно.

P4: В Монте Рехаб мы знаем, как лечить депрессию. Мы видели сотни людей, которые думали, что их случай – безнадежен. И мы знаем, что это не так.

H2: Признаки того, что тебе нужна помощь

P5: Депрессия – это не слабость, но она делает слабее. Ты можешь не замечать, как она постепенно заполняет твою жизнь. Вот на что стоит обратить внимание:

LIST:
  • Постоянная усталость. Утро начинается с мысли, что тебе просто не хочется вставать.
  • Потеря интереса. То, что раньше приносило радость, больше не вызывает никаких эмоций.
  • Изоляция. Ты избегаешь общения, даже с близкими.
  • Раздражительность или чувство пустоты. Иногда это ярость, иногда – ничего.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 13: ru/executive_burnout.html
Breadcrumb: О клинике → Душевное здоровье → Профессиональное выгорание
Hero h1: Профессиональное выгорание: когда работа забирает слишком много
Hero image: (см. таблицу)
```
LEAD:
Каждое утро начинается одинаково. Ты встаёшь с кровати, но вместо энергии чувствуешь только усталость. Твои силы будто исчерпаны, а задачи, которые раньше вдохновляли, теперь вызывают лишь раздражение. Цинизм, безразличие, эмоциональная пустота – ты чувствуешь, что перестал быть собой.

P1: Скорее всего, ты думаешь, что это временно. Что достаточно отпуска или пары выходных, чтобы всё наладилось. Но нет. Это не просто усталость. Это профессиональное выгорание – состояние, которое нельзя игнорировать.

H2: Профессиональное выгорание: что это такое

P2: Выгорание на работе – это не лень, не слабость и не отсутствие мотивации. Это состояние, когда физическое, эмоциональное и умственное истощение достигают точки, где ты больше не можешь продолжать. Это настоящий синдром.

P3: Скажу прямо: справиться с этим самостоятельно практически невозможно. Почему? Потому что ты внутри проблемы. Потому что твоё состояние – это результат длительного стресса и игнорирования собственных потребностей. Чтобы понять, что происходит, важна диагностика.

P4: В Монте Рехаб мы знаем, как помочь. Но только если ты готов помочь себе сам.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 14: ru/insomnia_treatment.html
Breadcrumb: О клинике → Душевное здоровье → Лечение бессонницы
Hero h1: Ты забыл, что такое сон?
Hero image: (см. таблицу)
```
LEAD:
Кажется, весь мир спит, а ты вновь считаешь часы на будильнике, задаваясь одним и тем же вопросом: «Почему я не могу просто закрыть глаза и отдохнуть?» Бессонница – она тихо крадется в твою жизнь, отнимает силы, снижает концентрацию, ломает привычный ритм.

P1: В какой-то момент ты даже начинаешь думать, что это нормально – не спать ночами и жить с постоянной усталостью. Но это не нормально. Сон – это основа твоего здоровья, твоего настроения, твоей жизни. И если ты чувствуешь, что потерял эту базовую потребность, знай: лечение бессонницы возможно. В Монте Рехаб мы знаем, как вернуть тебе полноценный сон.

H2: Бессонница: что это такое

P2: Давай разберемся: бессонница (или инсомния) – это не просто плохой сон. Это состояние, которое разрушает тебя изнутри. Постоянное недосыпание сказывается на работе мозга, иммунной системе, настроении. И самое главное – самостоятельно справиться с этим практически невозможно.

P3: Ты можешь пробовать считать овец, смотреть успокаивающие видео, даже принимать снотворные, но проблема не исчезнет, пока ты не найдешь её причину. Здесь и нужна помощь профессионалов – психологов и психиатров, которые понимают, что такое бессонница, и знают, как с ней бороться.

H2: Причины бессонницы

P4: Ты можешь обвинять стресс, кофе перед сном или неудобную подушку. Но бессонница – это чаще всего сложная комбинация факторов. Вот что может быть её причиной:

LIST:
  • Психологические факторы. Тревога, стресс, депрессия – все это способно лишить тебя сна.
  • Физические состояния. Боль, усталость, хронические заболевания могут быть причиной бессонницы.
  • Образ жизни. Постоянная работа за компьютером, отсутствие физической активности, неправильное питание.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 15: ru/mood_disorder_treatment.html
Breadcrumb: О клинике → Душевное здоровье → Лечение расстройства настроения
Hero h1: Лечение расстройства настроения
Hero image: (см. таблицу)
```
LEAD:
Время от времени каждый будет испытывать чувство грусти, печали и меланхолии. Например, возможно, вы недавно расстались со своим партнером, у вас был семейный конфликт или вы пропустили крайний срок выполнения проекта.

P1: Но если преобладают негативные эмоции, вас месяцами ничто не радует, и вы не обретете гармонии с окружающим миром. Это симптомы расстройства настроения.

P2: Депрессивное расстройство, сезонное аффективное расстройство, биполярное расстройство, расстройство адаптации, тревога и т.д. — все это разновидности расстройства настроения, на которые не было своевременного реагирования.

SUBHEADING: Расстройство настроения — это не просто период, который вы проживаете в негативных эмоциях, это заболевание, которое имеет разновидности и по-разному сказывается на вашем состоянии и на вашем здоровье.

P3: Со временем расстройства настроения могут привести к дезадаптации или к потере способности адаптироваться к окружающей действительности. Неадекватные эмоциональные реакции разрушают личные отношения и делают невозможным продуктивную работу.

P4: Кроме того, расстройство настроения приводит к ухудшению самочувствия, раздражению, апатии, вялости, потере аппетита, отсутствию мотивации, чувству безнадежности и т.д.

P5: Мы создаем особую среду, которая даст вам возможность разобраться в своих личных переживаниях, отдохнуть от повседневной рутины, восполнить свою жизненную энергию и научить вас справляться с трудностями, развивать здоровые привычки и контролировать свои эмоции.

CTA: Оставить заявку → #enquiry
```

---

### RU FILE 16: ru/ptsd_and_trauma_treatment.html
Breadcrumb: О клинике → Душевное здоровье → Лечение ПТСР
Hero h1: Ты сильнее своей боли. Время это доказать.
Hero image: (см. таблицу)
```
LEAD:
Жизнь после травмы может казаться сплошной темнотой. Возможно, ты всё ещё слышишь те звуки, видишь те образы или ощущаешь то, что когда-то перевернуло твой мир. Посттравматическое стрессовое расстройство (ПТСР) – это не просто воспоминания, это состояние, которое диктует твою реальность. Но это не конец. Это вызов.

P1: Проблема в том, что многие даже не догадываются, что живут с ПТСР. Ты привыкаешь к этой боли, начинаешь воспринимать её как часть себя. Но она не должна быть твоей сутью. Справиться с этим в одиночку крайне сложно.

P2: В Монте Рехаб мы понимаем, что ПТСР – это не слабость, не "надуманная проблема", а реальная реакция твоего разума и тела на травму. И мы знаем, как помочь.

H2: ПТСР: что это и почему возникает

P3: ПТСР – это больше, чем просто плохие воспоминания. Это рана, которая не заживает, потому что каждый день что-то раздирает её снова и снова. Это может быть результатом одного тяжёлого события — несчастного случая, насилия или потери — или цепочки событий, которые оставили след на твоей психике.

P4: Ты можешь чувствовать, что что-то не так, но не понимать, что именно. Может быть, это ощущение тревоги, которое не отпускает. Может быть, ты избегаешь определённых мест или людей. Или, возможно, тебе кажется, что всё вокруг утратило смысл.

P5: Но знаешь, что самое важное? Это не твоя вина. Это твоя реакция. А любая реакция может быть изменена.

CTA: Оставить заявку → #enquiry
```

---

# ═══════════════════════════════════════
# ME (MONTENEGRIN) VERSION
# ═══════════════════════════════════════

## TASK FOR MONTENEGRIN VERSION

The ME version requires translation. The workflow is:

1. Claude Code builds EN and RU versions first (32 files total)
2. A human translator (Valera) translates all RU content into Montenegrin (Crnogorski)
3. Claude Code then builds ME version using the translated content

## ME NAV STRUCTURE (from original site)

```
Logo: MonteRehab

Nav links:
- O klinici → me/index.html
- Program liječenja ▾
    Program rehabilitacije → me/stacionarno_leenje.html
    Grupna terapija        → me/grupna_terapija_online.html
- Zavisnosti ▾
    Alkoholizam                     → me/zavisnost_od_alkohola.html
    Zavisnost od droga              → me/zavisnost_od_droga.html
    Detoksikacija                   → me/medicinska_detoksikacija.html
    Liječenje ponašajnih zavisnosti → me/leenje_ponaajnih.html
    Dvostruka dijagnoza             → me/dvojna_dijagnoza.html
- Mentalno zdravlje ▾  (original says "Duhovno zdravlje")
    Liječenje anksioznosti              → me/leenje_anksioznosti.html
    Liječenje depresije                 → me/leenje_depresije.html
    Sindrom sagorijevanja na poslu      → me/izgaranje_na_poslu_kod_rukovodilaca.html
    Liječenje nesanice                  → me/leenje_nesanice.html
    Liječenje poremećaja raspoloženja   → me/leenje_poremeaja_raspoloenja.html
    Liječenje PTSP-a i trauma           → me/leenje_ptsp.html
- Cijena    → me/pricing.html
- Kontakti  → me/contacts.html
```

## ME HOME PAGE CONTENT (already in Montenegrin — from original site)

```
Hero:
  Headline:   Slobodan život bez zavisnosti
  Subline:    Dozvoli da ti pomognemo
  Button 1:   Hajde da počnemo! → #enquiry
  Button 2:   Zašto to zaista djeluje → #rec836031031

About section:
  H1: Centar za rehabilitaciju i liječenje zavisnosti u Crnoj Gori
  H2: Znamo tvoj problem – Nije tvoja krivica

  P1: Ako se boriš sa zavisnošću, može ti se činiti da izlaza nema. Ali to nije istina! Mnogi ljudi su uspješno pobijedili svoju zavisnost – i ti to možeš. Najvažnije je da nikada ne izgubiš nadu i da vjeruješ stručnjacima u centru za rehabilitaciju.

  P2: Stručnjaci u centru razumiju koliko je zavisnost složena i mogu ti pomoći da stekneš vještine i podršku koja ti je potrebna za oporavak. Uz njihovu pomoć, možeš se osloboditi lanaca zavisnosti i ponovo živjeti zdrav i ispunjen život.

  P3: Zato ne gubi nadu – javi se i potraži pomoć koja ti je potrebna da se vratiš na put oporavka. Taj put može biti težak i pun prepreka, ali uz podršku i vođenje stručnjaka iz centra, možeš doći do cilja.

Services section:
  Card 1 — Stacionarno liječenje:
    Naš tim će ti pomoći da definišeš svoje lične ciljeve prije nego što započneš program.
    Dnevne individualne terapijske sesije postavljaju temelje za trajne pozitivne promjene i pomažu u razvoju vještina samoregulacije.
    Prilikom prijema radimo kompletan ljekarski pregled i pružamo individualnu podršku za prateće zdravstvene probleme.
    Nudimo sigurne i intimne grupne radionice, online i uživo, kao podršku oporavku i prevenciji recidiva.
    CTA: Saznaj više → me/stacionarno_leenje.html

  Card 2 — Online terapija:
    Na osnovu najboljih svjetskih praksi zasnovanih na dokazima i 10 godina našeg iskustva u liječenju poremećaja ishrane, razvili smo jedinstven online program.
    Za samo tri godine, 1.500 ljudi je završilo kurs, a 83% njih je riješilo svoj problem i značajno poboljšalo kvalitet života.
    Ovo je prvo rješenje za liječenje poremećaja ishrane koje može zamijeniti tradicionalne rehabilitacione i stacionarne centre.
    Sve što treba da uradiš jeste da pratiš savjete naših stručnjaka i dijeliš svoj napredak sa timom – za sve ostalo pobrinućemo se mi.
    CTA: Saznaj više → me/grupna_terapija_online.html

Addiction section:
  Tag: Ako imaš hemijsku zavisnost
  H2: Znamo kroz šta si prošao – i ovdje smo da ti pomognemo
  Moto našeg pristupa liječenju zavisnosti je promjena kroz prihvatanje, podršku i profesionalizam.
  [REST TO BE TRANSLATED FROM RU by Valera]

Mental health section:
  [TO BE TRANSLATED FROM RU by Valera]

Pricing section:
  [Same prices as EN/RU, currency labels in Montenegrin]
```

## ME INNER PAGES

All 14 inner ME pages (all except index and contacts which have partial content above):
- Content = **translation of corresponding RU page**
- **Valera translates each RU page into Montenegrin**
- File naming = original Montenegrin slugs (see file structure above)
- Images = same Tilda CDN URLs as RU version

## ME CONTACTS PAGE

```
Hero h1: Kontakti

Napišite nam:
Telefon: +382 69 621 111
Email: montenegrorehab@gmail.com

Iz Evrope: transfer 1000€ + putni troškovi.
Iz Crne Gore: Besplatan transfer.

WhatsApp → https://wa.me/38269621111
Telegram → https://t.me/RehabMontenegro
Viber    → viber://chat?number=+38269621111

Pravne informacije:
D.o.o "ProfReab"
Roman Konevichev
UL. SVETOSAVSKA BB, BLIZIKUĆE BUDVA
Registarski broj 50945727
PIB 03332381

Adresa: Sveti Stefan, Blizikuće 85315, Montenegro
```

## ME SHARED FORM

```
Heading:    Kontaktirajte nas i počnite put ka oporavku danas
Subheading: Unesite ime i e-mail adresu i javićemo vam se
Fields:     Ime (text), E-mail (email)
Checkbox:   Slažem se da podijelim svoje podatke sa monterehab.com
Button:     Pošalji
```

## BUILD ORDER

Claude Code should build in this order:
1. All 16 EN files (root folder)
2. All 16 RU files (ru/ folder)
3. STOP — wait for Valera to translate RU→ME
4. All 16 ME files (me/ folder) using translated content

