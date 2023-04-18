# Hello World
## Headers are fun

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```
    def mySqrt(self, x: int) -> int:
        left = 0
        right = x
        while right>=left:
            mid = (left + right)//2

            if mid*mid<=x:
                left = mid+1
            else:
                right = mid-1
        return right
```
## Tasks for today
-[ ] End GH skills
-[ ] Dive into backtest example
-[ ] Dive into from_orders
