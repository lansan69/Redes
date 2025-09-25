Steps:
1. Add router 1841
2. Add switch 2960
3. Add a pc
4. Repeat the process to have two local networks
--image--

5. Connect the interface fast ethernet 0/0 on router to the fast ethernet 0/1 on the switch.
6. Connect the interface fast ethernet 0/2 on the only fast ethernet on pc.
7. Repeat for the other local network
8. Install module WIC-2T on both your routhers
 - Click and select physical
 - Turn off the router
 - Drag the module to the space in the middle (like installing)
 - turn on again and just clic (no) and enter on the set up
9. Make a serial connection between the two routers
10. Assign IP's to the devices with labels for reference
11. Go to router and assign the IP adress
12. Turn on the port
--image--
13. Go to the computer and assign the same IP as in the router
    - click laptop
    - go to desktop
    - assign the ip adress
14. Check connectivity
    - Click on laptop
    - Go to command prompt
    - run ping <ip-adress-router>
15. Click on the letter on the top and drag it to pc and router. It shall display a successful message on the bottom right
