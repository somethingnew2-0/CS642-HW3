CS642-HW3
=========

Web Security

The ctional "Zoobar Foundation" has set up a simple Web application at zoobar.org (inside the
BoxesX VM), allowing registered users to post proles and transfer \zoobar" credits between each
other. Each registered user starts with 10 zoobars.
You will craft a series of attacks on zoobar.org that exploit vulnerabilities in the Websites design.
Each attack presents a distinct scenario with unique goals and constraints, although in some cases
you may be able to reuse parts of your code.
Although many real-world attackers do not have the source code for the Websites they are
attacking, you are one of the lucky ones: you can nd the source code under /var/zoobar/www in
the BoxesX VM.
The zoobar server is actually run locally on each of your boxes. We will run your attacks
after wiping clean our own local database of registered users (except the user named \attacker").
Of course this means that any data you have added while working on the assignment will not be
present during grading.
