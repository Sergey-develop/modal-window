<template>
  <div class="head">
    <div class="block d-flex justify-content-center">
      <div class="main">
        <h1>Заголовок</h1>
        <p>
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry.
        </p>
      </div>

      <div class="feedback">
        <div>
          <div class="contacts">
            <b-row class="d-flex align-items-baseline justify-content-between">
              <b-col :lg="3">
                <label>Ваше имя</label>
              </b-col>
              <b-col :lg="9">
                <b-input class="input" placeholder="Иван Иванов" />
              </b-col>
            </b-row>

            <b-row class="d-flex align-items-baseline justify-content-between">
              <b-col :lg="3">
                <label>Ваш телефон</label>
              </b-col>

              <b-col :lg="9">
                <b-input
                  class="input"
                  placeholder="Константин Константинович"
                />
              </b-col>
            </b-row>

            <b-row>
              <div class="data justify-content-end">
                <div class="d-flex agreement justify-content-end">
                  <b-col :lg="9" class="d-flex">
                    <div class="checkboxes">
                      <input
                        type="checkbox"
                        value="1"
                        id="c1"
                        checked="checked"
                      />
                      <label class="check" for="c1"></label>
                    </div>
                    <p>
                      Я даю согласие на обработку персональных данных, я
                      ознакомился Политикой конфиденциальности
                    </p>
                  </b-col>
                </div>
              </div>
            </b-row>

            <b-row class="d-flex justify-content-center">
              <button class="button">Отправить</button>
            </b-row>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
