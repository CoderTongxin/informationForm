<template>
  <div id="form">
    <form class="ui form segment">
      <h4 class="ui dividing header center">货币数据查询</h4>
      <div class="field">
        <label>时间区间</label>
        <div class="two fields">
          <div class="field">
            <input type="text" name="shipping[first-name]" placeholder="起始日期">
          </div>
          <div class="field">
            <input type="text" name="shipping[last-name]" placeholder="截止日期">
          </div>
        </div>
      </div>
      <div class="two fields">
        <div class="field">
          <label>币种</label>
          <div class="ui fluid multiple search selection dropdown">
            <input type="hidden" name="country">
            <i class="dropdown icon"></i>
            <div class="default text">币种</div>
            <div class="menu">
              <div class="item" data-value="af"><i class="af flag"></i>Afghanistan</div>
              <div class="item" data-value="ax"><i class="ax flag"></i>Aland Islands</div>
              <div class="item" data-value="al"><i class="al flag"></i>Albania</div>
              <div class="item" data-value="dz"><i class="dz flag"></i>Algeria</div>
              <div class="item" data-value="as"><i class="as flag"></i>American Samoa</div>
              <div class="item" data-value="ad"><i class="ad flag"></i>Andorra</div>
              <div class="item" data-value="ao"><i class="ao flag"></i>Angola</div>
              <div class="item" data-value="ai"><i class="ai flag"></i>Anguilla</div>
              <div class="item" data-value="ag"><i class="ag flag"></i>Antigua</div>
              <div class="item" data-value="ar"><i class="ar flag"></i>Argentina</div>
            </div>
          </div>
        </div>
        <div class="field">
          <label>精度</label>
          <div class="ui fluid search selection dropdown" multiple="">
            <input type="hidden" name="country">
            <i class="dropdown icon"></i>
            <div class="default text">精度</div>
            <div class="menu">
              <div class="item" data-value="mr"><i class="mr flag"></i>Mauritania</div>
              <div class="item" data-value="mu"><i class="mu flag"></i>Mauritius</div>
              <div class="item" data-value="yt"><i class="yt flag"></i>Mayotte</div>
              <div class="item" data-value="mx"><i class="mx flag"></i>Mexico</div>
              <div class="item" data-value="fm"><i class="fm flag"></i>Micronesia</div>
              <div class="item" data-value="sm"><i class="sm flag"></i>San Marino</div>
              <div class="item" data-value="gs"><i class="gs flag"></i>Sandwich Islands</div>
              <div class="item" data-value="st"><i class="st flag"></i>Sao Tome</div>
              <div class="item" data-value="es"><i class="es flag"></i>Spain</div>
              <div class="item" data-value="lk"><i class="lk flag"></i>Sri Lanka</div>
              <div class="item" data-value="sd"><i class="sd flag"></i>Sudan</div>
              <div class="item" data-value="sr"><i class="sr flag"></i>Suriname</div>
              <div class="item" data-value="sj"><i class="sj flag"></i>Svalbard</div>
              <div class="item" data-value="sz"><i class="sz flag"></i>Swaziland</div>
              <div class="item" data-value="se"><i class="se flag"></i>Sweden</div>
              <div class="item" data-value="ch"><i class="ch flag"></i>Switzerland</div>
            </div>
          </div>
        </div>
      </div>
      <div class="two field">
        <div class="field">
          <label>交易对</label>
          <div class="ui fluid multiple search selection dropdown">
            <input type="hidden" name="country">
            <i class="dropdown icon"></i>
            <div class="default text">请选择交易对</div>
            <div class="menu">
              <div class="item" data-value="af"><i class="af flag"></i>Afghanistan</div>
              <div class="item" data-value="ax"><i class="ax flag"></i>Aland Islands</div>
              <div class="item" data-value="al"><i class="al flag"></i>Albania</div>
              <div class="item" data-value="dz"><i class="dz flag"></i>Algeria</div>
              <div class="item" data-value="as"><i class="as flag"></i>American Samoa</div>
              <div class="item" data-value="ad"><i class="ad flag"></i>Andorra</div>
              <div class="item" data-value="ao"><i class="ao flag"></i>Angola</div>
              <div class="item" data-value="ai"><i class="ai flag"></i>Anguilla</div>
              <div class="item" data-value="ag"><i class="ag flag"></i>Antigua</div>
              <div class="item" data-value="ar"><i class="ar flag"></i>Argentina</div>
            </div>
          </div>
        </div>
        <div class="field">
          <select class="ui fluid search dropdown" multiple="">
            <option value="">State</option>
            <option value="AL">Alabama</option>
            <option value="AK">Alaska</option>
            <option value="AZ">Arizona</option>
            <option value="AR">Arkansas</option>
            <option value="CA">California</option>
            <option value="CO">Colorado</option>
            <option value="CT">Connecticut</option>
            <option value="DE">Delaware</option>
            <option value="DC">District Of Columbia</option>
            <option value="FL">Florida</option>
            <option value="GA">Georgia</option>
            <option value="HI">Hawaii</option>
          </select>
        </div>
      </div>

      <div class="ui blue button" tabindex="0">提交查询</div>
    </form>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
