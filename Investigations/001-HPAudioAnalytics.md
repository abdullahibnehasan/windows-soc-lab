# Investigation 001 - HPAudioAnalytics Service Activity

## Date

2026-08-18

## Detection Source

Microsoft Sysmon

## Event

Sysmon Event ID 1 - Process Creation

---

## 1. Initial Detection

Sysmon detected a `cmd.exe` process running with SYSTEM privileges.

**Process:**

```text
C:\Windows\System32\cmd.exe