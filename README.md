name : n v mohana krishna
reg :212224100039

# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:
```
Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/5aea7a87-35c4-4b25-9cce-c93c16d44338)


![image](https://github.com/user-attachments/assets/4c5a99b2-9585-43e1-8223-b78aa2c09e15)


## Finding IP address:

```
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

```

## OUTPUT:


![image](https://github.com/user-attachments/assets/fed51f82-5fe2-440e-8195-4746c0592c2c)


## Finding Hosting Company


```


get further detail by using ip2location.com website.

```
## Output:


![image](https://github.com/user-attachments/assets/c1ea8588-a52b-457b-a9c0-f47f13813ade)



![image](https://github.com/user-attachments/assets/12728b2b-7c8a-4b45-a855-a6d8d7e8c92a)


## History of the website:

```
https://web.archive.org/


```


## Output


![image](https://github.com/user-attachments/assets/18b2a85a-410a-4e26-9455-7d53ebcce805)


![image](https://github.com/user-attachments/assets/7e3853cc-1dd0-422e-97e9-8fbbe5d0b1bd)


![image](https://github.com/user-attachments/assets/c570d942-594a-45ec-ada5-4f260c19c489)


## Netcat:

```
sudo apt ndtv.com 80

```

## Output:

![image](https://github.com/user-attachments/assets/c4931f93-6a55-435b-bf9a-86653c61dfa6)


## nmap:

```
nmap -p -sV --script=banner youtube.com

```
## Output:


![image](https://github.com/user-attachments/assets/9567d2c5-1251-4f28-a06d-97cadc667db8)


## Whatweb

```
whatweb youtube.com

```

## Output:


![image](https://github.com/user-attachments/assets/616f61f5-3f18-44d5-ba4e-0e09d6b7fca6)



![image](https://github.com/user-attachments/assets/9c55ef0b-26cd-4748-a447-630c5cd7a8db)


![image](https://github.com/user-attachments/assets/2fdc96ac-ad73-47c7-b947-b6b21fc1a68d)


![image](https://github.com/user-attachments/assets/0c143605-2de8-4271-aa7a-e04741c28686)


## Tracing the Location

TCP Traceroute:

```
sudo traceroute -T www.google.com

```
## Output:

![image](https://github.com/user-attachments/assets/e2952636-ecdf-4073-8238-0e719973d68c)



## UDP Traceroute:

```


sudo traceroute -U www.google.com

```


## Output


![image](https://github.com/user-attachments/assets/11160de8-bd68-46b7-b8f8-11f764d98192)


## ICMP Traceroute:

```


sudo traceroute  www.google.com

```

## Output:



![image](https://github.com/user-attachments/assets/d4b01515-e5d9-47c8-aeb0-37c0c36abf0b)



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
