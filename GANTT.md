```mermaid
gantt
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    section 3D printing
test mercury: HG, 2026-05-12, 7d
   tongadem        :a1, 2026-05-12, 2d
    Sensors     :after a1  , 20d
    section Sensors
    Order Parts :done, order, 2026-05-11, 1d
    Task in sec      :2026-05-12  , 12d
    another task       : 24d
