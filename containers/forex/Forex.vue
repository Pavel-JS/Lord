<template>
  <div class="post">
    <div class="post__icon">
      <img src="/public/Mask.svg" alt="" />
    </div>
    <div class="post__info">
      <div class="post__info__texts">
        <div class="post__info__texts_text">
          Торговля на рынке Forex с<br />
          низкими спредами и<br />
          комиссиями: 
        </div>
        <div class="post__info__texts_text2">
          Получите доступ к мировому рынку и торгуйте с самыми <br />
          популярными в мире валютными парами. Откройте торговый счет на <br />
          рынке Forex. Наслаждайтесь эксклюзивными услугами от Lord Prime 
        </div>
        <button class="post__info__texts_button">Начать зарабатывать</button>
      </div>
    </div>
  </div>
  <div class="iformation">
    <div class="iformation__info1">
      <div class="iformation__info1_icon">
        <img src="/image11.svg" alt="" />
      </div>
      <div class="iformation__info1__texts">
        <div class="iformation__info1__texts_text">Трейдинг на Forex: </div>
        <div class="iformation__info1__texts_text1">
          Валютный рынок или рынок Forex- крупнейший и самый <br />
          ликвидный финансовый рынок в мире. Торговля контрактами <br />
          CFD на разницу цен позволяет спекулировать на изменение<br />
          валютных пар, не владея активами 
        </div>
      </div>
    </div>
    <div class="iformation__info2">
      <div class="iformation__info2__texts">
        <div class="iformation__info2__texts_text">
          Торговые объёмы на Forex
        </div>
        <div class="iformation__info2__texts_text1">
          Рынок Forex является крупнейшим рынком в мире с<br />
          ежедневным оборотом торговли 7 трлн долларов. Торговля<br />
          валютными парами открывает бесконечные возможности и <br />
          перспективы 
        </div>
      </div>
      <div class="iformation__info2_icon">
        <img src="/image12.svg" alt="" />
      </div>
    </div>
  </div>
  <div class="WhyTrade">
    <div class="WhyTrade__name">
      <div class="WhyTrade__name_text">
        Почему стоит торговать на<br />
        Форекс с Lord Prime
      </div>
    </div>
    <div class="WhyTrade__line">
      <div class="WhyTrade__line__block">
        <div class="WhyTrade__line__block_icon">
          <img src="/public/speed.svg" alt="" />
        </div>
        <div class="WhyTrade__line__block_text">
          Высокая скорость исполнения  
        </div>
      </div>
      <div class="WhyTrade__line__block">
        <div class="WhyTrade__line__block_icon">
          <img src="/public/market.svg" alt="" />
        </div>
        <div class="WhyTrade__line__block_text">
          Лучшая платформа MetaTrader 5 
        </div>
      </div>
      <div class="WhyTrade__line__block">
        <div class="WhyTrade__line__block_icon">
          <img src="/public/growth.svg" alt="" />
        </div>
        <div class="WhyTrade__line__block_text">
          Минимальные спреды от 0.1 пипс 
        </div>
      </div>
    </div>
    <div class="WhyTrade__line">
      <div class="WhyTrade__line__block">
        <div class="WhyTrade__line__block_icon">
          <img src="/public/quarterly.svg" alt="" />
        </div>
        <div class="WhyTrade__line__block_text">Кредитное плечо до 1:1000 </div>
      </div>
      <div class="WhyTrade__line__block">
        <div class="WhyTrade__line__block_icon">
          <img src="/public/business.svg" alt="" />
        </div>
        <div class="WhyTrade__line__block_text">Более 40 валютных пар</div>
      </div>
      <div class="WhyTrade__line__block">
        <div class="WhyTrade__line__block_icon">
          <img src="/public/hand.svg" alt="" />
        </div>
        <div class="WhyTrade__line__block_text">Партнерская программа </div>
      </div>
    </div>
  </div>
  <div class="BlockQuestions">
    <div class="BlockQuestions_text">
      Ответы на частые <br />
      вопросы
    </div>
    <div class="BlockQuestions__Questions">
      <div class="BlockQuestions__Questions__Question">
        <div class="BlockQuestions__Questions__Question_text">
          Что такое Forex?<button class="button">
            <img src="/public/Frame.svg" alt="" />
          </button>
        </div>
      </div>

      <div class="BlockQuestions__Questions__Question">
        <div class="BlockQuestions__Questions__Question_text">
          Кто является участником валютного рынка?<button class="button">
            <img src="/public/Frame.svg" alt="" />
          </button>
        </div>
      </div>

      <div class="BlockQuestions__Questions__Question">
        <div class="BlockQuestions__Questions__Question_text">
          Кто является участником валютного рынка?<button class="button">
            <img src="/public/Frame.svg" alt="" />
          </button>
        </div>
      </div>

      <div class="BlockQuestions__Questions__Question">
        <div class="BlockQuestions__Questions__Question_text">
          Какие валютные пары являются пополярными?<button
            class="button"
            @click="toggleInfo"
          >
            <img src="/public/Frame.svg" alt="" />
          </button>
        </div>
        <div :class="`none ${isInfoOpen && 'info4'}`">
          Самыми популярными парами валютными парами являются пары связанные с
          долларами США и валютами других влиятельных стран. В этот список
          входят следующие активы: EURUSD, GBPUSD, USDJPY, USDCAD, USDCHF и
          другие 
        </div>
      </div>
    </div>
  </div>
  <div class="SaveUser">
    <div class="SaveUser_image">
      <img src="/public/image14.svg" alt="" />
    </div>
    <div class="SaveUser__block">
      <div class="SaveUser__block_text">Безопасность клиента</div>
      <div class="SaveUser__block_text1">
        Ваши средства полностью защищены, когда вы торгуете с Lord Prime. 
      </div>
      <div class="SaveUser__block__infos">
        <div class="SaveUser__block__infos__info">
          <div class="SaveUser__block__infos__info_icon">
            <img src="/public/Frame110.svg" alt="" />
          </div>
          <div class="SaveUser__block__infos__info_texts">
            <div class="SaveUser__block__infos__info_texts_text">
              Регулируемая деятельность:
            </div>
            <div class="SaveUser__block__infos__info_texts_text1">
              лицензия ISA номер 052689-018. 
            </div>
          </div>
        </div>
        <div class="SaveUser__block__infos__info">
          <div class="SaveUser__block__infos__info_icon">
            <img src="/public/Frame111.svg" alt="" />
          </div>
          <div class="SaveUser__block__infos__info_texts">
            <div class="SaveUser__block__infos__info_texts_text">
              Защита от отрицательного баланса 
            </div>
            <div class="SaveUser__block__infos__info_texts_text1">
              Надежная защита средств
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";

const isInfoOpen = ref(false);
const toggleInfo = () => {
  isInfoOpen.value = !isInfoOpen.value;
};
</script>

<style lang="scss">
.post {
  width: 100%;
  height: 526px;
  margin-bottom: 50px;
  background: #002035;
  &__icon {
    float: right;
  }
  &__info {
    display: flex;
    height: 526px;
    align-items: center;
    &__texts {
      margin-left: 30px;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      &_text {
        color: #ffff;
        font-size: 40px;
        margin-bottom: 30px;
      }
      &_text2 {
        color: #ffff;
        font-weight: 300;
        font-size: 20px;
        margin-bottom: 30px;
      }
      &_button {
        cursor: pointer;
        width: 220px;
        height: 40px;
        border: 0;
        border-radius: 4px;
        background: #1563b7;
        color: #ffff;
        font-size: 15px;
        font-weight: 600;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      }
    }
  }
}
.iformation {
  margin: 0 20px 0 20px;
  &__info1 {
    display: flex;
    align-items: center;
    margin-bottom: 50px;
    justify-content: space-between;
    &_icon {
      img {
        border-radius: 4px;
      }
    }
    &__texts {
      &_text {
        font-size: 40px;
        font-weight: 500;
        margin-bottom: 30px;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      }
      &_text1 {
        font-size: 20px;
        font-weight: 400;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      }
    }
  }

  &__info2 {
    display: flex;
    align-items: center;
    margin-bottom: 50px;
    justify-content: space-between;
    &_icon {
      img {
        border-radius: 4px;
      }
    }
    &__texts {
      &_text {
        font-size: 40px;
        font-weight: 500;
        margin-bottom: 30px;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      }
      &_text1 {
        font-size: 20px;
        font-weight: 400;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      }
    }
  }
}
.WhyTrade {
  margin-bottom: 50px;
  padding: 40px 30px 30px 30px;
  &__name {
    display: flex;
    justify-content: center;
    &_text {
      text-align: center;
      font-size: 40px;
      font-weight: 500;
      margin-bottom: 30px;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
  }
  &__line {
    display: flex;
    &__block {
      display: flex;
      width: 40%;
      height: 250px;
      border: 1px solid #e0e0e0;
      border-radius: 4px;
      margin: 10px 10px 0 0;
      flex-direction: column;
      justify-content: space-around;
      align-items: center;
      &_text {
        font-size: 18px;
        font-weight: 500;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      }
    }
    :last-child {
      margin: 10px 0 0 0;
    }
  }
}
.BlockQuestions {
  display: flex;
  margin-bottom: 50px;

  padding: 0px 20px 0px 20px;
  justify-content: space-between;
  &_text {
    font-size: 40px;
    font-weight: 500;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  }
  &__Questions {
    width: 60%;
    &__Question {
      margin-top: 10px;
      border-bottom: 1px solid #e9e9e9;
      &_text {
        display: flex;
        height: 50px;
        align-items: center;
        justify-content: space-between;
        font-size: 24px;
        font-weight: 600;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
        .button {
          cursor: pointer;
          background: #ffff;
          border: 0;
          transform: rotate(180eg);
        }
      }
    }
    .none {
      display: none;
    }
    .info4 {
      display: block;
      font-size: 20px;
      font-weight: 400;
      margin-bottom: 10px;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
  }
}
.SaveUser {
  height: 450px;
  position: relative;
  margin-bottom: 50px;
  &__block {
    position: absolute;
    left: 50%;
    transform: translate(-50%);
    width: 80%;
    height: 300px;
    border-radius: 20px;
    background: #f2f2f2f5;
    &_text {
      display: flex;
      justify-content: center;
      margin-top: 30px;
      font-size: 40px;
      font-weight: 500;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
    &_text1 {
      display: flex;
      justify-content: center;
      margin-top: 10px;
      font-size: 20px;
      font-weight: 500;
      color: #6d6d6d;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
    &__infos {
      display: flex;
      margin-top: 20px;
      justify-content: space-around;
      &__info {
        display: flex;
        align-items: center;
        &_texts {
          margin-left: 20px;
          &_text {
            font-size: 20px;
            font-weight: 700;
            margin-bottom: 10px;
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
          }
          &_text1 {
            color: #6d6d6d;
            font-size: 20px;
            font-weight: 400;
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
          }
        }
      }
    }
  }
  &_image {
    position: absolute;
    display: flex;
    bottom: 0;
    left: 0;
    right: 0;
    background: #000f1c;
    justify-content: space-around;
  }
}
</style>
