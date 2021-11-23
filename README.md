### Hi there 👋

<!--
**vagundav/vagundav** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


Create visualization screen using webview component.

**Testing**
**Use Case 1: User can switch on home device using Vizualization. After shutting down and reopening an application have home devices corresponding value as in previous run of application**.

<details>
<summary>Test on/off button</summary>

- 1. Open visualization-screen
- 2. Click on Floor 2/ Rooms
- 3. Switch on Kitchen123
- 4. Check in http://192.168.8.207/scada-main the state of object "asd" has current value "on"
- 5. There is in android device click on home button
- 6. There is in android device go to list of opened apps, and close the app "touchpanel"
- 7. There is in android device open app "touchpanel" oncemore.
- 8. Kitchen123
</details>

- [ ] passed
