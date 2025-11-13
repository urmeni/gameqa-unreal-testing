# Bug Report UE-002: Collision Physics

**Summary:** Physics object passes through floor under high velocity

**Steps to Reproduce:**
1. Create physics-enabled cube
2. Apply high downward force (>10000)
3. Observe collision behavior

**Expected Result:** Object should bounce/stop on floor collision

**Actual Result:** Object tunnels through floor geometry

**Severity:** High
**Priority:** Medium
**Environment:** UE 5.x, Windows 11

**Screenshots:** See /screenshots/physics_issue.png
