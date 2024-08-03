# Hit Trace System
### When using the default Trace, you may lose the hit target when animation speed is too fast or FPS is unstable. Like this
![image](https://github.com/user-attachments/assets/7782ebb2-1b6e-486a-9636-2ed55850a0a6)

![image](https://github.com/user-attachments/assets/69f318e3-97cc-4a6d-85c6-605a87816186)

### Use `Hit Trace Component` can be avoid this problem 
![image](https://github.com/user-attachments/assets/03a2607b-74b7-4181-a5c9-11821e5a6017)

![image](https://github.com/user-attachments/assets/f7d552e2-a3ae-4049-b1f5-88db90204cdf)



![image](https://github.com/user-attachments/assets/0fc10161-c989-46c5-a3de-41790e08df41)

# API

## Start Trace functions
![image](https://github.com/user-attachments/assets/e6cd9782-d370-4152-bfd0-08c9f383bb15)

| Params| Description |
| ----------- | ----------- |
| `TaskName` |  `When using two-handed weapon, you can specify different TaskName to track multiple weapons.` 
| `Mesh` |  `Weapon mesh` 
| `BeginSocket` |  `Weapon Socket` 
| `EndSocket` |  `Weapon Socket` 
| `Instigator` |  `The Instigator of cause damage (e.g. weapon onwer character)` 

## Stop Trace
![image](https://github.com/user-attachments/assets/a8c27be1-f31f-4c14-ab97-5f2c6cccb482)

## When actor is hit
![image](https://github.com/user-attachments/assets/58e5d192-a5d2-42e2-b10b-4e1c1a5b8682)

| Params| Description |
| ----------- | ----------- |
| `TaskName` |  `Current TaskName.` 
| `Mesh` |  `Current Weapon mesh` 
| `Instigator` |  `Who caused this damage` 
| `Actor` |  `Traced Actor` 
| `HitResult` |  `HitResult Struct` 

# Example
#### Montage
![image](https://github.com/user-attachments/assets/825a6836-6ab1-420b-abc6-e138fef85458)
#### Blueprint (CharacterBP)
![image](https://github.com/user-attachments/assets/35bfbdff-211b-4fba-be8f-70586bf60dcf)

