
# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To Develop a Java Program to perform static synchronization method for the below Scenario Create a Class Display with synchronized void wish method in that perform "Welcome : Message. Note :Assume Sleep as 400 ms i.e Thread.Sleep(400)
 
## ALGORITHM :
1.	1.	Start the Program.
2.	Define class `Display`:
-	a) Create a `Scanner` object `sc` for input
-	b) Define a synchronized method `wish(String str)`:
- i) Print "Welcome :: " followed by `str` (twice)
3.	End

## PROGRAM:
 ```

Program to implement a Packages using Java
Developed by: Silambarasan E
RegisterNumber:  212222040156

```

## Sourcecode.java:
```java
  class Display {

	static synchronized void wish(String name) {
		for (int i = 0; i <= 1; i++) {
			System.out.print("Welcome :: ");
			try {
				Thread.sleep(600);
			} catch (InterruptedException e) {

			}
			System.out.println(name);
		}
	}
  }
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/14e305a5-e4db-41a1-b9be-1942dc545e1b)

## RESULT:
Thus the java program for synchronization was executed successfully.
