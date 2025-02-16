Given the ever-increasing dangers lurking on the Internet, it is important to understand how to keep your data safe. This document outlines a number of precautions that will help preserve your privacy and lower the likelihood that someone will gain access to sensitive information.

# Authentication

Authentication is required when logging into a service or requesting access to any type of sensitive data. This ensures that you are who you say you are and prevents unauthorised access.

## Passwords

The most basic element of authentication is a password. It is something you know, which can help demonstrate that you are supposed to have access to your data.

Hackers use specialised software to guess passwords. Given enough time, any password can be guessed, which is why a few safety precautions need to be in place.

First off, a password must not contain any information connected to you personally. Hackers will do research on their targets before they attempt anything. They will read through your social media and compile a list of every song you like, every film, every city you've visited, the date you were married, the birth dates of your children, names of pets, etc.

The reason is that people tend to use personal information to create passwords. This makes them easier to remember but also makes you vulnerable to this kind of attack.

Secondly, it must ideally be longer than 12 characters and contain some symbols, upper-case letters, and numbers. This makes guessing the password take a lot longer.

Thirdly, ideally a password is changed regularly. If your password gets leaked, your data is now vulnerable. Changing it every few months helps protect against this eventuality.

This may seem unnecessary, but allow me to give you some examples of common passwords and how long specialised software would take to guess them.

cat123 - Instantaneously<br>
c@t123 - Instantaneously<br>
myc@t123 - 10 minutes<br>
Myc@t12345 - 1 week<br>

A few lowercase characters and a few numbers would take less than a second to guess by the software. Adding symbols helps, but not if the password is too short.

Adding two more characters increases the time required by an order of magnitude, namely 10 minutes in the example above. Adding 2 more numbers and making one of the letters uppercase makes the time required to guess even longer, at around 1 week.

A way to create a password that is both solid and easy to remember is by creating a passphrase. This can be a short phrase comprising three or four words, with a few rules you establish beforehand that you can apply to your passphrases going forward.

For example, let's say that your phrase is "ihaveacutekitten". This passphrase is long but still easy to guess because of something called a "dictionary attack". This is when hackers use specialised software to try common words in random orders in an attempt to guess your password. The phrase above can be guessed very quickly, so let's establish some rules in order to make it more secure.

For example, let's say you decide to add a period between each word and each syllable. So, the passphrase is now "i.have.a.cute.kit.ten".

Great. Now, let's say that you also decide to capitalise each word's first letter. The passphrase now becomes "I.Have.A.Cute.Kit.ten".

Finally, let's create a rule set for replacing letters with symbols and numbers. You might be tempted to do things like replacing lower-case L with "1" and such, but hackers are already aware of this trick. You need to come up with a rule that only you know.

Let's say that we'll replace "a" and "A" with 0, and we'll replace "u" with "^". The passphrase now becomes "I.H0ve.0.C^te.Kit.ten". It would theoretically take 600 trillion years for a hacker to guess this password.

However, as per one of the rules mentioned earlier, you should not include personal information in the password. A password like this may be a good idea if you don't have a cat. However, if you have photos of "Mr. Mittens" all over your Instagram, it might be best not to include cats in your password.

Next time you have to change your password, you can come up with a different phrase and then apply the same replacement rules again. This will make the process of changing passwords far less painful.

## Password Managers

The process outlined above is ideal when creating passwords for our user accounts. However, given our number of online services, creating unique passwords for each account would be very cumbersome.

To solve this problem, one can use a password manager. A password manager stores accounts and passwords in a locked vault, which requires a master password. In this case, the only password you need to remember is that one password.

When you create an account for a new online service, the password manager can create a long and complex password for you, such as "Un7DTLiLFofBaUE3cv51rlI7Lk2rKQ3ofW". You will never have to remember this password, as the manager will do that for you.

You can retrieve the password from the application the next time you log into the account. Password managers can be installed as stand-alone apps on your computer and smartphone or as browser extensions.

For example, when you go to a website where you do have an account, if you have a password manager extension, it will automatically detect that you have an account with it. It will either auto-fill the information for you or ask if you would like the information to be auto-filled.

This not only saves time but also ensures that you have a different password for each online account.

If you reuse the same password, you probably also use the same email. When a service gets hacked, and bad actors get a hold of your password, not only that account but every other online account you have is now compromised, as they will simply try to log into many other services using the same credentials. A password manager protects you from all of that.

## 2FA

As mentioned above, a password is something you know. Any password can easily be compromised in a number of ways, which is why, over the past few years, 2FA or Two-Factor Authentication has become more prevalent.

2FA introduces a second element to the authentication process, making it more secure. This can be something you have, like an OTP code or a hardware key, or even who you are, like your fingerprint, face, or retina.

### OTP

An OTP is a one-time password that is generated anew every 30 seconds. It can be sent to you via SMS or generated by an application that you have installed on your computer or phone.

It works by taking a secret, usually in the form of a QR code, that you are given when you make a new account and creating a unique code using the current time.

Recently, companies have been moving away from sending codes over SMS, as those can be easily compromised. An attacker can call your phone company, impersonate you, and say that they lost their phone.

The company would then transfer your phone number onto a SIM that the hacker has. Once the process is complete, the hacker will now intercept all of your text messages, including any OTP codes you may receive.

### Hardware Keys

The next step up from generating OTP codes on your phone is having a hardware key. The most common type is a Yubikey. These keys store the secret mentioned above physically inside them.

When you need to generate an OTP code, you need to use the key. You can do this by plugging the key into your computer or your phone or by using your phone's NFC capability. In most cases, this means touching the key to the top of your phone near the cameras.

This will prove that you have the key, adding another element of security to the authentication process. If you lose the key, it doesn't matter as long as you have backups of your secrets. Even if someone finds the key, they won't know which accounts the key is associated with, and even if they knew, they don't have the password.

### Biometrics

Biometrics falls into the category of "something you are". Smartphones have had biometrics for years, either in the form of a fingerprint sensor or a face scanner.

This means that biometrics are very convenient, as you do not have to remember anything, and you do not need anything other than your face or your finger.

However, biometrics can not be changed. Plus, someone can use force in order to get a user to touch a fingerprint scanner, or look at a face scanner.

# Malware

The strongest password in the world will not do much if your devices are compromised by malware, also generally referred to as "viruses." There are many types of malware, but that is outside the scope of this document.

Instead, we will cover methods for protecting your data and finances from malware.

## Antivirus

Using some form of antivirus is generally a good idea, as it can protect you from common threats. Windows has a decent antivirus built-in; however, many options exist.

## Separate Devices

Even though an antivirus can be useful, it has one flaw: It is not able to detect brand-new threats. If a new virus is created, your antivirus will generally not be able to detect it until it is captured and analysed, and then an update is sent to your antivirus.

As a result, it is advisable to have a separate device for your finances. This can either be a laptop or a smartphone, but it needs to be used only for that purpose.

As an extra step, you can even use a firewall to ensure that the machine only communicates with your bank and its manufacturer so that it can continue to receive security updates. This will minimise the chances of a bad actor getting access to your finances.

## VMs

If having a separate device is not feasible, you can increase your security by using a virtual machine (VM).

A virtual machine is like running a separate computer on your own computer. This can create some isolation between your machine and the machine on which you do your banking, adding an extra level of security. Regardless of whether you are using Windows or macOS, plenty of applications can do this.

## Backups

Malware infections are sometimes inevitable. If or when they happen, you should have a system in place to recover as quickly as possible.

The best way to do this is to have backups. There are myriad backup solutions out there, but it is generally advised to have a spare local copy of your data and at least one cloud backup as well.

You do not necessarily need to back up everything, especially as cloud storage can be expensive. You don't need to back up entire applications, just your preferences, and the actual data that you need. You can simply re-download all the applications when you re-install your operating system.

If you want to go one step further, you can make a clone of your machine after installing your OS and configuring everything just the way you like it.

In the event of a malware infection, you can then wipe your machine, restore the operating system from the cloned image, and then restore your backed-up data.

# Social Engineering

All hackers understand that the easiest way to get access to sensitive data is through people. It is a good idea to familiarise yourself with some of the concepts that will be discussed here, as it will allow you to not fall victim to what is known as "social engineering."

In short, social engineering is tricking someone into giving you access to something you should not be able to access or information that leads to the same end.

## Pretexting

This is one of the most effective forms of social engineering. Pretexting usually involves a threat actor masquerading as someone they are not to obtain information or unauthorised access.

For example, let's assume you're coming back from your lunch break. As you scan your ID card to get into the office building, you notice a woman carrying large boxes and allow her to enter. A threat actor could use your instinct to help her in order to gain physical access to the building.

Another is gaining access to a building just by wearing a high-visibility vest and claiming to need access in order to perform repairs.

The attack can sometimes involve a story and a sense of urgency. For example, a young person in a suit, clearly in a panic, can request access, claiming it's their first day, they forgot their card, and if they don't get in, they'll be fired.

Whilst all of the examples above might be legitimate, you should always stop and think for a second whenever access is involved. A good story and a sense of urgency are fantastic ways to gain unauthorised access.

## Phishing

Pronounced "fishing," phishing is a way to get you to click on a link or download a program, usually masked as something else, in order to steal data or gain access.

For example, you might receive an email from your bank telling you that you need to log in immediately and confirm some information; otherwise, your account will be closed.

The intent of this email is to get you to click on a link, which might take you to a carbon copy of your banking website. You type in all of your information to log in, but the website belongs to the attacker, who now has all your login credentials.

Another example might be an email from the police stating that you are under investigation for a crime and that you should download a program to contact them and explain yourself.

Emails like these can be scary. If you ever read an email that triggers an emotional response, you should always pause for a second. Does the email appear legitimate? What is the email of the sender? Are there any grammatical errors in the email? Would the police actually contact you via email if they were investigating you?

Whenever something seems suspicious, you should always stop for a second and think.

# Conclusion

You do not need to implement all of the above. Being aware of the dangers of malware and social engineering and implementing a handful of authentication security measures will get you well on your way to being safer online.
