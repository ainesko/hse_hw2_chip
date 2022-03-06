# hse_hw2_chip

Ссылка на Colab: https://colab.research.google.com/drive/1bptiNNcdIcWCRQCvs_TGoVR0_EtYiZTe?usp=sharing

Работа с файлами ENCFF000VDP, ENCFF000VDN, ENCFF000VEK

# FastQC 

***ENCFF000VDP***

<img width="520" alt="image" src="https://user-images.githubusercontent.com/93263861/156945727-b703cd5d-8d0e-4e32-b350-b0b913a3965f.png">

<img width="854" alt="image" src="https://user-images.githubusercontent.com/93263861/156945770-d77583be-7c8a-4051-a1b4-0b5826e564aa.png">

<img width="864" alt="image" src="https://user-images.githubusercontent.com/93263861/156945779-a3b6f9fb-1414-4335-bcd5-c5555cc745fa.png">

<img width="869" alt="image" src="https://user-images.githubusercontent.com/93263861/156945795-3e59ebb8-507f-4d01-8b83-01872023af94.png">

<img width="860" alt="image" src="https://user-images.githubusercontent.com/93263861/156945848-f702d195-bda6-49cd-b292-1f302035fee1.png">

<img width="862" alt="image" src="https://user-images.githubusercontent.com/93263861/156945861-d41d90fd-1aca-4ae6-83ed-87b6f88b9f6d.png">



***ENCFF000VDN***

<img width="523" alt="image" src="https://user-images.githubusercontent.com/93263861/156945885-f837fd46-f259-4b7e-8fc7-ea954ef281dc.png">

<img width="849" alt="image" src="https://user-images.githubusercontent.com/93263861/156945876-d5234030-9b64-4fd4-8f98-7448b26dfdd1.png">

<img width="865" alt="image" src="https://user-images.githubusercontent.com/93263861/156945898-55629a92-243f-4bf3-b1fe-659f7090149c.png">

<img width="860" alt="image" src="https://user-images.githubusercontent.com/93263861/156945904-d44f98e4-8f1f-468f-bec5-ed2299857e01.png">

<img width="857" alt="image" src="https://user-images.githubusercontent.com/93263861/156945917-25268fa0-8bae-4061-a20e-3054dba9af28.png">

<img width="853" alt="image" src="https://user-images.githubusercontent.com/93263861/156945923-8b50636d-37f0-4e16-9a30-df85375e5e73.png">



***ENCFF000VEK***

<img width="534" alt="image" src="https://user-images.githubusercontent.com/93263861/156945940-396edb2f-5d04-4d4e-bba2-c8695d4fbb15.png">

<img width="854" alt="image" src="https://user-images.githubusercontent.com/93263861/156945957-a0d7db4d-9c8a-4da5-a57d-f4c65ef3fa08.png">

<img width="852" alt="image" src="https://user-images.githubusercontent.com/93263861/156945965-9c259319-52c4-461f-8587-7b7c893e7c62.png">

<img width="851" alt="image" src="https://user-images.githubusercontent.com/93263861/156945983-6a9f469a-2669-4325-86d2-f69edfb22a67.png">

<img width="880" alt="image" src="https://user-images.githubusercontent.com/93263861/156945998-9d300d5a-aa69-42ba-8932-9718e84fa3d7.png">

<img width="854" alt="image" src="https://user-images.githubusercontent.com/93263861/156946013-f1bf10b8-c628-4873-a526-0042272aa145.png">



# Таблица со статистикой

<img width="1028" alt="image" src="https://user-images.githubusercontent.com/93263861/156946575-6cff1768-bed8-46ea-848e-bb5d4875bbf7.png">


# Диаграммы Венна

Пересечение пиков 1 реплики с пиками ENCODE

<img width="497" alt="image" src="https://user-images.githubusercontent.com/93263861/156946866-86950423-112b-4abb-a1b9-a7815cedbf6c.png">

Пересечение пиков ENCODE с пиками 1 реплики

<img width="498" alt="image" src="https://user-images.githubusercontent.com/93263861/156946781-248fc871-e864-4ad1-b0bc-9448e38c709a.png">

Пересечение пиков 2 реплики с пиками ENCODE

<img width="498" alt="image" src="https://user-images.githubusercontent.com/93263861/156946899-7ba89f02-84c0-4879-9db2-1cbe93c92c24.png">

Пересечение пиков ENCODE с пиками 2 реплики

<img width="485" alt="image" src="https://user-images.githubusercontent.com/93263861/156946834-1049781f-b001-47b4-927a-67f8ab52f42f.png">


***Почему процент выравниваний получился именно таким?***

Мы выравнивали риды на одну хромосому, что является небольшой частью генома, поэтому процент выравниваний получился таким низким.

***Имеет смысл для дальнейшего анализа отобрать уникально картированные риды?***

Имеет смысл для дальнейшего анализа отобрать уникально картированные риды



***Как можно объяснить различия в количестве пересечений?***

Пересечений мало в связи с выравниванием только на одну хромосому. В базе данных ENCODE пики составлены для всех хромосом, поэтому их намного больше. Пересечение наших пиков с ENCODE и пересечение ENCODE с нашими пиками - это не одно и то же: пересечение устроено таким образом, что считается число участков в первом файле таких, что они имеются во втором, аналогично при другом порядке - участки второго, которые имеются в первом.



