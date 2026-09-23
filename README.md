# JavaCICDDemo

Demo CI/CD cho bai thuyet trinh: **GitHub Actions tu dong chay unit test moi khi push code**.

![CI](https://github.com/nguyenvoii/JavaCICDDemo/actions/workflows/ci.yml/badge.svg)

## Cau truc

- `src/javacicddemo/Calculator.java` - code chinh
- `test/javacicddemo/CalculatorTest.java` - unit test (JUnit 4)
- `.github/workflows/ci.yml` - pipeline: moi push / Pull Request -> chay `ant test` tren may ao Ubuntu
- `lib/` - JUnit 4.13.2 + Hamcrest (project tu chua, build duoc o moi may)

## Chay test o may local

```
ant clean test
```

> Sau khi tao repo: thay `TEN_TAI_KHOAN` trong link badge tren bang username GitHub cua ban.
