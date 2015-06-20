# i2c-bq27210

Code sketch to demonstrate reading the BQ27210 battery gas gauge sensor via I2C on Edison.

To run,

```bash
node main.js
```

Which will show some of the sample values that can be read from the chip over I2C.

You can compile [stress](http://people.seas.harvard.edu/~apw/stress/) on the Edison and uncomment the relevant line of this script to put the system under significant strain to watch the battery levels change.

