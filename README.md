### Hi there š

<!--
**vagundav/vagundav** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->


Create visualization screen using webview component.

## Testing
Use Case: User can switch an home device using Vizualization. After shutting down and reopening an application have home devices corresponding value as in previous run of application.

<details>
<summary>Test 1 - Switch on Kitchen123</summary>
  
1. Open visualization-screen
2. Click on Floor 2/ Rooms
3. Switch on home device Kitchen123
4. Check in http://192.168.8.207/scada-main the state of object "asd" has current value "on"
5. There is in android device click on home button
6. There is in android device go to list of opened apps, and close the app "touchpanel"
7. There is in android device open application "touchpanel" oncemore.
8. Kitchen123 is switched on
</details>

