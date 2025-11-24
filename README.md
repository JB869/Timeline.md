gantt
    title Project Timeline
    dateFormat  YYYY-MM-DD
    axisFormat  %W

    section Preparation
    Site Survey (1 Day)           :a1, 2025-12-01, 1d
    Pre-Requisites (1 Week)       :a2, after a1, 1w

    section Implementation
    Installation (1 Day)          :b1, after a2, 1d

    section Analysis
    Data Gathering (3 Weeks)      :c1, after b1, 3w
    Review and Report (1 Week)    :c2, after c1, 1w

    section Improvement
    Optimisation (4 Weeks)        :d1, after c2, 4w
    Energy Efficiency Review (1 Week) :d2, after d1, 1w
