# Nobel Prize Winners – Data Visualization Project

The Nobel Prize is one of the most prestigious international awards presented since 1901 across disciplines like Physics, Chemistry, Literature, Medicine, Peace, and Economics. In this project, we dive into over a century of Nobel data to explore trends in gender, nationality, category, and time.

## 📁 Dataset Overview

**Source:** Nobel Prize API  
**File:** `nobel.csv`  
**Columns:**

| Column               | Description                                                  |
|----------------------|--------------------------------------------------------------|
| year                 | Year the prize was awarded                                   |
| category             | Prize category (e.g. Physics, Peace)                         |
| prize                | Type of Nobel Prize                                          |
| motivation           | Motivation for the award                                     |
| prize_share          | Share of the prize won                                       |
| laureate_id          | Unique identifier for laureate                              |
| laureate_type        | Individual or organization                                   |
| full_name            | Full name of the laureate                                    |
| birth_date           | Birth date of the laureate                                   |
| birth_city           | City where laureate was born                                 |
| birth_country        | Country of birth                                             |
| sex                  | Gender of laureate                                           |
| organization_name    | Affiliated organization at the time of award (if any)        |
| organization_city    | City of the organization                                     |
| organization_country | Country of the organization                                  |
| death_date           | Death date (if applicable)                                   |
| death_city           | City of death                                                |
| death_country        | Country of death                                             |

---

## 🎯 Key Questions Answered

### ✅ What is the most commonly awarded gender and birth country?

- **Gender:** Male  
- **Birth Country:** United States of America

---

### 📈 Which decade had the highest ratio of US-born Nobel Prize winners?

- Decade with highest US-born winner ratio was **2000s**  
- This trend was visualized using a **line plot** showing the rise in American dominance over time.

---

### 👩‍🔬 Which decade and Nobel category had the highest proportion of female laureates?

- **Decade:** 2000s  
- **Category:** **Peace** had the highest share of female laureates

Visualized using a **multi-line plot** showing female winner proportions over time by category.

---

### 🥇 Who was the first woman to receive the Nobel Prize?

- **Marie Curie, née Sklodowska**  
- **Category:** Physics  
- **Year:** 1903

---

### 🔁 Which individuals or organizations have won more than one Nobel Prize?

- **Marie Curie, née Sklodowska** – Physics & Chemistry  
- **John Bardeen** – Twice in Physics  
- **Frederick Sanger** – Twice in Chemistry  
- **Linus Carl Pauling** – Peace & Chemistry  
- **International Committee of the Red Cross** – Multiple Peace Prizes  
- **UNHCR (UN Refugee Agency)** – Multiple Peace Prizes

---

## 📊 Visualizations

- US-born winner trends by decade
- Female representation by decade and category
- Distribution of awards over time
- First female laureate highlight
- Repeated Nobel Prize winners list

---

## 🎓 Learning Outcomes

- Performed groupby and aggregation using `pandas`
- Worked with time-based data (decade grouping)
- Applied boolean masking and filtering on complex conditions
- Created multi-line plots using `seaborn` and `matplotlib`
- Discovered key insights from a historical global dataset
