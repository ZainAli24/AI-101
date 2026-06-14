# 🤖 AI-201 — Agentic AI Orientation
## Class 01 & 02 Notes: The Agent Factory Thesis

> **Course:** Fundamentals of Agentic AI (AI-101) — Panaversity
> **Source:** Orientation Session Slides + [agentfactory.panaversity.org](https://agentfactory.panaversity.org)
> **Level:** Beginner-friendly notes

---

## 📌 Table of Contents

1. [Kyun Abhi? — SaaSpocalypse](#1-kyun-abhi--saaspocalypse)
2. [Key Vocabulary](#2-key-vocabulary)
3. [AI-Native Company kya hoti hai?](#3-ai-native-company-kya-hoti-hai)
4. [The Agent Factory Thesis](#4-the-agent-factory-thesis)
5. [Paradigm Shift: SaaS vs Agent Factory Era](#5-paradigm-shift-saas-vs-agent-factory-era)
6. [The Production Engine](#6-the-production-engine)
7. [The 10-80-10 Rule](#7-the-10-80-10-rule)
8. [Two Modes of Agent Use](#8-two-modes-of-agent-use)
9. [The Two-Layer Model](#9-the-two-layer-model)
10. [The 7 Invariants of the Agent Factory](#10-the-7-invariants-of-the-agent-factory)

---

## 🔥 1. Kyun Abhi? — SaaSpocalypse

### Pehle ek simple scene socho:

Tum ek **lawyer** ho. Tumhari job hai contracts padhna, legal documents check karna, NDAs review karna. Tumhari company tumhein **$500/month** deti hai kisi software ka license — jaise Thomson Reuters ka legal software — taake tum efficiently kaam kar sako.

Ab ek din Anthropic aata hai aur kehta hai:

> *"Hamara AI agent yeh sab kaam khud kar sakta hai — bina us software ke, bina us lawyer ke."*

**Socho ab us software company ka kya hoga?**

---

### February 4, 2026 — Woh Din

Anthropic ne ek kaam kiya — apne **Claude Cowork** platform mein **11 free plugins** release kiye. Yeh plugins in fields ke liye thay:

- ⚖️ Legal (contracts, NDAs)
- 💰 Finance (reports, audits)
- 📊 Sales
- 📣 Marketing
- 🔢 Data Analysis

**Koi bhi in plugins ko free mein use kar sakta tha.**

Iska matlab tha ke ab woh kaam jo insaan karta tha — aur jis ke liye companies mehenge software khareedti thin — ab AI agent seedha kar sakta tha.

---

### Stock Market ka reaction — "SaaSpocalypse"

Jab investors ne yeh suna, unhone socha:

> *"Agar AI yeh kaam kar sakta hai toh logon ko yeh mehenga software kyun khareedna hai?"*

Aur unhone uss software ki companies ke shares bechne shuru kar diye. Ek hafte mein:

| Company | Share price gira |
|---------|-----------------|
| Thomson Reuters (legal software) | **-16%** |
| Salesforce (sales/CRM software) | **-7%** |
| ServiceNow (enterprise software) | **-7%** |

> Sirf ek **legal AI plugin** ne **$285 billion** wipe kar diya — ek hi trading session mein.

> Poori software industry mein nearly **$1 trillion** ki value khatam ho gayi.

Log is event ko **"SaaSpocalypse"** kehne lage — **SaaS** (Software as a Service) + **Apocalypse** (tabahi) = SaaSpocalypse.

---

### Lekin kyun? Root cause kya tha?

Pehle samjho — **SaaS model kya tha:**

> Tum ek software khareedti thi → Ek human us software ko use karta tha → Woh human kaam deliver karta tha.

**Value insaan mein thi** — software sirf ek tool tha jis se insaan kaam karta tha.

Ab AI ne yeh sab badal diya:

> AI agent khud software use kar sakta hai → Khud kaam kar sakta hai → Outcome directly deliver kar sakta hai.

**Ab insaan ko software "operate" karne ki zaroorat nahi rahi.**

Isliye market ne decide kiya:

> **Woh companies jo sirf "per-seat software" bechti hain — unki value khatam ho rahi hai.**

---

### Anthropic ki apni value ka safar:

Yeh sab hote hue Anthropic ki khud ki value rocket ki tarah upar gayi:

| Mahina | Valuation |
|--------|-----------|
| February 2026 | $380 Billion |
| April 2026 | $800 Billion |
| May 2026 | **$965 Billion** |

Ab yeh interesting comparison dekho:

> 🇮🇳 India ki **top 6 IT companies** (TCS, Infosys, Wipro, HCL, etc.) milkar **1.9 million logon** ko employ karti hain aur unki combined value roughly **$300 Billion** hai.

> Anthropic ke paas sirf **~1,000 employees** hain — lekin yeh **$965 Billion** ka hai — yani **3.2x zyada valuable**.

**Matlab:** 1,000 log + AI = 1,900,000 logon se 3 guna zyada valuable.

---

### Citrini Quote — Is sab ka summary ek line mein

Ek researcher Citrini ne likha:

> *"For the entirety of modern economic history, human intelligence has been the scarce input. We are now experiencing the unwind of that premium."*

**Iska matlab simple Roman Urdu mein:**

Puri history mein — jab se economy shuru hui hai — sabse **qeemti (scarce) cheez** insaan ka **dimagh** tha. Companies insaani soch, insaani skill ke liye pay karti thin.

Ab AI aa gaya — aur woh **"dimagh waala kaam"** bhi kar sakta hai.

Toh insaani dimagh ka jo **"premium"** (extra value) tha — woh **"unwind"** ho raha hai — yani khatam ho raha hai, uth raha hai.

> **Short mein:** Pehle dimagh = money. Ab AI = money. Insaani dimagh ka monopoly khatam.

---

## 2. Key Vocabulary

Yeh terms baar baar aayenge — in ko yaad rakhna zaroori hai:

<details>
<summary><strong>🏭 Agent Factory kya hai?</strong></summary>

<br>

**Agent Factory** ek **process** hai — na koi product jo tum buy karo.

Yeh woh method aur architecture hai jisse AI Workers design kiye jaate hain, banaye jaate hain, aur deploy kiye jaate hain. Yeh ek practice hai jo tum adopt karte ho.

> **Analogy:** Jaise ek car factory cars banati hai — Agent Factory AI Workers banati hai.

</details>

---

<details>
<summary><strong>🏢 AI-Native Company kya hai?</strong></summary>

<br>

**AI-Native Company** woh company hai jis ka **output** Agent Factory produce karta hai.

- Is company mein workforce mostly AI hai
- Yeh company jo bhi sell karta hai — woh uski AI workforce produce karti hai: software, decisions, services, transactions
- **Tum is company se kuch buy nahi karte. Tum is ki AI workforce hire karte ho.**

> **Example:** Kal ek legal firm the jahan 100 lawyers kaam karte the. Aaj ek AI-Native Company ke paas 5 humans hain aur baaki sab AI Workers hain jo wahi kaam karte hain — 24/7, bina break ke.

</details>

---

<details>
<summary><strong>👷 AI Workers / Digital FTEs kya hain?</strong></summary>

<br>

**AI Workers** (jinhein **Digital FTEs** bhi kehte hain) woh role-based AI agents hain jo AI-Native Company ke andar kaam karte hain.

- **FTE** = Full-Time Employee
- Yeh chatbots nahi hain — yeh real kaam karne wale employees hain
- Yeh hire hote hain, kaam assign hota hai, aur retire bhi hote hain
- Example roles: Customer Support Worker, Data Analysis Worker, Finance Worker, Legal Worker

> **Simple:** Ek human employee ki tarah — bas yeh AI hai, kabhi thakta nahi, 24/7 kaam karta hai.

</details>

---

<details>
<summary><strong>📋 System of Record kya hai?</strong></summary>

<br>

**System of Record** company ka **official data** hai — woh substrate jis ke upar AI workforce kaam karta hai.

- Databases, ledgers, platforms
- Yeh company ki "sach" hai — jo truth AI Workers padhte aur likhte hain
- Example: Shopify (orders ka record), QuickBooks (accounts ka record)

> **Analogy:** Jaise ek office mein main register hota hai jis mein sab kuch likha hota hai — yeh wahi hai.

</details>

---

<details>
<summary><strong>🎯 Engagement kya hoti hai?</strong></summary>

<br>

**Engagement** ek bounded interaction hai human aur general agent ke darmiyan.

Do types hain:
1. **Problem-solving engagement** — agent se seedha kaam karwao, session khatam, outcome mile
2. **Manufacturing engagement** — agent use karke ek AI Worker banao jo permanently kaam kare

</details>

---

## 3. AI-Native Company kya hoti hai?

> **Key sentence:** *You don't buy from these companies. You hire them.*

AI-Native Company mein:
- Workforce mostly **AI** hai
- Product woh hai jo yeh AI workforce produce kare
- **Humans** intent define karte hain aur outcomes verify karte hain
- **AI Workers** execution karte hain

### Agentic AI ke agents economic actors bante ja rahe hain:

Yeh sirf kaam karne wale tools nahi rehe — ab yeh khud cheezein khareed sakte hain:

| Protocol | Company | Kaam |
|----------|---------|------|
| **ACP** | OpenAI + Stripe | ChatGPT ke andar agent kuch buy kare |
| **AP2** | Google | 60+ companies ka cross-vendor payment standard |
| **x402** | Coinbase | Crypto-native payments for agents |
| **MPP** | Stripe / Tempo | Micropayments — pennies per second |

> **Matlab:** AI agents ab khud compute khareed sakte hain, data procure kar sakte hain, services pay kar sakte hain — bina har step pe human approval ke.

---

## 4. The Agent Factory Thesis

### Ek line mein:

> *"In the AI era, the most valuable companies won't sell software — they'll manufacture AI employees."*

### Car Factory Analogy:

Jaise ek car factory mein:
- **Raw material** (steel, rubber) andar jaata hai
- **Specialized stations** par kaam hota hai (welding, painting, assembly)
- **Finished car** bahar aati hai — inspected aur ready

Agent Factory mein:
- **Raw material** = Tumhara intent (tum kya chahte ho)
- **Specialized stations** = AI Workers (har ek ek specific kaam karta hai)
- **Finished product** = Verified outcome (actual result, check kiya hua)

### Teen cheezein factory ko power karti hain:

1. **Specs** — likhit instructions jo AI Workers ko batati hain kya karna hai
2. **Skills** — packaged abilities jo har AI Worker use karta hai
3. **Feedback loops** — system sikhta rehta hai apne results se

### Connecting standard:

**MCP (Model Context Protocol)** — yeh ek universal standard hai jo har AI Worker ko har tool se connect karta hai.

> **Analogy:** Jaise factory mein har device ek hi type ke power outlet mein plug hoti hai — MCP wahi hai AI Workers ke liye.

---

## 5. Paradigm Shift: SaaS vs Agent Factory Era

| Feature | SaaS Era (Tools) | Agent Factory Era (Labor) |
|---------|-----------------|--------------------------|
| **Product** | Software Tools | AI Employees |
| **Value** | Per-Seat Subscriptions | Per-Outcome Results |
| **Execution** | Manual & Visible | Automated & Industrialized |
| **Resources** | Humans buy tools | Agents buy compute/data autonomously |
| **Human Role** | Operator | Supervisor & Verifier |
| **Integration** | APIs (rigid) | MCP (flexible) |
| **Focus** | HOW kaam hota hai | THAT kaam hua — verified |

> **Short:** Pehle tum software ko tool ki tarah use karte the. Ab tum AI Workers ko hire karte ho jo kaam deliver karte hain.

---

## 6. The Production Engine

Yeh Agent Factory ka sabse important concept hai.

```
[INTENT] ──► [PRODUCTION ENGINE] ──► [OUTCOME]
  ↑                                      ↑
Human defines                    Human verifies
```

### Teen layers:

1. **Intent** — High-level blueprint: goals, constraints, budgets, permissions (human deta hai)
2. **Production Engine** — Intent ko outcomes mein transform karta hai (AI Workers kaam karte hain)
3. **Outcome** — High-fidelity actions aur artifacts, verified for accuracy

### Human ka role change hua:

| Pehle | Ab |
|-------|-----|
| Operator | Supervisor |
| Typist | Editor |
| Coder | Architect of Outcomes |

> **Agent Factory human ko replace nahi karta — yeh human ko promote karta hai.**

---

## 7. The 10-80-10 Rule

### Steve Jobs se seekhi gayi lesson:

Steve Jobs pehle micromanager the — Mac calculator ka har pixel khud control karte the. Phir unhone shift ki: **10% vision, 80% team kare, 10% polish.** Apple duniya ki sabse valuable company bani.

### Ab yeh AI par apply hota hai:

| Phase | Jobs ki Apple | Agent Factory |
|-------|--------------|---------------|
| **First 10% — Intent** | Jobs vision set karta hai | Human spec define karta hai: goals, budget, permissions |
| **Middle 80% — Execution** | Apple ki teams build karti hain | AI Workers execute karte hain: tools compose, sub-agents spawn, outcomes deliver |
| **Final 10% — Verification** | Jobs polish karta hai "ship it" | Human review, refine, aur approve karta hai |

### Real-world proof (February 2026):

> Cursor reports karta hai ke uski apni product mein **35% pull requests** autonomous agents ne produce kiye — humans ne problem define ki aur artifacts review kiye, line-by-line guide nahi kiya.

### Simple formula tumhare liye:

- **Pehle 10%** = Clear prompt do, context do, constraints batao
- **Middle 80%** = AI Worker kaam kare — summarize, generate, analyze, format
- **Final 10%** = Tum review karo, refine karo, approve karo

> **Tumhara din badlega:** 80% execution se free ho jao, 100% attention wahan lagao jo sirf insaan kar sakta hai.

---

## 8. Two Modes of Agent Use

General agents (jaise Claude Code, Claude Cowork) do tareekon se use hote hain:

<details>
<summary><strong>Mode 1 — Problem-Solving Engagement</strong></summary>

<br>

**Kab use hota hai:** Jab tumhe abhi, is session mein, ek problem solve karni ho.

- Developer Claude Code mein khaolta hai aur service refactor karta hai
- Finance analyst Claude Cowork mein quarterly close model banata hai
- Session khatam — outcome directly tumhare paas

**Governed by:** Seven Principles

1. **Bash is the Key** — Agent act kare, sirf describe na kare
2. **Code as Universal Interface** — Structured formats use karo, prose nahi
3. **Verification as Core Step** — Har meaningful output check hoga pehle
4. **Small, Reversible Decomposition** — Chote steps mein kaam karo, har step undo ho sake
5. **Persisting State in Files** — Jo matter kare woh file mein save karo
6. **Constraints and Safety** — Explicit permissions, explicit scope
7. **Observability** — Tum dekh sako agent ne kya kiya — no black boxes

**Tools:**
- Engineers → Claude Code / OpenCode
- Domain experts → Claude Cowork / OpenWork

</details>

---

<details>
<summary><strong>Mode 2 — Manufacturing Engagement</strong></summary>

<br>

**Kab use hota hai:** Jab tumhe kuch permanent banana ho — ek AI Worker jo session ke baad bhi kaam karta rahe.

- Developer Claude Code se ek code-review AI Worker banata hai
- Finance analyst (+ engineer ke saath) month-end close Worker deploy karta hai
- Output = AI Worker jo company mein join ho jaata hai

**Governed by:** Seven Invariants (agla section)

**Tool:** Hamesha Claude Code / OpenCode — chahe kaun bhi operate kare — kyunki AI Worker banana fundamentally ek coding task hai.

> **Key difference:** Mode 1 mein general agent khud worker hai. Mode 2 mein general agent Worker banane ka manufacturing tool hai.

</details>

---

## 9. The Two-Layer Model

AI-Native Company do layers par chalti hai:

```
┌─────────────────────────────────────────┐
│           EDGE LAYER                    │
│  Personal Identic Agents (tumhara       │
│  personal AI delegate/chief of staff)   │
└──────────────────┬──────────────────────┘
                   │ delegates work
                   ▼
┌─────────────────────────────────────────┐
│         AI WORKFORCE LAYER              │
│  Role-based AI Workers jo kaam karte   │
│  hain — Support, Finance, Legal, etc.  │
└─────────────────────────────────────────┘
```

| Layer | Kya Hai | Kis ke liye | Kya Karta Hai |
|-------|---------|-------------|---------------|
| **Edge Layer** | Personal identic agents | Individual human | Intent translate karo, AI Workers ko delegate karo |
| **AI Workforce Layer** | Role-based AI Workers | Enterprise | Tasks execute karo, workflows coordinate karo, outcomes deliver karo |

### Identic AI kya hai?

Don Tapscott (business thinker) ne yeh term diya — **"Identic"** kyunki yeh agent tumhari **identity** carry karta hai:
- Tumhara judgment
- Tumhara preferences
- Tumhara authority

Yeh generic assistant nahi — yeh **tumhara representative** hai.

> **Neither layer works alone:** Personal agents without workforce = digital assistant with no one to command. Workforce without personal agents = humans manually orchestrating sab kuch — wahi failure mode jo Agent Factory eliminate karna chahta hai.

---

## 10. The 7 Invariants of the Agent Factory

> **Invariant kya hota hai?** Woh rule jo kabhi nahi badalta — chahe tools badlein, products badlein, saal badlein. Yeh building ka structure hai, furniture nahi.

---

<details>
<summary><strong>Invariant 1 — The human is the principal</strong></summary>

<br>

**Rule:** Har kaam ki chain ek insaan se shuru hoti hai — jo intent set kare, budget define kare, authority envelope kheenche, aur outcome ka zimmedaar ho. Koi exception nahi.

**Kyun zaroori hai:**
Intent khud generate nahi hoti. Judgment, values, budget authority, aur accountability transfer nahi ho sakti.

**Agar absent ho toh:**
Unowned systems produce karte hain unaccountable outcomes. Liability evaporate ho jaati hai. Budget ka koi owner nahi.

**Lahore Online Store Example:**

> Malik (owner) ne decide kiya ke AI customer complaints handle kare. AI woh karta hai — lekin agar koi customer 5000 rupay se zyada refund maange, toh AI khud approve nahi karega. Malik ko batayega. Insaan ki approval zaroori hai.

- `Owner sets goals`
- `AI follows rules`
- `Human approves big decisions`

</details>

---

<details>
<summary><strong>Invariant 2 — Every human needs a delegate</strong></summary>

<br>

**Rule:** Ek insaan apna intent manually dozens of AI Workers tak scale nahi kar sakta. Usse ek personal agent chahiye jo uska context rakhe, uska judgment represent kare, uski authority carry kare, aur downstream kaam broker kare.

**Kyun zaroori hai:**
Ek insaan 20 alag AI workers ko manage nahi kar sakta.

**Agar absent ho toh:**
Human bottleneck ban jaata hai. AI Workforce Layer idle baithti hai. Scale collapse ho jaata hai human typing speed tak.

**Current tool:** OpenClaw (Panaversity ka delegate)

**Lahore Online Store Example:**

> Owner Sara ke paas ek personal AI delegate hai jiska naam **'Sara's Assistant'** hai. Sara kehti hai _'aaj ke orders check karo'_ — aur yeh delegate automatically Order Worker, Inventory Worker, aur Shipping Worker ko kaam deta hai. Sara ko har ek se directly baat nahi karni padti.

- `Sara (owner)`
- `Sara's Delegate AI`
- `Orders Worker`
- `Shipping Worker`

</details>

---

<details>
<summary><strong>Invariant 3 — The workforce needs a management layer</strong></summary>

<br>

**Rule:** AI Workers ka dhair lagana company nahi hoti. Workforce ko ek management layer chahiye — AI-Native Company ka operating system — jo Workers hire kare, kaam assign kare, budgets enforce kare, risk approve kare, lifecycle manage kare.

**Kyun zaroori hai:**
Coordination, accountability, aur economic discipline individual agents ki emergent properties nahi hain.

**Agar absent ho toh:**
Workers collide karein ge. Budgets leak honge. Audit trail fracture ho jaayega. Retire hue Workers chalte rahenge.

**Current tool:** Paperclip (Panaversity ka management layer)

**Lahore Online Store Example:**

> Ek **'Operations Manager AI'** hai. Yeh dekhta hai ke Support Worker zyada busy hai, toh ek extra Support Worker automatically start ho jata hai. Sales mein slow season hai toh Marketing Worker ka budget kam ho jata hai. Manager decide karta hai — insaan approve karta hai.

- `Operations Manager AI`
- `Support Worker x2`
- `Marketing Worker`
- `Inventory Worker`

</details>

---

<details>
<summary><strong>Invariant 4 — Each worker picks its own engine (AI model)</strong></summary>

<br>

**Rule:** Sab AI Workers ek hi model use nahi karte. Har Worker woh model use karta hai jo uske kaam ke liye sahi ho — capability, cost, aur latency ke hisaab se.

**Kyun zaroori hai:**
Ek powerful (mehenga) model har cheez pe waste karna uneconomical hai. Routine kaam ke liye cheap fast model kaafi hai.

**Agar absent ho toh:**
Ya toh quality suffer hogi (sab cheap models use karein) ya cost explode hogi (sab powerful models use karein).

**Lahore Online Store Example:**

> Ek angry customer ka jawab likhna — iske liye powerful **GPT-4** use hoga jo samajhdari se reply kare. Lekin 1000 order confirmation emails bhejne ke liye — iske liye simple fast model kaafi hai.
>
> ✅ Important kaam = achi engine
> ✅ Routine kaam = cheap engine

- `Powerful AI: complaints`
- `Budget AI: bulk emails`
- `Mid-tier: product descriptions`

</details>

---

<details>
<summary><strong>Invariant 5 — Every worker uses a system of record</strong></summary>

<br>

**Rule:** Har AI Worker company ka authoritative data source (system of record) use karta hai — na ki apni cached ya assumed knowledge.

**Kyun zaroori hai:**
Agar AI ke paas real data nahi toh woh "guess" karega ya made-up information dega.

**Agar absent ho toh:**
Workers stale ya incorrect data pe act karein ge. Conflicting states emerge honge. Outcomes unverifiable honge.

**System of record = company ki official memory.**

**Lahore Online Store Example:**

> Support Worker jab customer ka order status batata hai, woh directly **Shopify database** se data uthata hai — real tracking number, real delivery date. Agar database se connected na hota toh woh galat ya made-up information de sakta tha.
>
> ✅ Real data = trustworthy AI

- `Support Worker ↔ Shopify DB`
- `Inventory Worker ↔ Stock System`
- `Finance Worker ↔ Accounts`

</details>

---

<details>
<summary><strong>Invariant 6 — The workforce can self-expand under policy</strong></summary>

<br>

**Rule:** Jab demand badhe, system automatically naye AI Workers spawn kar sakta hai — lekin sirf us policy envelope ke andar jo human ne define ki hai. Uncontrolled growth invariant ka violation hai.

**Kyun zaroori hai:**
Manual scaling = bottleneck. Uncontrolled scaling = budget explosions aur unaccountable systems.

**Agar absent ho toh:**
Demand spikes mein workforce manually scale karni padegi. Ya uncontrolled growth costs explode karegi.

**Lahore Online Store Example:**

> Eid ke season mein orders 10x ho jaate hain. System automatically 3 extra Support Workers deploy karta hai — lekin sirf tab jab monthly budget **50,000 rupay** se kam ho. Budget limit cross hone par insaan se permission maangta hai. Rules ke andar automatic growth.

- `Normal season: 1 worker`
- `Eid season: 4 workers`
- `Budget limit = human control`

</details>

---

<details>
<summary><strong>Invariant 7 — The company runs on a nervous system</strong></summary>

<br>

**Rule:** AI-Native Company ek event-driven nervous system par chalti hai — jaise hamare body ka nervous system signals automatically bhejta hai bina consciously sochne ke. Events automatically ek Worker se doosre tak travel karte hain.

**Kyun zaroori hai:**
Manual handoffs = latency, errors, aur missed steps. Yeh wahi failure modes hain jo Agent Factory eliminate karna chahta hai.

**Agar absent ho toh:**
Humans manually coordinate karein ge Workers ke darmiyan. Workflow bottleneck ban jaayega human coordination pe. System crashes se recover nahi kar payega.

**Lahore Online Store Example:**

> Customer ne order place kiya → automatically Order Worker activate hota hai → Inventory Worker stock check karta hai → Shipping Worker label print karta hai → Customer ko SMS jaata hai.
>
> Poori chain automatic hai. Koi step miss nahi hoti. Agar kuch break ho toh system khud recover karta hai.

- `Order placed`
- `→ Inventory checked`
- `→ Label printed`
- `→ SMS sent (auto)`

</details>

---

## 💡 Key Takeaways

> **Tools change. Invariants stay.**
> Yeh 7 rules AI-Native Company ki **constitution** hain.

### Ek line mein poori class:

| Concept | Short mein |
|---------|-----------|
| **SaaSpocalypse** | AI agents ne $1T software value destroy ki — market ne AI ki taaqat recognize ki |
| **AI-Native Company** | Jis company ka workforce mostly AI ho |
| **Agent Factory** | Process jo AI Workers banata hai |
| **Digital FTE** | AI Worker = AI Employee jo real kaam karta hai |
| **10-80-10 Rule** | 10% intent + 80% AI execution + 10% human verification |
| **Two-Layer Model** | Edge Layer (personal delegate) + AI Workforce Layer |
| **7 Invariants** | Constitution jo kabhi nahi badlati |

---

## 📚 Resources

- 📖 Book: [agentfactory.panaversity.org](https://agentfactory.panaversity.org)
- 📖 Thesis: [agentfactory.panaversity.org/docs/thesis](https://agentfactory.panaversity.org/docs/thesis)
- 📖 Preface: [agentfactory.panaversity.org/docs/preface-agent-native](https://agentfactory.panaversity.org/docs/preface-agent-native)

---

*Notes by: Zain Ali | AI-101 Class 01 | Panaversity*