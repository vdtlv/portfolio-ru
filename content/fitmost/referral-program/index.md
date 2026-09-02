---
title: "Обновление реферальной программы"
date: 2023-08-01T00:07:07+07:00
description: Простые изменения, которые дали +30% виральных юзеров и −30% CAC.
image: /images/fm-ref-main.png
caption:
categories:
  - fitmost
tags:
  - UX
  - Product
  - Design
  - Analytics
draft: false
---

Фитмост — сервис для записи на спортивные занятия, бьюти и wellness-процедуры за пару кликов. Сервис работает по подписной модели: одна подписка открывает доступ к более чем 3000+ локаций по всей России.

В начале 2023 года появилась гипотеза, что пробный период не приносит бизнесу ожидаемой пользы: стоимость привлечения новых пользователей росла, а конверсия в покупку подписки оставалась на месте. Кроме того, пробный период создавал возможности для фрода, а из-за высокой стоимости подписки пользователи часто обращались в поддержку после окончания бесплатного периода.

![image](/images/fm-ref-0.png)

Ситуация была далеко не идеальной, поэтому наша команда провела A/B-тестирование пробного периода. Мы узнали, что пробный период никак не влиял на конверсию: пользователи покупали подписку с одинаковым успехом независимо от того, был ли им доступен пробный период или нет.

![image](/images/fm-ref-1.png)

Ваау! Оказалось, что пробный период можно убрать и одновременно устранить связанные с ним негативные последствия. После этого мы увидели следующие изменения:
- Пользователи перестали обращаться в поддержку по поводу окончания пробного периода и начали осознанно оплачивать подписку напрямую — без использования бесплатных баллов.
- Фродеры больше не могли получать бесплатные баллы.
- Стоимость привлечения клиента (CAC) существенно снизилась, высвободив бюджет для дальнейшего распределения.

### Solution

We have several sources of new users: organic traffic, paid acquisition, and corporate clients. The last option is the referral program, which had become dull due to its monotony. The discount for the first month for a friend only benefits the friend, not the referrer, and the invite link can expire, leaving the friend without bonuses. Despite the minuses of such an implementation, analytics shows good results that can be improved.

From Amplitude and support feedback, we understood what to improve:

- Replace the invite link with a promo code, so there's no chance of losing the invitation and being left without a link.

- Increase the touchpoints between the user and the referral program.

- New conditions: give 15 points to the user for each friend who signs up for Fithmost with a discount, applied after using a personal promo code. We leave the freed-up CAC.

After the release, the conversion rate in the referral program grew by **100%+** Such a great result was achieved thanks to advertising, but the new conditions still show great results.

![image](/images/fm-ref-2.png)

To consolidate the result and let the referral program float freely, we can mention it in places where users interact most frequently, such as the class page and the success booking screen.

![image](/images/fm-ref-3.png)

This gives a plus to promo code sharing (30%), and activation rates are also growing. The new referral program has minimally changed externally, but the new conditions and touchpoints on the user's path have given a significant boost to this source of new users.
