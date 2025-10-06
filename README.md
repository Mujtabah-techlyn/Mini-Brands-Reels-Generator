Client Requirement end-to-end project

# 🎬 Mini Brands Reels Generator

The **Mini Brands Reels Generator** is a fully automated AI-driven pipeline designed to create, render, and upload short-form viral videos for niche brands. Developed with a focus on scalability and automation, this system transforms brand data into engaging YouTube content with zero manual editing.

Whether you're showcasing **sneakers**, **coffee shops**, **luxury watches**, or **fast food chains**, this tool handles everything — from **creative story generation** to **final video upload** — powered by cutting-edge AI services and automation APIs.

---

## 🚀 What This Project Does

- ✅ Automatically generates **story prompts** using OpenAI based on brand data.
- 🖼️ Uses AI to **generate imaginative images** representing the brand’s vibe.
- 🎧 Synthesizes **natural-sounding voiceovers** via Eleven Labs API.
- 🎞️ Combines assets to render engaging **short vertical videos** using Creatomate.
- 📤 Uploads final videos directly to **YouTube** with titles and descriptions.
- 📝 Tracks everything in **Google Sheets** for transparency and scalability.

--- 
## Example content

https://f002.backblazeb2.com/file/creatomate-c8xg3hsxdu/87e55c24-7811-4f02-a7ce-780008acccfc.mp4

https://f002.backblazeb2.com/file/creatomate-c8xg3hsxdu/966b509f-3bae-4339-95ae-12a7f28fc580.mp4

https://f002.backblazeb2.com/file/creatomate-c8xg3hsxdu/6e5e569f-b17f-42bb-818c-85a3e945b718.mp4

https://f002.backblazeb2.com/file/creatomate-c8xg3hsxdu/6e5e569f-b17f-42bb-818c-85a3e945b718.mp4

---

## 🔧 Tools & APIs Used

| Function               | Technology / Service           |
|------------------------|-------------------------------|
| Script Generation      | OpenAI API (ChatGPT model)     |
| Voiceover              | Eleven Labs API                |
| Image Generation       | QueueTask API                  |
| Video Rendering        | Creatomate API                 |
| Data Management        | Google Sheets, Google Drive    |
| Publishing             | YouTube Data API               |
| (Optional) Distribution| TikTok, Instagram API          |

---

## 🧠 Use Cases

- 👟 Mini brand marketing (sneakers, coffee shops, fashion, etc.)
- 📈 Daily YouTube automation for content creators
- 🎯 Scalable UGC-style video creation for digital agencies
- 📲 Multi-platform short-form content generation

---

## 📁 Project Structure

mini-brands-reels-generator/
├── assets/ # Static images, logo templates
├── scripts/ # Individual Python scripts for each step
├── config/ # API key management (.env files)
├── data/ # Brand data source (CSV / Sheets)
├── main.py # Orchestrates the entire automation
├── requirements.txt # Project dependencies
└── README.md # Documentation


---

## ⚙️ How It Works (Workflow)

1. **Input brand data** into Google Sheets (or CSV).
2. **OpenAI** generates personalized brand stories.
3. **QueueTask** generates high-quality brand visuals.
4. **ElevenLabs** creates voiceovers or soundscapes.
5. **Creatomate** renders the final video using dynamic templates.
6. **YouTube API** uploads the video and updates progress logs.

---

## 💻 Who This Is For

- Content creators looking to **automate YouTube Shorts**
- Marketing agencies that manage **multiple brand profiles**
- AI and automation enthusiasts interested in building **end-to-end media pipelines**

---

## 📌 Status

✅ Version 1 in development  
🛠️ Modular scripts being created step by step  
📢 Full demo & deployment guide coming soon

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgment

Inspired by a system created by **Mujtabah Asam**.

