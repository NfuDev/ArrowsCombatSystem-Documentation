# Arrows Combat Plugin

**Arrows Combat** revolutionizes Unreal Engine combat development. This highly optimized, plug-and-play plugin provides a complete and customizable combat system, ideal for rapid prototyping or full-scale production in hack-and-slash, adventure, and action games. Enjoy flexibility and performance straight out of the box.

<img width="128" height="128" alt="Icon128" src="https://github.com/user-attachments/assets/2e04d47c-a493-402a-9292-b32ea810acc6" />

| UE 5.3 | UE 5.4 | UE 5.5 | UE 5.6 | UE 5.7 |
|--------|--------|--------|--------|--------|
| ✅ Supported | ✅ Supported | ✅ Supported | ✅ Supported | ✅ Supported |


- [📘 Open full documentation](https://github.com/NfuDev/ArrowsCombatSystem-Documentation/wiki)

  You can also view the plugin on **[Fab](https://www.fab.com/listings/19ba7cb7-9db4-4a09-80eb-753d76297232)**.

  ---
  # Features :

  ## Fighting style editor updates
  1- easy to use custom input buffer editor so you can define it without the need to write in text box, eliminating spelling mistakes and also forgetting what available attacks types in this style
  2- custom notifies editor , this will help editing the notifies in the montages without the need to jump from asset to asset , just keep working in the main fighting style and edit and tweak damage and stuff here.
  <img width="1907" height="971" alt="image" src="https://github.com/user-attachments/assets/1fb68d87-57f0-452c-802b-888e780c7529" />

  ## 1- Multiplayer :
  in this upcoming update we will support multiplayer.
  all combat states are well replicated , and maybe shortly after this update the GAS implementation is also going to be added.
  the GAS implementation is going to be a way to preform combos using gameplay ability system classes if you want to go all in with GAS and don't want to handle combos using
  our built-in dynamic input binders.
  
  <img width="1904" height="991" alt="image" src="https://github.com/user-attachments/assets/88a87022-1b78-4048-9a87-b3f32018285e" />
---
## 2- Visual Logger :
now the logs are way cleaner and straight forward, using the visual logger you can see how the combat is flowing and if something isn't working you can spot it right a way very easily
red bars indicates an error has happened , yellow will have warnings but this is just the flags being updated so it doesn't mean issues.

<img width="1821" height="731" alt="image" src="https://github.com/user-attachments/assets/9368ec41-b111-4ea4-83df-e3099c92ea66" />

<img width="1357" height="757" alt="image" src="https://github.com/user-attachments/assets/dff77994-b727-42ab-8ff4-295b72b6063e" />

<img width="1843" height="748" alt="image" src="https://github.com/user-attachments/assets/41ac4cd4-e19f-4189-82b5-e2b131822f70" />

## 3- Rewind Debugger : 
Similar to the Visual Logger, this feature displays all logged events alongside the recorded gameplay within the Rewind Debugger. By scrubbing the timeline to any point in the recording, you can inspect the logs, flags, and other debugging information exactly as they existed at that moment.

This provides valuable context when investigating bugs. Instead of viewing log entries in isolation, you can simultaneously observe the gameplay, including character positions, animations, interactions, and other visual events. Correlating the debug output with the actual game state makes it significantly easier to understand what each log entry represents, identify the sequence of events that led to an issue, and determine the root cause of a bug.

@upcoming updates 
new custom tracks for combat events , checking for targets and tracing and different combat flags

<img width="986" height="283" alt="image" src="https://github.com/user-attachments/assets/f2e07487-ac08-4e2d-8f28-260ed9be7bc1" />

the combat flags track shows a grid of flags telling you which one is on or if changed in previous update or didn't change ever

<img width="630" height="295" alt="image" src="https://github.com/user-attachments/assets/62a8169d-397d-438d-978e-b71296376a5a" />

combat event details page shows the visual logs and events here and if they happened in the same frame they will get stacked in the list, you can select and see the changes in the event details above

<img width="1544" height="822" alt="image" src="https://github.com/user-attachments/assets/7d0d19a0-20e0-44dc-a40a-a7df0b840f49" />

like here in the stacked events , i selected the add flag event and you can see the is attacking is on now , even though this is the same combat event data point.
it just represent all the events on that frame, so there will be no spams on the screen when many things happen

<img width="1604" height="850" alt="image" src="https://github.com/user-attachments/assets/62456c69-9c24-4399-b27e-3d8d76f8cf64" />

the checking for target track shows info about target selection and fileting process , here you can see the trace got two potential targets
and one was rejected due to failing distance check the other one was closer so it was selected as best target , this target is what going to be the motion warping target
you can set the filter policy in your combat component settings to get different behaviors , currently it is using nearest target in input direction

<img width="1912" height="795" alt="image" src="https://github.com/user-attachments/assets/a44b9886-3dda-4f77-89b0-d365aa2f9ac5" />








Copyright Arrows Interactive Systems, nightfall16@2025. All Rights Reserved.

