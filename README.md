# PingPong Game

----
## ���� ���/��ǥ

>* �Ӻ���� ���α׷��� �ۼ��ϱ� ���� ���� ���� ȯ��, ���α׷��� �ۼ��� ���� �����Ϸ� ����, LCD�� ����ϱ� ���� ��°��� ���α׷��� �� ������ �� ���� Ŀ��ŧ������ ��� ����� ������ ������ ����

>* ���尡 ������ �Ǿ� ������ ������Ű�� �ٸ� ������ ȯ���� PC�� ������ �ϸ� ���� ������ ��� �� �ִ�.


----
## ���� ���� �� ����

>* ������ ȯ�濡�� Client �������Ϸ� Board�� ������ ������ �� �ִ�. 

>* Ŭ���̾�Ʈ�� ó���� Insert Coinȭ�� â���� 1 Ȥ�� 2 Ű�� �Է��Ͽ� �ϳ��� �÷��̾� ��ȣ�� ���� �� �� �ְ� �� ���� �÷��̾ ���� 1, 2Ű�� �Է��� ��� ������ �Ǹ� 2���� ������ ���۵ȴ�. �� �� �÷��̾���� ������ Bar�� wŰ�� sŰ�� ��, �Ʒ� ������ �Ͽ� ������� ���� ���� ���� ������ ���� ���� ������ ȹ���Ѵ�. ��ܿ� ������ ǥ��ȴ�.

>* ������ Ŭ���̾�Ʈ�κ��� ���� ���� ���η� ������ ������ �� �ְ� w, s������ Bar�� ��ǥ�� ����, ������ش�.

>![���� ����](/image/concept.png)

----
## ���� ����

>* ũ�ν� �����Ϸ��� ��ġ�Ͽ� ���忡 ���α׷��� �ø� �� �ְ� �Ѵ�.

>* ������ Thread�� �� �� ����Ͽ� �ϳ��� UDP Socket ���� �� recvform()���� �����͸� �޴� ���Ҹ� �ϰ�, �ٸ� �ϳ��� ���� �����ͷ� ��¸� ���ִ� ����� �Ѵ�. ���� �׸��� �̿� ���� ������ Block Diagram���� ǥ���� ���̴�.

>![���� ���̾�׷�](/image/diag1.png)

>![���� ���̾�׷�](/image/diag2.png)

>* Ŭ���̾�Ʈ�� �ϳ��� ���� �帧���� UDP Socket ���� �� sendto()�� �����͸� �����ϴ� ���Ҹ� �Ѵ�. 

>![���� ���̾�׷�](/image/diag3.png)

>* �׸� �׸��� �Լ�, ���� �׸��� �Լ��� �ۼ��Ͽ� ���� ���ӿ� �°� ��ġ�Ѵ�.

>* ���� ������� �޴� 2���� ��ǻ�Ϳ��� ���� �����͸� �����Ͽ� ������ Bar�� �����δ�.


----
## ���� ���� ����

>* ���� ��� : C

>* PC : Linux Fedora

>* Board : Marsboard RK3066 Feature

>* Protocol : UDP Socket

>* ���о� : ��ü

----
## ���� ȭ��

>![����ȭ��](/image/res1.png)

>![����ȭ��](/image/res2.png)

----
## ��Ű�� ����

>* �ҽ� : socket/client.c, ttt_test/main.c

>* �������� : client, server

>* ���� nfs �߰����� : fond/, lib/