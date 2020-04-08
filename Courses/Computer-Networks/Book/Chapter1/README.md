# Chapter1 Questions

### Section 1.1

> R1. What is the difference between a host and an end system? List several different types of end systems. Is a Web server an end system?

- �����Ͷ�ϵͳ��������һ���ġ�
- ��ϵͳ���������������������ļ�����������ֻ�����Ϸ���ȡ�
- Web ������Ҳ���ڶ�ϵͳ��

> R2. The word protocol is often used to describe diplomatic relations. How does Wikipedia describe diplomatic protocol?

`Protocol` Э�顢`diplomatic realtions` �⽻��ϵ

> https://en.wikipedia.org/wiki/Protocol_(diplomacy)
>
> In international politics, **protocol** is the etiquette of diplomacy and affairs of state. 

�ڹ��������У�Э�����⽻�͹����������ڣ���������

> R3. Why are standards important for protocols?

���˱�׼��Э�������Ч����ϵͳ���ܻ���Э���ƶ��ı�׼����ͨ�š�

### Section 1.2

> R4. List six access technologies. Classify each one as home access, enterprise access, or wide-area wireless access.

1. סլ����
   - DSL - �����û��� (Digital Subscriber Line)��ס��ͨ�����ṩ���ص绰����ı��ص绰��˾����� DSL ���������롣ʹ�õ绰�ߣ�˫��ͭ�ߣ���ͨ��Ƶ�ָ��õķ�ʽ��
   - ���£����õ���`���ߵ��ӹ�˾`���е����ߵ��ӻ�����ʩ��ʹ�ô�ͳ��ͬ����´��䵽��ͥ�С�
   - �����뻧(FTTH: Fiber To The Home)
   - ������· �� ��ͳ�ĵ绰�߲��Ž��롣
2. ��ҵ����
   - ������ (LAN) ����ϵͳ���ӵ���Ե·��������������������������
   - ��̫����ʹ��˫��ͭ����һ̨��̫��������������
   - WiFi (����802.11����������LAN����)
3. �������߽���
   - ͨ���������ṩ�̵Ļ�վ�����ͺͽ��շ��顣
   - 3G��4G��5G & LTE

> R5. Is HFC transmission rate dedicated or shared among users? Are collisions possible in a downstream HFC channel? Why or why not?

HFC��Hybrid Fiber Coax��Ϲ���ͬ������������û�����ġ�����һ����Ҫ���������ǹ���㲥ý�壬ͬʱ����ͨ��������ͨ�����ǶԳƵġ�

���й����п��ܻ������ײ����Ϊ�û������ŵ���

> R6. List the available residential access technologies in your city. For each type of access, provide the advertised downstream rate, upstream rate, and monthly price.

������Ŀ

> R7. What is the transmission rate of Ethernet LANs?

 Transmission rate���������ʣ�

��̫���Ĵ������ʿ��Դ���̫����׼�����ֻ�ã��� 10BASE-T, 100BASE-T, 1000BASE-LX �ȡ����ֵĵ�һ���־��������׼�����ʣ���Ӧ 10Mbps, 100Mbps, 1000Mbps��**���ֱ�׼������ȡ���������Ľṹ��**

> R8. What are some of the physical media that Ethernet can run over?

**��̫��������ý��**������̫���д����һ�����ش� ���������� �� ���������� ֱ�Ӿ�����·�Ρ�

������˫��ͭ�ߡ�ͬ����¡���ģ�����µȡ�

> R9. Dial-up modems, HFC, DSL and FTTH are all used for residential access. For each of these access technologies, provide a range of transmission rates and comment on whether the transmission rate is shared or dedicated.

**��Դ����**

| ����           | ����                        | ��ʽ |
| -------------- | --------------------------- | ---- |
| ���ŵ��ƽ���� | 56Kbps                      | ר�� |
| HFC            | ����42.8Mbps������30.7Mbps  | ר�� |
| DSL            | ����24Mbps������2.5Mbps     | ���� |
| FTTH           | ����10-20Mbps������2-10Mbps | ר�� |

> R10. Describe the most popular wireless Internet access technologies today. Compare and contrast them.

��������Ŀ����Ҫ���Ƿ��ѵ� 4G �� WiFi

�����豸���ӵ������������Ҫͨ����վ����վ�������ּ������в�ͬ��ʵ�ַ�ʽ��

- �������磺��վ�Ƿ����������Խ�Զ���봫����Ϣ��
- WiFi��IEEE802.11������վ�����߾������Ľ���㣨��������������·���������������Ͻ���

### Section 1.3

> R11. Suppose there is exactly one packet switch between a sending host and a receiving host. The **transmission rates** between the sending host and the switch and between the switch and the receiving host are R1 and R2, respectively. Assuming that the switch uses **store-and-forward packet switching**, what is the total end-to-end delay to send a packet of length L? **(Ignore queuing, propagation delay, and processing delay.)**

Transmission rates���������ʣ� + store-and-forward packet switching���洢ת�����鷽ʽ��

**�洢ת������**��������������ܵ��������飬���ܿ�ʼ�������·����÷���ĵ�һ�����ء�

����ľ��Ǵ���������ʱ�ļ��㷽ʽ��**ʹ���ܵĳ��� ���� ��������**��
$$
\frac{L}{R1}+\frac{L}{R2}
$$


> R12. What advantage does a **circuit-switched** network have over a **packet-switched** network? What advantages does **TDM have over FDM** in a circuit-switched network?

Circuit-switched����·�������磩�����ƣ�

- Ԥ�ȷ�����·��ʹ�ã���������·��Ԥ���˺㶨�Ĵ������ʡ����ɷž��ܹ���**ȷ��**�ĺ㶨��������շ��������ݡ�

Packet-switched�����齻���������ƣ�

- ���õĴ�����
- �ȵ�·�������Ӽ򵥡���Ч��ʵ�ֳɱ�����

**TDM��ʱ�ָ��ã�**�� **FDM��Ƶ�ָ��ã�**��

- FDM��ÿ����·�����صõ����ִ���
- TDM��ÿ����·�ڶ�ʱ���϶�����ڵصõ�ȫ������

TDM�ܸ���ֵ�ռ�ô������������û����Ͼ��и������Ե�Ч����

TDM�Ȱ���·��ʱ���Ϸָ�Ϊ֡��Ȼ����ÿ֡�л��ֳ�ʱ϶��ÿ���û���ÿ֡������һ��ʱ϶����������������Ϊ�û�������·������ÿ���û�����������ʱ϶��������������·�Ĵ���

> R13. Suppose users share a 2 Mbps link. Also suppose each user transmits continuously at 1 Mbps when transmitting, but each user transmits only 20 percent of the time. (See the discussion of statistical multiplexing in Section 1.3.)
>
> - a. When circuit switching is used, how many users can be supported?
> - b. For the remainder of this problem, suppose packet switching is used. Why will there be essentially no queuing delay before the link if two or fewer users transmit at the same time? Why will there be a queuing delay if three users transmit at the same time?
> - c. Find the probability that a given user is transmitting.
> - d. Suppose now there are three users. Find the probability that at any given time, all three users are transmitting simultaneously. Find the fraction of time during which the queue grows.

a. ��·������Ԥ��Ϊ�û��������·��һ������þͻ�Ԥ�����ⲿ�ֵĴ���һ��֧�� 2Mbps / 1Mbps = 2���û���

b. **���������û�Ϊʲô����û��ʱ�ӣ�**����ľۺϵ�������С�ڻ���ڸ���·��������ʣ�����ͨ������·�ķ���������û��ʱ�ӡ�**��Ծ�û�3����**�������ʳ�����·��������ʣ�������л�߳����Ŷ�ʱ�ӻ����ӡ�

c. 20% = 0.2

d. **����������ʱ����ʣ�**$0.2*0.2*0.2=0.008$

> R14. Why will two ISPs at the same level of the hierarchy often peer with each other? How does an IXP earn money?

- ISP(Internet Service Provider)�����������ṩ�̡�
- �������������ͬ��ISPͨ���ϼ�ISP�������紫�䣬����Ҫ����һ����ISP֧�����á���ͨ���໥�Եȣ� ����ͬ����ISP���ƹ��ϼ�ISPֱ�ӽ������紫�䣬��ʡ���á������Եȵ�ISPͨ�������н��㡣
- IXP(Internet Exchange Point)�����������㣬��һ���ṩ�Եȵĵط���ͨ��λ��һ�����Լ��Ľ������Ķ����������С��Ե�ISP��IXP�н������紫�䣬IXPͨ�����ⲿ���������н�����Ǯ��

> R15. Some content providers have created their own networks. Describe Google �� s network. What motivates content providers to create these networks?

�ȸ��п�Խȫ��Ĵ�С��һ���������ģ� �����û�Ҫ���ʵ����ݴ�����ĳ�����������У� ���ͨ������ISP����ȸ�ķ������� �����һ�ʲ�С�������ѡ� �ȸ����������ͨ��һ���鲼ȫ������绥���� ��һר����������ڹ����������� ���ƹ��߲��ISPֱ����ϵͲ��ISP�ԵȻ���IXP���������ӣ� ����������򶥲�ISP֧���ķ��ã� ͬʱ�������������ν������ͻ����˸���Ŀ��ơ� ��ע: ���ڲ����û�����ͨ������ISP���ʵ��ȸ裬 ��˹ȸ�Ҳ�붥��ISP������

### Section 1.4

> R16. Consider sending a packet from a source host to a destination host over a fixed route. List the delay components in the end-to-end delay. Which of these delays are constant and which are variable?

- ����ʱ�ӣ�**�������ײ�**��**�������鵽��δ�**����Ҫ��ʱ�䡣����ʱ��Ҳ������**�����ؼ���Ĳ������Ҫ��ʱ��**��ͨ����**΢����߸��͵�������**���������֮��·�����Ὣ�÷�������ͨ��·����B��·֮ǰ��**����**������Constant Delay.
- �Ŷ�ʱ�ӣ��ڶ����У�**��������·�ϵȴ�����**��ʱ�䡣һ���ض�������Ŷ�ʱ�ӳ���**ȡ�������ڵ���������Ŷӵȴ�����·����ķ�������**��ͨ����**���뵽΢�뼶��**������Variable Delay.
- ����ʱ�ӣ���**���з���ı���������·�����䣩����Ҫ��ʱ��**�����㹫ʽ$\frac{L}{R}$��ͨ����**���뵽΢�뼶��**������Constant Delay.
- ����ʱ�ӣ�����·����㴫������һ̨·�������õ�ʱ�䡣���㹫ʽ�Ǵ���������Դ����ٶȣ�����ý�飩$\frac{d}{s}$��ͨ����**��������**������Constant Delay.

> R17. Visit the Transmission Versus Propagation Delay applet at the companion Web site. Among the rates, propagation delay, and packet sizes available, find a combination for which the sender finishes transmitting before the first bit of the packet reaches the receiver. Find another combination for which the first bit of the packet reaches the receiver before the sender finishes transmitting.

[DuDuDuu~]

> R18. How long does it take a packet of length 1,000 bytes to **propagate** over a link of distance 2,500 km, propagation speed $2.5* 10^8$ m/s, and transmission rate 2 Mbps? More generally, how long does it take a packet of length L to propagate over a link of distance d, propagation speed s, and transmission rate R bps? Does this delay depend on packet length? Does this delay depend on transmission rate?

ע������ֻ��Ҫ**����ʱ��**
$$
\frac{2500km}{2.5*10^8 m/s} = 0.01s 
$$


> R19. Suppose Host A wants to send a large file to Host B. The path from Host A to Host B has three links, of rates R1 = 500 kbps, R2 = 2 Mbps, and R3 = 1 Mbps.
> 
> - a. Assuming no other traffic in the network, what is the throughput for the file transfer?
> - b. Suppose the file is 4 million bytes. Dividing the file size by the throughput, roughly how long will it take to transfer the file to Host B?
> - c. Repeat (a) and (b), but now with R2 reduced to 100 kbps.

a. �ļ����͵�������ȡ����**�˵���·����ƿ����·**�Ĵ������ʡ��� `500kbps`

b. ��Ҫע�� `bytes`
$$
\frac{8*4Mb }{500kbps} = 64s
$$
c. 
$$
\frac{8*4Mb }{100kbps} = 320s
$$

> R20. Suppose end system A wants to send a large file to end system B. At a very high level, describe how end system A creates packets from the file. When one of these packets arrives to a packet switch, what information in the packet does the switch use to determine the link onto which the packet is forwarded? Why is packet switching in the Internet analogous to driving from one city to another and asking directions along the way?

- ��ϵͳA���Թ̶��Ĵ�С�Ѵ��ļ����Ϊ���С�����ݿ飬Ȼ��ͨ��Э��ջ�� �Զ����µذ����ݷ�װΪ���鲢���͵����նˡ�
- ���齻�������յ������ ���ȡ**�����ײ���һ�������ֶε�ֵ**�� Ȼ���Լ���ת�����в�ѯ��ֵ�ö�Ӧת������һ����·�ϡ�
- �����Ǽݳ���һ�����е���һ������ʱ�� ����ֻ֪��Ŀ�ĵأ� ����֪������Ҫ�ߵ�·���� �����ǿ���ͨ��ѯ��·;�е���վ�����˵�֪��һ���ľ���·���� ���齻����ͬ��Ҳ��**ֻ֪������Դ��ַ��Ŀ�ĵ�ַ�� ;��Ҫ��������·������ ��·���������Ŀ�ĵظ��߷�����һ��Ҫ�ߵľ���·����**

> R21. Visit the Queuing and Loss applet at the companion Web site. What is the maximum emission rate and the minimum transmission rate? With those rates, what is the traffic intensity? Run the applet with these rates and determine how long it takes for packet loss to occur. Then repeat the experiment a second time and determine again how long it takes for packet loss to occur. Are the values different? Why or why not?

[DuDuDuu~]


### Section 1.5

> R22. List five tasks that a layer can perform. Is it possible that one (or more) of these tasks could be performed by two (or more) layers?

- һ�������ִ�е�������Ҫ֮������������װ����ı��ĶΣ����ø��ֲ������Խ��ܵ��ı��Ķν��в���飬�����ܽ����������á���������ȡ�
- �����ɵ����񣺲�����

> R23. What are the five layers in the Internet protocol stack? What are the principal responsibilities of each of these layers?

1. **Ӧ�ò㣺����Ӧ�ó������ǵ�Ӧ�ò�Э������ĵط���**Ӧ�ò�Э��ֲ��ڶ����ϵͳ�У�һ����ϵͳ�е�Ӧ�ó���ʹ��Э������һ����ϵͳ�еĽ�����Ϣ���飬������鱻��Ϊ����(message)��
2. **����㣺�������Ӧ�ó���˵�֮�䴫��Ӧ�ò㱨�ġ�**TCP / UDP Э������һ�㡣�����ķ����Ϊ���Ķ�(segment)��
3. **����㣺����㸺�����ݱ�(datagram)�����������һ̨�����ƶ�����һ̨������** IPЭ�顣
4. **��·�㣺�����������ݱ���װ����·���֡(frame)�����Ҵ��䵽��һ���ڵ㡣**������ռ��ϵ��з��𣿡�һ�����ݱ��Ĵ�������п��ܻᱻ��;��ͬ��·�ϵĲ�ͬ��·�㴦��
5. **����㣺����·��֡�е�һ���������ƶ�����һ���ڵ㡣**����Э������·��صģ�ͬʱҲ��ʵ�ʴ���ý����ء�

> R24. What is an application-layer message? A transport-layer segment? A network layer datagram? A link-layer frame?

- **Ӧ�ò㱨��**ָ������**��ϵͳ��Ӧ�ó���֮�䰴��ĳ��Э�������Ϣ����**�ķ��顣
- **����㱨�Ķ�**ָ����ͨ��TCP/UDP�������Э���Ӧ�ò㱨�Ľ��з�װ�����γɵķ��顣**������ײ���Ϣ��Ӧ�ò㱨�Ĺ���������㱨�ĶΡ�**��ӵ���Ϣ�п����ǣ�������ն�������������ʵ���Ӧ�ó��򽻸����ĵ���Ϣ�������Ϊ��Ϣ�������ý��շ��ж��ڴ�������б����еı����Ƿ�ı䣩��
- **��������ݱ�**�Ƕ�����㱨�Ķ�**��������Դ��Ŀ�Ķ�ϵͳ��ַ��������ײ���Ϣ**���з�װ������ķ��顣
- **��·��֡**�Ƕ���������ݱ�������**��·���ײ���Ϣ������һ���ڵ�ľ����ַ��**�ķ�װ��

����������**�ײ��ֶ� + ��Ч�غ��ֶ�** ������ÿһ���з����Ԫ�ء�

> R25. Which layers in the Internet protocol stack does a router process? Which layers does a link-layer switch process? Which layers does a host process?

·������������㡢��·�㡢�����

��·��������������㡢��·��

������������㡢��·�㡢����㡢����㡢Ӧ�ò�

### Section 1.6

> R26. What is the difference between a virus and a worm?

- **����**��һ��**��Ҫĳ����ʽ���û�����**����Ⱦ�û��豸�Ķ��������
- **���**��һ��**�����κ������û�����**���ܽ����豸�Ķ��������

> R27. Describe how a botnet can be created, and how it can be used for a DDoS attack.

- DDoS(Distributed Denial-of-Service) �ֲ�ʽ�ܾ����񹥻�
- **��ʬ����Ĳ���**�������������豸������һ����Ⱦ�����豸������Ⱦ���豸�ﵽһ��������ʱ�򣬾ͱ�ɿ��Թ������߲ٿصĽ�ʬ���硣
- **���������ã��ܺ������γɵģ���ʬ����**����ÿ̨������Ŀ�����ҷ������������Ŀ���������̱����

> R28. Suppose Alice and Bob are sending packets to each other over a computer network. Suppose Trudy positions herself in the network so that she can capture all the packets sent by Alice and send whatever she wants to Bob; she can also capture all the packets sent by Bob and send whatever she wants to Alice. List some of the malicious things Trudy can do from this position. 

- ���� Alice �� Bob �ĶԻ�����
- ģ�� Alice �� Bob ���ͷ�����Է� 


