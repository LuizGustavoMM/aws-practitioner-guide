# AWS Cloud Practitioner (CLF-C02) and AI Practitioner (AIF-C01) study kit

Free, self-contained study material for the two foundational AWS certifications: two field guides and two practice exams, plus a plain-English walkthrough of AWS Skill Builder, which is where the official (and mostly free) training lives.

Everything here is a single HTML file. No install, no build step, no account. Open it in a browser and it works, on desktop or phone. Your progress is saved in your own browser and nowhere else.

---

## What is in this kit

| File | What it is |
|---|---|
| `aws-cloud-practitioner-guide.html` | CLF-C02 field guide: every service and concept likely to appear, with the exam angle for each |
| `aws-clf-c02-practice-exam.html` | 65 original CLF-C02 practice questions, exam mode and practice mode |
| `aws-ai-practitioner-guide.html` | AIF-C01 field guide: AI/ML and generative AI concepts plus the AWS AI services |
| `aws-aif-c01-practice-exam.html` | 65 original AIF-C01 practice questions |

### Features of the guides
- Search across every service, keyword and note (press `/`).
- **Recall mode** blurs the explanations so you can test yourself before revealing.
- Tick each service you already know; progress is saved and shown per section.
- **Flashcards**, in both directions (service → what it does, or description → service), with a deck for the commonly confused services only.
- Review sheets: **trigger words** (exam phrase → service), **look-alikes** (how to tell confusable services apart), and **numbers to memorize**.
- Dark mode, and printable.

### Features of the practice exams
- **Exam mode:** 90-minute timer, flag for review, question map, no feedback until you finish.
- **Practice mode:** no timer, explanation after each question.
- Score breakdown per exam domain, so you can see which domain is weakest.
- Review only the questions you got wrong, and retake just those.
- A button that copies your mistakes as text, so you can paste them into an AI assistant or your notes.

### About the questions
They are **original questions**, written to match the style, domain weighting and difficulty of the real exams. They are **not** real exam questions. Sites that sell or share actual exam content ("dumps") violate the AWS Certification Program Agreement, and using them can get your certification revoked. They are also frequently wrong. Use these, the official AWS practice question sets, and reputable paid providers instead.

---

## Suggested study path

1. **Read the exam guide PDF** for your certification (linked from the certification page below). It lists exactly what is in scope.
2. **Take the free AWS Skill Builder course** for your certification (see the next section).
3. **Work through the field guide** in this kit. Tick off the services you can explain without looking.
4. **Drill the look-alikes.** Most failures come from confusing two similar services, not from never having heard of one.
5. **Take a practice exam in practice mode**, read every explanation, and note your weakest domain.
6. **Go back to the guide** for that domain, then take the exam again in **exam mode**.
7. **Book when you consistently score 80%+** on full runs. The passing score is 700/1000, which is roughly 70% correct, but the conversion is not exact, so leave yourself a margin.

Typical preparation time: 20–40 hours for Cloud Practitioner if you are new to cloud, less if you already work in IT. Similar for AI Practitioner, and less if you already hold Cloud Practitioner, because the two overlap on AWS basics.

---

## How to use AWS Skill Builder (the part nobody explains)

**AWS Skill Builder** is AWS's own online learning platform: <https://skillbuilder.aws/>. It is where the official courses, exam prep plans and hands-on labs live. It confuses people because it mixes free and paid content on the same screens, and because "exam prep" and "courses" are different things.

### Step 1: Create an AWS Builder ID

Go to <https://skillbuilder.aws/> and sign up. Use an **AWS Builder ID**, which is a personal login separate from any AWS account, and register it with a **personal email** so you keep access to your certifications and badges if you change jobs or schools. You do **not** need an AWS account with a credit card to use Skill Builder.

### Step 2: Understand free versus subscription

**Free (no payment):**
- 600+ on-demand digital courses, including the full course for each certification.
- Learning plans and Exam Prep Plans (the free parts of them).
- One **official practice question set** per certification, usually 20 questions, with explanations.
- Some game-based and introductory content.

**Individual subscription (around $29/month, or an annual plan; price varies by country and changes over time):**
- **AWS Builder Labs**: 200+ hands-on labs in a real AWS console with no risk to your own account or bill.
- **Official Practice Exams**: full-length, scored simulations that mirror the real exam.
- **Exam Prep Enhanced Courses** and Domain Practice.
- **AWS Cloud Quest** and **AWS Industry Quest** (role-playing games where you solve real architecture tasks), **AWS SimuLearn**, **AWS Escape Room** (available for AI Practitioner), and **AWS Jam** challenges.
- **AWS Digital Classroom** on annual plans.

For the two foundational exams in this kit, **the free tier plus this study kit is enough to pass**. The subscription is worth it if you want hands-on labs, which matter much more for associate-level exams later.

Check for free access before paying: AWS regularly runs promotions giving free subscription access, and students and members of AWS emerging-talent programs can get 12 months of Skill Builder subscription free. Employers with AWS Partner or Enterprise agreements often have team subscriptions too. Search the AWS Training and Certification blog for current offers.

### Step 3: Find the right content (this is where people get lost)

There are three different things on Skill Builder, and you want them in this order:

1. **The course** teaches the material.
   - Search for **"AWS Cloud Practitioner Essentials"** (free, about 6 hours). This is the same content AWS uses in its paid instructor-led class.
   - For AI, search for **"AWS Certified AI Practitioner"** and take the free **"Fundamentals of Machine Learning and Artificial Intelligence"**, **"Introduction to Generative AI"** and **"Amazon Bedrock Getting Started"** courses in the AI Practitioner plan.

2. **The Exam Prep Plan** organizes your preparation. Search for **"Exam Prep Plan: AWS Certified Cloud Practitioner (CLF-C02)"** or **"Exam Prep Plan: AWS Certified AI Practitioner (AIF-C01)"**. Each plan follows four steps:
   - **Step 1 – Orientation:** what the exam covers, the domains and their weighting.
   - **Step 2 – Assess:** the free **Official Practice Question Set** (20 questions) to find your gaps, and the Official Pretest with a subscription.
   - **Step 3 – Review and practice:** free **Domain Review** courses per domain, plus Domain Practice and labs with a subscription.
   - **Step 4 – Final assessment:** the full **Official Practice Exam** (subscription) before booking.

3. **Hands-on practice** cements it. With a subscription, use **AWS Builder Labs** and **Cloud Quest: Cloud Practitioner**. Without one, create a personal AWS account on the Free Tier and build something small: launch an EC2 instance, host a static site on S3, create an IAM user, and try Amazon Bedrock in the console. Set a **budget alert** first so you never get a surprise bill.

### Step 4: Follow the certification track

Foundational certifications have **no prerequisites**. A sensible order:

- **AWS Certified Cloud Practitioner (CLF-C02)** → the vocabulary and services of AWS.
- **AWS Certified AI Practitioner (AIF-C01)** → AI/ML and generative AI on AWS. It assumes basic AWS familiarity, so it pairs naturally after Cloud Practitioner.
- Then, if you want to go deeper: **Solutions Architect – Associate**, **Developer – Associate**, or **SysOps Administrator – Associate**, and afterwards the professional and specialty exams.

### Step 5: Book and take the exam

- Register through your **AWS Certification account** at <https://aws.amazon.com/certification/>. Booking goes through Pearson VUE.
- Both exams: **65 questions, 90 minutes, USD 100, scaled score 100–1000 with 700 to pass**. 50 questions are scored and 15 are unscored research questions that do not affect your result.
- Choose a **test center** or **online proctored** exam. Online means a quiet, private room, a clear desk, a webcam room scan and no interruptions. If that is hard to guarantee, take it at a center.
- If English is not your first language, request the **ESL +30 minutes** accommodation in your certification account **before** booking. It is free.
- There is no penalty for a wrong answer, so **never leave a question blank**. Flag and return to the hard ones.
- Certifications are valid for **3 years**. Passing usually earns a **50% discount voucher** for your next exam, plus practice-exam benefits, all visible in your certification account.

### Official links

- AWS Skill Builder: <https://skillbuilder.aws/>
- All AWS certifications: <https://aws.amazon.com/certification/>
- Cloud Practitioner (exam guide PDF and sample questions): <https://aws.amazon.com/certification/certified-cloud-practitioner/>
- AI Practitioner (exam guide PDF and sample questions): <https://aws.amazon.com/certification/certified-ai-practitioner/>
- AWS Training and Certification blog (new courses and free promotions): <https://aws.amazon.com/blogs/training-and-certification/>
- AWS Free Tier (for hands-on practice): <https://aws.amazon.com/free/>

---

## How to use these files

Download the HTML files and open them in any browser, or host them anywhere static (GitHub Pages, S3, Netlify). There are no dependencies beyond a web font loaded from Google Fonts, and the pages still work without it.

To publish with GitHub Pages: push the files to a repository, then in **Settings → Pages** choose the `main` branch and the root folder. The files become available at `https://<user>.github.io/<repo>/aws-cloud-practitioner-guide.html`.

Your progress (services ticked, exam attempts) is stored in your browser's local storage. It is private to you, never leaves your device, and is cleared if you clear site data.

---

## Accuracy and contributions

AWS changes services, prices and support tiers constantly. The content reflects the CLF-C02 and AIF-C01 exam guides as of **September 2026**. Always confirm current details against the official exam guide and AWS documentation. Corrections and additional questions are welcome.

## License

Use, copy, modify and share freely. Not affiliated with or endorsed by Amazon Web Services. "AWS" and the certification names are trademarks of Amazon.com, Inc. or its affiliates.
