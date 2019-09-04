# Purpose
Take note of IPv6 on AWS

# Table of Content

# AWS VPCでIPv6を使う  
[AWS VPCでIPv6を使う 2019-07-29](https://qiita.com/skubota/items/89e0c1addd52c6809134)  

## VPC の作成  
![alt tag](https://camo.qiitausercontent.com/7e6b814c15468f7205f27ff53318b1356949bdc8/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e61702d6e6f727468656173742d312e616d617a6f6e6177732e636f6d2f302f35353837392f61666464383036612d393639322d663537372d303961362d6437313333393561333835322e706e67)

## IPv6 CIDRブロックの指定  
![alt tag](https://camo.qiitausercontent.com/890cf963aaac93222e88835441cf9267e0b5329e/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e61702d6e6f727468656173742d312e616d617a6f6e6177732e636f6d2f302f35353837392f65323231376335342d643662312d643532612d646164632d3338343639633236373634312e706e67)

## VPC 完成  
/56が割当完了  
![alt tag](https://camo.qiitausercontent.com/7b8e386b3fe358ebc6c263f32301ba57868b20be/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e61702d6e6f727468656173742d312e616d617a6f6e6177732e636f6d2f302f35353837392f65343034363265302d633133642d353064392d323366352d3835636333646538313331322e706e67)

## サブネットの作成  
![alt tag](https://camo.qiitausercontent.com/a955c38ccfba8933e7d85c0cd8a361440b0c2893/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e61702d6e6f727468656173742d312e616d617a6f6e6177732e636f6d2f302f35353837392f36646530363039392d316433622d623335352d613366312d3762613061383764656539312e706e67)

## アドレス割当  
IPv4同様にIPv6のサブネットの2桁(56-64bit)を指定  
![alt tag](https://camo.qiitausercontent.com/93ae3f4f206859f668f098fe3ce6e1d4eef586ab/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e61702d6e6f727468656173742d312e616d617a6f6e6177732e636f6d2f302f35353837392f66323765373038362d323465392d653265322d626431642d6231643938323334393033632e706e67)

azは必要分作成

## ec2等 作成  
* ネットワーク：作成したVPCを指定  
* サブネット：作成したサブネットを指定  

# Reference


* []()  
![alt tag]()

# h1 size

## h2 size

### h3 size

#### h4 size

##### h5 size

*strong*strong  
**strong**strong  

> quote  
> quote

- [ ] checklist1
- [x] checklist2

* 1
* 2
* 3

- 1
- 2
- 3