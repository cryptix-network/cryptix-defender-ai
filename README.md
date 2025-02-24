Cryptix Defender AI v.1.0.0 Release

After experiencing firsthand how frustrating DDoS and payload attacks can be, we decided to develop a security AI that functions as an intelligent firewall. The AI utilizes TensorFlow, neural networks, and deep learning to provide the most modern AI patterns. Cryptix Defender AI is not just designed for crypto projects; it can be used on any server that has a hosting task. All connections to a server are protected, and the AI currently offers the following security defense mechanisms. It is, therefore, also useful outside of crypto-related applications and protects against attackers.

    Anti-DDoS attacks
    Anti-0 Byte attacks
    Anti-payload attacks
    Anti-UDP flood attacks
    Anti-SYN flood attacks

Additional protection mechanisms will be added as development continues, but these are already the most common and widely used by attackers.

The AI features a training mode, where it learns what normal user behavior and server load look like. In the running mode, the learned data is applied, and the AI uses the acquired knowledge to protect the server. You can freely choose whether potential attackers should be blocked temporarily or permanently banned from the server. The AI analyzes IP-based user behavior from the past 30 seconds, 2 minutes, and 10 minutes. This helps to detect both fast, aggressive attacks and longer-term passive attacks.

It is important to note that the AI needs to be trained for at least 1 hour during high-peak (high load) conditions to acquire the correct training data and become usable. Ideally, it should be trained multiple times. Also, please note that this is version 1 of the AI, and more features and analysis patterns will be added. There may still be some bugs present. Therefore, we recommend using the block mode for now, as it provides full protection.

This AI will always be free, and we hope that it can help stop annoying tyrants on the internet and assist overwhelmed server administrators in dealing with such attacks more effectively.

And of course other crypto projects can use it too. We would be happy if we could help them too.

Startarguments:

Training Modus:
cryptix-defender-ai.exe --mode train --train_time [SECONDS]

Training Example:
cryptix-defender-ai.exe --mode train --train_time 30


Running Modus:
cryptix-defender-ai.exe --mode run --ban_mode [block/ban]

Running Example:
cryptix-defender-ai.exe --mode run --ban_mode block
