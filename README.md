# Pastry Simulator

A [FreePastry](https://www.freepastry.org) implementation. It's a basic chat app.

## How to run

1. Generate .jar

2. Open the CLI and go to /dist location

```shell
  cd /dist
```

3. Run the following command

```shell
  java -jar "PastrySimulator.jar" 9000 [your local IP] 9000
```

4. (Optional) Open another CLI and run the following command, you can repeat this step as many times as you want (for i=1)

```shell
  java -jar "PastrySimulator.jar" 9000+i [your local IP] 9000
```

5. Now, you can send messages

![Chat - Demo](./.github/chat.png)
