
#Electrical Requirements of Components
  # Rpi 4B
    - Voltage = 5V
    - Current = 3A
      # Benchmarks of Power Consumption
        - Idle                            0.540A (2.7 W)
        - "ab -n 100 -c 10 (uncached)"    1.010A (5.1W)
        - 400% CPU load (stress --cpu 4)  1.280A (6.4W) 

  # Rpi 3B+
    - Voltage = 5.1V
    - Current = 2.5A
      # Benchmarks of Power Consumption
        - Idle                            0.350A (1.9 W)
        - "ab -n 100 -c 10 (uncached)"    0.950A (5.0W)
        - 400% CPU load (stress --cpu 4)  0.980A (5.1W) 

  #LED-Array
    # 1 LED
      - Voltage = 3.5V
      - Current = 0.350A
    # 2 LED - in-serial
      - Voltage = 8V
      - Current = 0.350A
    # 3 LED - in-serial
      - Voltage = 10.5V
      - Current = 0.350A
    # 2 LED - in-parallel
      - Voltage = 3.5V
      - Current = 0.700A
    # 3 LED - in-parallel
      - Voltage = 3.5V
      - Current = 1.050A
