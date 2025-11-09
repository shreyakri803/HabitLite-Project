# Project Schedule – Gantt Chart  
Version: 1.0  
Owner: Shreya  
Date: 09/11/2025

```mermaid
gantt
    title HabitLite Project Plan (3-Week Timeline)
    dateFormat  YYYY-MM-DD
    excludes weekends

    section Initiation
    Project Charter            :done, a1, 2025-11-10, 1d
    Scope Definition           :done, a2, 2025-11-11, 1d

    section Planning
    Requirements Gathering     :a3, 2025-11-12, 1d
    User Flow Mapping          :a4, after a3, 1d
    Wireframe Creation         :a5, 2025-11-14, 2d
    WBS + Schedule             :a6, 2025-11-16, 1d
    Risk Register Setup        :a7, 2025-11-17, 1d

    section Execution
    UI Development             :b1, 2025-11-18, 4d
    Habit Logic & LocalStorage :b2, after b1, 2d
    CSV Export Feature         :b3, after b2, 1d
    Weekly Summary Page        :b4, after b3, 1d

    section Testing
    Test Case Preparation      :c1, 2025-11-25, 1d
    QA & Bug Fixing            :c2, after c1, 3d

    section Release
    Beta Testing               :d1, 2025-11-29, 2d
    Final Launch               :d2, after d1, 1d

    section Closure
    Lessons Learned            :e1, 2025-12-02, 1d

