# script-money

1. *微信名或昵称：* whichlee
2. *discord的ID：* whichlee#0483
3. *擅长的建设领域、语言或工具、熟练度：*  8年java后端开发经验，熟练掌握java/scala等常用后端语言。
4. *每周能花在业余项目的时间：* 8小时左右
5. *区块链建设经验（产品、项目、黑客松、技术文章、代码贡献、艺术创作等）：* 通过buildspace学习web3开发;使用dune.xyz进行链上数据分析。
6. *用任意编程语言计算以下公式*
   ![](https://latex.codecogs.com/svg.image?\sum_{n=1}^{100}\left&space;(n^{3}-\sqrt[3]{n}&space;\right&space;))

```java#
import java.util.stream.IntStream;

public class Test {
    public static void main(String[] args) {
        Double sum = IntStream.range(0, 100).mapToDouble(i -> Math.pow(i + 1, 3) - Math.cbrt(i + 1)).sum();
        System.out.println(sum);
    }
}
```
