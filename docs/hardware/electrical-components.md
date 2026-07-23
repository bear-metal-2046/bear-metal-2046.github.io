---
description: Information regarding various electrical components commonly used in FRC control systems.
---


# Electrical System Components

Below are several electrical system components that you may be working with on our robots.

---

## PDH

The PDH distributes power from the battery throughout the robot's electrical system. We typically use the PDH due to it's ports being easier to open, it having a native voltage display, and other features not available on the PDP.

<img src="https://cdn11.bigcommerce.com/s-t3eo8vwp22/images/stencil/1280x1280/products/602/3245/REV-11-1850-Power-Distribution-Hub-Hero-FINAL__29576.1704386743.png?c=2" alt="PDH" width="400"/>

---

## PDP

The PDP serves the same purpose as the PDH. We don't typically use the PDP on competition robots due to the fact that it lacks features available on the PDH.

<img src="https://cdn11.bigcommerce.com/s-7cuph2j78p/images/stencil/1280x1280/products/188/586/PDP__05475.1641569906.jpg?c=1" alt="PDP" width="400"/>

---

## VRM

The VRM is used to regulate voltage, specifically to components that require less power and use smaller gauge wire.

<img src="https://cdn11.bigcommerce.com/s-7cuph2j78p/images/stencil/1280x1280/products/178/587/VRM__22344.1641570374.jpg?c=1" alt="VRM" width="400"/>

---

## Five-Star

The Five-Star allows CAN to be routed to other components individually rather than in a daisy chain.

---

## Radio

The Radio allows the robot to be controlled wirelessly through the driver's station. Below is an image of the new radio that will become standard for the 2025 season.

<img src="https://frc-radio.vivid-hosting.net/~gitbook/image?url=https%3A%2F%2F4239402461-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FzaDthb1gXvbj84qIfOUE%252Fuploads%252Fxxsihiyk82pWBFoxhk1P%252FIMG_6513.jpeg%3Falt%3Dmedia%26token%3Dac0484d9-dbc6-42e1-8940-1dda140c49f3&width=300&dpr=1&quality=100&sign=cc769a20cad48a50834eae4fe6e5d9d73dc524fd2ba5d162920fc3a18ae8d8d3" alt="2025 Radio" width="400"/>

---

## RPM

The RPM is used to easily splice power into an ethernet cable, which will be used to power the radio using PoE.

<img src="https://cdn11.bigcommerce.com/s-t3eo8vwp22/images/stencil/1280x1280/products/601/3249/REV-11-1856-RadioPowerModule-Hero-FINAL__11706.1704391002.png?c=2" alt="RPM" width="400"/>

---

## CANCoder

CANCoders are used to find how much rotating mechanisms have rotated and relay that data through the CAN system. The CANCoder itself is a small PCB, but is placed in close proximity to a cylindrical magnet that rotates with the rotating mechanism (for example, in an axle) whilst the CANCoder remains static. The CANCoder uses the magnet to find rotational data.

<img src="https://cdn11.bigcommerce.com/s-7cuph2j78p/images/stencil/1280x1280/products/153/445/ccd1__25134.1674524028.jpg?c=1" alt="CANCoder" width="400"/>

---

## Main Breaker

The Main Breaker interrupts the positive wire from the battery before it goes to the PDH or PDP. The large red button will disconnect power, and pushing the lever back in will restore power. When connecting the main breaker, make sure the "aux" terminal is connected to the PDP or PDH.

<img src="https://cdn.andymark.com/product_images/120-amp-breaker/am_0282/5bd3e2f661a10d27d2433225/detail.jpg?c=1540612854" alt="Main Breaker" width="400"/>

---

## RoboRIO

The RoboRIO is the code that runs robot code. It is an extremely important part of the robot (and expensive), so please try not to break it.

<img src="https://th.bing.com/th/id/R.c8438c31a8e62e36edff0c85f10b40b6?rik=Givp77hTFUhDzA&riu=http%3a%2f%2fforums.ni.com%2flegacyfs%2fonline%2f174340_roboRIO+anaotated.png" alt="RoboRIO" width="400"/>

---

## Pigeon 2.0

The Pigeon 2.0 IMU is a gyroscope that assists the robot in knowing where it is on the field. Typically this component will be placed somewhere near the center of the robot.

<img src="https://cdn11.bigcommerce.com/s-7cuph2j78p/images/stencil/1280x1280/products/210/613/Pigeon2__35998.1641996756.1280.1280__82782.1643919663.png?c=1" alt="Pigeon 2.0" width="400"/>

---

## RSL

The RSL is a large orange light that displays the status of the robot. Solid means that the robot is powered on, but not enabled. Blinking means the robot is powered on and enabled. If the light is not on, the robot either doesn't have power or the RSL is not connected correctly.

<img src="https://cdn.shopify.com/s/files/1/2572/4044/products/855BS-N10BL5_1000x1000_4c3f870e-fd17-4edb-9ba7-97bdd9be97c6_1024x1024.jpg?v=1531257333" alt="RSL" width="400"/>

---

## CANivore

The CANivore is a CAN-to-USB adapter that allows us to create an entirely new CAN network. This allows us to split all CAN connected components in our robot into different groups. For example, in the 2024 season we had all of our mechanisms daisy chained to the RoboRIO's CAN port, and we had our swerve motors and CANCoders daisy chained to a CANivore. One of the downsides to CANivores is that we need to manually add terminating resistors to the end of daisy chained systems that use a CANivore.

<img src="https://cdn11.bigcommerce.com/s-7cuph2j78p/images/stencil/1280x1280/products/211/616/canivore_main__07095.1638900553.1280.1280__43296.1643920037.png?c=1" alt="CANivore" width="400"/>