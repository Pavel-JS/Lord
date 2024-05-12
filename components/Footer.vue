<template>
  <div class="OpenAccount">
    <div class="OpenAccount_text">Откройте свой счет сегодня</div>
    <div class="OpenAccount__steps">
      <div class="OpenAccount__steps__step1">
        <div class="number">1</div>
        <div class="text1">Зарегистроватся</div>
        <div class="text2">Заполните форму и пройдите верификацию</div>
      </div>
      <div class="OpenAccount__steps__step2">
        <div class="number">2</div>
        <div class="text1">Пополнить счет</div>
        <div class="text2">Внесите деньги или криптовалюту на свой счет</div>
      </div>
      <div class="OpenAccount__steps__step3">
        <div class="number">3</div>
        <div class="text1">Начать торговать</div>
        <div class="text2">
          Загрузите нашу платформу, войдите в систему и начните торговать
        </div>
      </div>
    </div>
    <div class="block">
      <button class="button">Открыть счет</button>
    </div>
    <div class="contacts">
      <div class="contacts_text">
        Остались вопросы? Получите консультацию<br />
        на сайте или в удобном мессенджере
      </div>
      <div class="contacts_icon">
        <NuxtLink to=""> <img src="/public/Frame18.svg" alt="" /></NuxtLink>
      </div>
      <div class="contacts_icon">
        <NuxtLink to=""><img src="/public/Frame58.svg" alt="" /></NuxtLink>
      </div>
      <div class="contacts_icon">
        <NuxtLink to=""><img src="/public/Frame59.svg" alt="" /></NuxtLink>
      </div>
    </div>
  </div>
  <div class="Footer">
    <div class="Footer_icon">
      <img src="/public/Logo.svg" alt="" />
    </div>
    <div class="Footer__tabels">
      <div class="tabel">
        <div class="name">Торговля</div>
        <div class="link">Валюты</div>
        <div class="link">Металлы</div>
        <div class="link">Криптовалюты</div>
        <div class="link">Криптовалюты</div>
        <div class="link">Кредитные плечи</div>
        <div class="link">
          Защита от <br />
          отрицательного баланса
        </div>
      </div>
      <div class="tabel">
        <div class="name">Торговые счета</div>
        <div class="link">Стандартные счета</div>
        <div class="link">
          Профессиональные <br />
          счета
        </div>
        <div class="link">Автоматические счета</div>
        <div class="link">Демо-счета</div>
        <div class="link">Пополнение и снятие</div>
      </div>
      <div class="tabel">
        <div class="name">MetaTrader 5</div>
        <div class="link">MetaTrader 5</div>
      </div>
      <div class="tabel">
        <div class="name">Инструменты</div>
        <div class="link">Календарь праздников</div>
        <div class="link">
          Расписание торговых<br />
          сессий
        </div>
        <div class="link">Ответы на вопросы</div>
      </div>
      <div class="tabel">
        <div class="name">Партнеру</div>
        <div class="link">Партнерская программа</div>
        <div class="link">Акции</div>
      </div>
      <div class="tabel">
        <div class="name">О нас</div>
        <div class="link">О компании</div>
        <div class="link">
          Безопасность Ваших <br />
          средств
        </div>
        <div class="link">Лицензирование</div>
        <div class="link">Документы</div>
        <div class="link">Контакты</div>
      </div>
    </div>
  </div>
  <div class="info">
    <div class="text">
      Lord Prime Ltd — финансовая брокерская компания, регулируемая
      (ISA)Управлением международных финансовых услуг, лицензия № 052689-018.
    </div>
    <div class="text">
      Lord Prime Ltd зарегистрирована в юрисдикции Науру, юридический адрес
      компании: Island Ring Road, TB office, NRU68, Йерен, Науру, Республика
      Науру, регистрационный номер 00982024
    </div>
    <div class="text">
      Предупреждение о рисках: Осуществление операций на рынке Форекс позволяет
      получить прибыль, но неразрывно связано с риском получения убытков. Сделки
      с финансовыми инструментами могут привести к потере части или всех ваших
      первоначальных инвестиций. Убедитесь, что вы понимаете связанные с этим
      риски и обладаете достаточными знаниями для выполнения операций. Услуга
      недоступна для жителей США, Японии, Канады, Австралии и стран Европейской
      экономической зоны.
    </div>
  </div>
</template>

<style lang="scss">
.OpenAccount {
  margin: 0 20px 0 20px;
  &_text {
    display: flex;
    justify-content: center;
    font-size: 40px;
    font-weight: 500;
    margin-bottom: 35px;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  }
  &__steps {
    display: flex;
    margin-bottom: 35px;
    &__step1 {
      width: 40%;
      height: 280px;
      padding: 20px;
      background: #eef6ff;
    }
    &__step2 {
      width: 40%;
      height: 280px;
      padding: 20px;
      background: #c1dfff;
    }
    &__step3 {
      width: 40%;
      height: 280px;
      padding: 20px;
      background: #1563b7;
      .number {
        color: #ffff;
      }
      .text1 {
        color: #ffff;
      }
      .text2 {
        color: #ffff;
      }
    }
    .number {
      font-size: 100px;
      font-weight: 400;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
    .text1 {
      font-weight: 700;
      font-size: 20px;
      margin: 20px 0 10px 0;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
    .text2 {
      font-weight: 400;
      font-size: 20px;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
  }
  .block {
    display: flex;
    justify-content: center;
    .button {
      cursor: pointer;
      width: 225px;
      height: 40px;
      border: 0;
      color: #ffff;
      border-radius: 4px;
      font-size: 15px;
      font-weight: 600;
      background: #1563b7;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
  }
  .contacts {
    display: flex;
    margin: 50px 0 50px 0;
    align-items: center;
    justify-content: center;
    &_text {
      font-weight: 400;
      font-size: 25px;
      margin-right: 20px;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
    &_icon {
      margin-left: 20px;
    }
  }
}
.Footer {
  padding: 30px 20px 50px 20px;
  border-top: 1px solid #e9e9e9;
  border-bottom: 1px solid #e9e9e9;
  &__tabels {
    display: flex;
    margin-top: 50px;
    justify-content: space-between;
    .tabel {
      .name {
        font-weight: 500;
        font-size: 16px;
        margin-bottom: 10px;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      }
      .link {
        font-size: 16px;
        font-weight: 400;
        color: #6d6d6d;
        margin-bottom: 5px;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      }
    }
  }
}
.info {
  padding: 30px 20px 50px 20px;
  .text {
    font-size: 16px;
    font-weight: 400;
    margin-bottom: 10px;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  }
}
</style>
