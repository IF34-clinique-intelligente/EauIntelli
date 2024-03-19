# clinique intelligent

## Introduction

Ce projet vise à utiliser la technologie IoT pour créer une clinique intelligente sans personnel, desservant les zones reculées où les ressources médicales sont rares. En permettant aux patients de s'auto-diagnostiquer et en fournissant une assistance médicale à distance, nous simplifions et rendons plus intelligent le processus médical.

Membres: Jiashun Chen/Shilun Xu/Zezhong Wang/Zhifan Lin

**Partage de documents**: [lien](https://docs.google.com/document/d/1ZcildPnoJ99VDRN4thcEPjKXmgYHPFyIxWTUTX1hytU/edit)

## Objectifs

- Améliorer la qualité des services médicaux dans les régions reculées, réduire les coûts médicaux et améliorer l'expérience des patients.
- Réaliser des consultations immédiates pour réduire le temps d'attente des patients et éviter le gaspillage des ressources médicales.

## Fonctionnalités

1. Consultation en libre-service pour les patients
   Sur place, les patients sont guidés par des caméras et des capteurs pour utiliser des appareils faciles à utiliser tels que les tensiomètres, les moniteurs de fréquence cardiaque, et effectuer des tests sanguins et d'autres procédures courantes.
   2.Collecte et analyse des données
   Les données des patients sont transférées vers le cloud via les appareils IoT de la clinique pour le stockage et l'analyse. Si possible, les données peuvent être combinées avec celles provenant d'autres appareils portables que les patients utilisent au quotidien, permettant aux professionnels de la santé de prédire les maladies, d'analyser les tendances et de concevoir des plans de traitement personnalisés.
2. Diagnostic et traitement à distance
   Des consultations médicales à distance sont réalisées via des appels vidéo entre les médecins et les patients.
3. Fonctionnalité de chirurgie à distance
   Les médecins experts réalisent des interventions chirurgicales simples telles que l'appendicectomie, la résection de polypes intestinaux, à distance, en aidant les médecins locaux à mener à bien les procédures chirurgicales à l'aide d'un bras mécanique.
4. Gestion intelligente des médicaments
   Un service d'auto-distribution de médicaments est proposé aux patients, avec des rappels automatiques et des fonctions de commande automatique via une application mobile.
5. Surveillance et désinfection des équipements médicaux
   Surveillance des dommages aux équipements médicaux et désinfection automatique de l'environnement de la clinique grâce à un système de ventilation et à des dispositifs de stérilisation par rayonnement ultraviolet.

## Avantages

- La détection et le diagnostic à distance permettent de pallier le manque de ressources médicales dans les régions périphériques.
- Consultations immédiates réduisant le temps d'attente des patients pour les consultations médicales.
- Les patients réalisent eux-mêmes les étapes de diagnostic préliminaire, ce qui améliore l'efficacité de la clinique.

## Utilisation

### Exigences matérielles

- Équipement médical x 10 : tensiomètres, moniteurs de fréquence cardiaque, thermomètres auriculaires, etc. (avec module de transmission de données IoT)
- Caméra haute définition (avec bras mécanique mobile) x 1 : pour les consultations médicales
- Caméra de surveillance x 3 : installée dans chaque pièce pour aider au processus de consultation des patients
- Caméra x 4, bras mécanique x 1 : pour le diagnostic et la chirurgie à distance
- Smartphone et montre intelligente : pour la collecte et la gestion des données des patients

### Exigences logicielles

- Logiciel de gestion des données médicales
- Logiciel de visioconférence
- Application de gestion des médicaments pour les patients

### Protocoles de communication

- Zigbee : pour les dispositifs de transmission de données légères tels que les tensiomètres et les thermomètres
- WiFi : pour le transfert de données en grande quantité telles que les scans CT et les rapports sanguins
- 5G : pour les appels vidéo à distance

# 智能诊所

## 介绍

项目旨在利用 IoT 技术实现一个智能无人诊所，服务于偏远地区的医疗资源匮乏的情况。通过患者自助就诊和远程医生协助，实现医疗流程的简化和智能化。

**成员**: Jiashun Chen/Shilun Xu/Zezhong Wang/Zhifan Lin

**分享文档**: [lien](https://docs.google.com/document/d/1ZcildPnoJ99VDRN4thcEPjKXmgYHPFyIxWTUTX1hytU/edit)

## 目标

- 改善偏远地区医疗服务水平，降低医疗费用，提高患者就医体验。
- 实现即到即诊，减少患者等待时间和医疗资源浪费。

## 功能

1. **患者自助就诊**
   现场通过设备上的摄像头和传感器来指导患者使用心率仪, 血压仪等易操作设备以及完成血液检测等常规操作.
2. **数据收集和分析**
   通过诊所内 IoT 设备的联网功能将患者数据传输的云端存储和分析. 如果可能的话, 可以结合患者平时运动手表等数据. 医疗人员可以利用这些数据进行疾病预测、趋势分析和个性化治疗方案的制定
3. **远程诊断和治疗**
   通过视频通话实现远程医生与患者的诊疗沟通.
4. **远程手术功能**
   通过手术机械臂, 由医生专家远程完成如阑尾切除, 息肉切除手术等简单手术. 辅助当地医生完成手术过程.
5. **智能药品管理**
   提供自助取药服务，并通过手机 APP 进行药物管理和提醒。
6. **医疗设备监测和消毒**
   监测医疗设备损坏情况，并实现诊所环境的自动消毒。

## 优势

- 远程检测和诊断, 解决边缘地区医护资源匮乏的问题
- 即到即诊, 减少患者医疗预约等待时间
- 患者自助完成前期常规检测流程, 挺高诊所效率

## 使用

### 硬件要求

- 医疗器械 x 10: 血压仪、心率仪、耳蜗温度计等（配备联网模块）
- 高清摄像头(配有可移动的机械臂) x1: 用于医生问诊
- 监控摄像头 x3: 各个房间配置, 用于辅助用户就诊流程
- 摄像头 x4, 机械臂 x1: 用于远程诊断和手术
- 智能手机和手表: 用于患者数据收集和管理

诊所方面: 医疗器械(如血压仪, 心率仪, 耳蜗温度计, 血常规设备等配有联网数据传输模块的设备) X 10, 高清摄像头(配有可移动的机械臂) x 1, 高清摄像头 x 3(各个房间配置), 机械手术臂 x 1

患者方面: 智能手机 x 1, 智能手表(可选)

### 软件要求

- 医疗数据管理软件
- 视频通话软件
- 患者药物管理 APP

### 通信协议

- **Zigbee**: 血压仪, 温度计等少量数据传输装置
- **WiFi**: CT, 血常规报告等图片大量数据传输
- **5G**: 远程视频通话
