# 🌐 All-in-One API — Only $3/month

🔥 The most affordable and powerful API for all your AI needs. Unlock the full potential of LLMs, Text-to-Image, Image-to-Image, and TTS — all in one place, for just **$3**!

➡️ **Now also available on [RapidAPI](https://rapidapi.com/FreeCode911/api/flux-api-4-custom-models-100-style)**

---

## 🚀 Features

### 🧠 LLM (Chat & Completion)
- Supports `gpt-4`, `gpt-3.5`, and custom models
- Chat or prompt-completion format
- Streamed or full response options

### 🎨 Text to Image
- Generate stunning images from text prompts
- Support for aspect ratios, styles, quality settings
- Fast, high-resolution outputs

### 🖼️ Image to Image
- Modify or enhance existing images
- Great for upscaling, style transfer, or edits

### 🗣️ Text to Speech (TTS)
- Lifelike voices for multiple languages
- Supports pitch, speed, and emotion customization
- Over 30+ voices available (English, Hindi, French, etc.)

### 🌍 AI Translation
- Translate text between 100+ languages
- Powered by large multilingual AI models
- Fast, reliable, and perfect for global applications

---

## 💰 Pricing

> **💸 Just $3/month** — No limits, No BS  
> Perfect for developers, creators, hobbyists, and businesses.

---

## 📡 API Endpoints Overview

| Feature          | Method | Endpoint                    |
|------------------|--------|-----------------------------|
| LLM Chat         | POST   | `/v1/chat/completions`      |
| Text to Image    | POST   | `/v1/generate/image`        |
| Image to Image   | POST   | `/v1/modify/image`          |
| Text to Speech   | POST   | `/v1/tts`                   |
| AI Translate      | POST   | `/v1/translate`             |

> 🔐 All endpoints require an `Authorization` token header.

---

## 🛠️ Quick Start

### 🔑 Get API Key
Visit: [RapidAPI](https://rapidapi.com/FreeCode911/api/flux-api-4-custom-models-100-style)

### 📦 Sample Request (LLM)

```bash
curl -X POST https://your-api-domain.com/v1/chat/completions \
-H "Authorization: Bearer YOUR_API_KEY" \
-H "Content-Type: application/json" \
-d '{
  "model": "gpt-4",
  "messages": [{"role": "user", "content": "Tell me a joke"}]
}'
```

### 🧪 Sample Request (TTS)

```bash
curl -X POST https://your-api-domain.com/v1/tts \
-H "Authorization: Bearer YOUR_API_KEY" \
-H "Content-Type: application/json" \
-d '{
  "text": "Hello world!",
  "voice": "bf_emma"
}'
```

---

## 📷 Image Output Example

| Text Prompt                     | Output Preview                     |
|--------------------------------|------------------------------------|
| *"Cyberpunk city at night"*    | ![preview](https://yourcdn.com/img1.jpg) |
| *"Fantasy warrior on dragon"*  | ![preview](https://yourcdn.com/img2.jpg) |

---

## 🙌 Why Choose Us?

✅ **Super Cheap** — Just $3  
✅ **All-in-One** — No need for multiple APIs  
✅ **Fast** — Built on top of powerful cloud infra  
✅ **Simple** — Easy-to-use REST endpoints  
✅ **Secure** — Token-authenticated & encrypted

---

## 📞 Support

Need help? Reach out on:

- Email: lykcloud@dr.com

---

## 🧠 Built With

- Node.js + Express / Deno
- Hosted on: Deno

---

## 🥂 Let's Build the Future Together

> Invite your friends, contribute on GitHub, and power your next big idea with AI — affordably.

**⭐ Star this repo if you love it!**
