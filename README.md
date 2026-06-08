# References

Roblox UI / feature reference screenshots used across Garena SG Roblox publishing work.

## Naming convention

```
Reference_<Feature>_<Source>_<YYYY-MM-DD>.<ext>
```

- **Feature**: which feature card this image references (e.g. `DailyLoginReward`, `GroupRewards`, `Settings`, `PreventiveExit`)
- **Source**: the game or product the screenshot is from (e.g. `Fish`, `LaunchAPenguin`, `SlimeRNG`, `BloxStrike`)
- **YYYY-MM-DD**: date the screenshot was captured (the date this UI pattern was current)
- **ext**: `.jpg` or `.png`

### Examples

```
Reference_DailyLoginReward_7Days_Fish_2026-06-08.jpg
Reference_GroupRewards_LaunchAPenguin_2026-06-15.jpg
Reference_Settings_Sound_SlimeRNG_2026-07-02.jpg
```

### Why dated

Roblox UI patterns and meta features shift month-to-month based on what top-CCU games are running. Dating each reference turns this repo into a historical log:

- Newest references represent the current meta
- Older references become evidence of pattern lifecycles (what worked, what died, what's emerging)
- Lets us trace and defend design decisions over time, not just point at a single screenshot

## Legacy references

Files without a date suffix are pre-convention references. They remain valid for use but are treated as undated historical references. No need to batch-rename existing files unless someone has bandwidth to do so.

## Categories currently in use

Tied to the publishing hub feature cards:

- `Settings`, `FeedbackButton`, `PatchNotes`
- `DailyLoginReward`, `PlaytimeRewards`, `PreventiveExit`, `OfflineEarnings`, `JoinEventNotifyMe` / `PushNotifications`
- `Discord`, `GroupRewards`, `GroupRewardsPopUpPrompt`, `InviteRewards`
- `TitlesGameProgress`, `TitlesOther`, `Flex`
- `CreatorCode`, `Partnerships`

New categories can be added as new feature patterns emerge.


