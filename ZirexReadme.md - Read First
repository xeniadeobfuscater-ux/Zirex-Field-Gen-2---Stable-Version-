# Zirex Hub — UI Library (`ZirexUi.luau`)

A sleek, monochrome interface library customized for **Zirex Hub**, featuring smooth animations, responsive layouts (top-bar & sidebar), and built-in configuration saving.

---

## Features
* **Monochrome Aesthetic:** Custom black-and-white default theme with smooth exponential transitions.
* **Dual Layouts:** Switch effortlessly between a classic top tab strip or a collapsible sidebar rail.
* **Rich Component Suite:** Buttons, Toggles, Sliders, Dropdowns (single & multi-select), Inputs, Keybinds, Color Pickers, Stats, Progress Bars, and Consoles.
* **Built-in Config System:** Auto-save, auto-load, and manage multiple profiles directly from the settings tab.
* **Global Search & Notifications:** Live multi-page element search, stacked notifications, toasts, and modal popups.

---

## Quick Start

Load `ZirexUi.luau` into your script using `loadstring`:

```lua
local ZirexUI = loadstring(game:HttpGet("https://githubusercontent.com"))()

-- Create the main window
local Window = ZirexUI:CreateWindow({
    name = "Zirex Hub",
    subtitle = "v1.0",
    sidebarLayout = false, -- Set to true for sidebar navigation
    configuration = {
        autoSave = true,
        autoLoad = true,
        fileName = "ZirexConfig",
        customFolder = "ZirexHub"
    }
})

-- Create a Tab
local MainTab = Window:CreateTab({
    name = "Main"
})

-- Add a Section
MainTab:CreateSection({
    name = "Player Controls"
})

-- Add a Toggle
MainTab:CreateToggle({
    name = "Example Toggle",
    flag = "ExampleToggle",
    value = false,
    callback = function(state)
        print("Toggle state:", state)
    end
})

-- Add a Slider
MainTab:CreateSlider({
    name = "WalkSpeed",
    flag = "WalkSpeedSlider",
    range = { 16, 200 },
    increment = 1,
    value = 16,
    suffix = "studs",
    callback = function(value)
        print("Slider value:", value)
    end
})

-- Add a Button
MainTab:CreateButton({
    name = "Send Notification",
    callback = function()
        Window:Notify({
            title = "Zirex Hub",
            content = "Everything is working smoothly!",
            duration = 4
        })
    end
})
```

---

## License & Moderation Notice

**This project is NOT stolen or unauthorized.**

* **Open-Source Compliance (MPL-2.0):** This library is a legitimate derivative work built on **Rayfield Gen2** (Copyright © 2026 Corridon Capital), which is officially distributed under the **Mozilla Public License 2.0 (MPL-2.0)**.
* **Permitted Modifications:** Under the terms of the MPL-2.0, anyone is legally permitted to copy, modify, rebrand, and redistribute the source code—provided that original copyright notices are retained and proper attribution is given.
* **Original Copyright Preserved:** All original copyright headers (`Copyright (c) 2026 Corridon Capital`) and MPL-2.0 license notices remain intact inside `ZirexUi.luau`, and full credit is openly displayed below.
* **Safe & Transparent Code:** `ZirexUi.luau` is hosted in clean, readable source form without malicious payloads, token loggers, or hidden backdoors.

---

## Credits & Attribution
* **Original Architecture:** **Rayfield Gen2** by **Corridon Capital / Sirius Software Ltd** — Licensed under [MPL-2.0](https://mozilla.org).
* **Zirex Hub Edition:** Custom monochrome theme palette, branding, and default configuration setup by **Zirex Hub**.
