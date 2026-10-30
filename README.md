# Bgmi-sensitivity-coach
AI persona prompt that suggests BGMI sensitivity settings
# BGMI Sensitivity Coach (AI Persona Prompt)

An open-source system prompt that turns any AI chatbot (Gemini, ChatGPT, Claude, etc.) into a **BGMI Tactical Analyst and Sensitivity Coach**.

Give it 4 details in a single message and it returns a full sensitivity setup, recoil advice, and a short quiz.

## What it does

- Sensitivity table (Camera, ADS, Gyro) for TPP, FPP, Red Dot, 2x, 3x, 4x, 6x, 8x
- Adapts to your control layout (2-finger or 4-finger claw)
- Adapts to your gyro mode (Non-Gyro, Semi-Gyro, Full-Gyro)
- Gun-specific recoil advice, or one universal setup for "All Guns"
- A short "0-recoil formula" explanation
- 3 MCQs at the end to test your recoil-control knowledge

## How to use

1. Open `prompt.txt` and copy the whole text.
2. Paste it into your AI tool:
   - **Gemini:** create a new Gem and paste it into the Instructions box
   - **ChatGPT:** create a Custom GPT and paste it into Instructions
   - **Claude:** create a Project and paste it into Project instructions
   - **Any chatbot:** paste it as the first message
3. Send one message with all 4 details, for example:

```
Device: Redmi Note 11
Layout: 4-Finger Claw
Gyro: Full-Gyro
Gun: M416
```

## Important disclaimer

- The values are **AI-generated suggestions** and are not guaranteed to be accurate. This repo contains only the prompt; it does not include any third-party articles or sensitivity data.
- Treat the output as a **starting point**. Test it in the Training Ground and adjust in small steps.
- Best sensitivity depends on your device, screen size, hand size, gyro habits, and playstyle.
- This project is not affiliated with or endorsed by KRAFTON or BGMI.

## Contributing

Pull requests are welcome. Ideas:

- Add real tested sensitivity data for specific devices
- Translate the prompt (Hindi, Hinglish, etc.)
- Improve the recoil advice for specific guns
- Build a small web app or Telegram bot around this prompt

## License

MIT License. See [LICENSE](LICENSE).
