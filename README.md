# 🏅 Nobel Prize Data Analysis

This project analyzes patterns in Nobel Prize winners from 1901 to 2023 using Python and the pandas library.  
It answers key questions about gender, geography, category distribution, and repeat winners over more than a century of Nobel history.

The dataset used is `nobel.csv`, obtained from the official [Nobel Prize API](https://nobelprize.org), and stored locally in the `/data` directory.

---

## 📊 Questions Explored

This project answers the following questions:

1. **What is the most commonly awarded gender and birth country?**  
   - `top_gender`: `'Male'`  
   - `top_country`: `'United States of America'`

2. **Which decade had the highest ratio of US-born Nobel Prize winners to total winners in all categories?**  
   - `max_decade_usa`: `2000`

3. **Which decade and category combination had the highest proportion of female laureates?**  
   - `max_female_dict`: `{2020: 'Literature'}`

4. **Who was the first woman to receive a Nobel Prize, and in what category?**  
   - `first_woman_name`: `'Marie Curie, née Sklodowska'`  
   - `first_woman_category`: `'Physics'`

5. **Which individuals or organizations have won more than one Nobel Prize?**  
   - `repeat_list`:  
     ```python
     [
       'Comité international de la Croix Rouge (International Committee of the Red Cross)',
       'Frederick Sanger',
       'John Bardeen',
       'Linus Carl Pauling',
       'Marie Curie, née Sklodowska',
       'Office of the United Nations High Commissioner for Refugees (UNHCR)'
     ]
     ```

---

## 🧰 Tools & Libraries

This project was built using the following tools:

- Python 3.x  
- pandas  
- numpy  
- seaborn  
- matplotlib

---

## 📁 Dataset
📌 This project is based on project work completed during the DataCamp Certificate. It was adapted, extended, and presented for portfolio purposes.
The dataset used is located at:

```bash
/data/nobel.csv
