# Gamer_Mindset_Analysis_Power_BI_Dashboard

As a data enthusiast, I wanted to explore how gamers interact with various elements in a game and from the time they spend to the currency they invest. So, I created a mock dataset and built an interactive Power BI dashboard to uncover meaningful insights.

📂 𝐃𝐚𝐭𝐚𝐬𝐞𝐭: Self-created mock gaming data
📅 𝐓𝐢𝐦𝐞 𝐏𝐞𝐫𝐢𝐨𝐝 𝐀𝐧𝐚𝐥𝐲𝐳𝐞𝐝: April–May 2025
⚒️ 𝐓𝐨𝐨𝐥 𝐔𝐬𝐞𝐝: Power BI,Power Query, Dax

🔍𝐊𝐞𝐲 𝐁𝐮𝐬𝐢𝐧𝐞𝐬𝐬 𝐐𝐮𝐞𝐬𝐭𝐢𝐨𝐧𝐬 𝐄𝐱𝐩𝐥𝐨𝐫𝐞𝐝:

📌 What are the daily trends in player activity?
📌 Which game mode leads to longer session durations?
📌 Which items are purchased the most, and where is the most in-game currency spent?
📌 How does player behavior change across levels?

𝐃𝐚𝐱 𝐅𝐨𝐫𝐦𝐮𝐥𝐚𝐬 :

🔵 𝐓𝐨𝐭𝐚𝐥𝐂𝐮𝐫𝐫𝐞𝐧𝐜𝐲𝐒𝐩𝐞𝐧𝐭 = SUM(mock_gaming_data[CurrencySpent])
🔵 𝐀𝐯𝐠𝐒𝐞𝐬𝐬𝐢𝐨𝐧𝐓𝐢𝐦𝐞= AVERAGE(mock_gaming_data[SessionDuration])
🔵 𝐀𝐯𝐠𝐋𝐞𝐯𝐞𝐥𝐬𝐑𝐞𝐚𝐜𝐡𝐞𝐝 = AVERAGE(mock_gaming_data[LevelReached])

𝐈𝐧𝐬𝐢𝐠𝐡𝐭𝐬 :

✅ Players spent most on 𝐀𝐯𝐭𝐚𝐫 (𝟔.𝟒𝟖𝐤) and 𝐁𝐨𝐨𝐬𝐭𝐞𝐫(𝟓.𝟖𝟖𝐤)items. It shows a strong preference for personalization and gameplay enhancement.

✅ 𝐒𝐨𝐥𝐨 and 𝐓𝐞𝐚𝐦 mode showed the 𝐡𝐢𝐠𝐡𝐞𝐬𝐭 𝐬𝐞𝐬𝐬𝐢𝐨𝐧 𝐝𝐮𝐫𝐚𝐭𝐢𝐨𝐧(𝟔𝟕𝐦𝐢𝐧𝐬)
. It shows deeper player engagement.

✅ Players spend less time as they progress to higher levels. It's possibly due to experience or game difficult patterns. 

✅ 📉 High drop off after 𝐋𝐞𝐯𝐞𝐥 𝟑 shows a need to investigate game balance or user onboarding.

✅ Nearly equal 𝐫𝐚𝐭𝐢𝐨 𝐨𝐟 𝐝𝐞𝐚𝐭𝐡𝐬 and 𝐥𝐞𝐯𝐞𝐥𝐬 𝐫𝐞𝐚𝐜𝐡𝐞𝐝. It shows a balanced gameplay mechanism.

✨ 𝐓𝐡𝐢𝐬 𝐩𝐫𝐨𝐣𝐞𝐜𝐭 𝐡𝐞𝐥𝐩𝐞𝐝 𝐦𝐞 𝐬𝐭𝐫𝐞𝐧𝐠𝐭𝐡𝐞𝐧 𝐦𝐲:

1️⃣ Data storytelling skills
2️⃣ Dashboard structuring and filtering
3️⃣ Understanding of behavioral metrics in gaming


# Dashboard:

![Image](https://github.com/user-attachments/assets/7a5c7691-097c-4532-82d7-ac07caeefefb)
