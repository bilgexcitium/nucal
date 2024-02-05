<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="a8e2cb7f-dff6-4701-ae3c-ebad5e2408d3"
    v-bind:style="{'width':'100%','height':'auto'}">
    <NucGroupElement v-bind:snapX="false" v-bind:snapY="false" v-bind:isLock="false" bgColor="" ncBgType="bgImage"
      position="relative" ncTooltipText="" backgroundImage="https://i.ibb.co/SdW5QPw/5.jpg"
      id="dc65826a-97c6-4cf9-9b48-21d48149501a"
      v-bind:style="{'color':'#FFFFFF','width':'100%','height':'100%','zIndex':2,'tabIndex':'-1','boxShadow':'','fontStyle':'normal','marginTop':'0px','textAlign':'center','fontFamily':'Roboto','fontWeight':400,'lineHeight':'1.25','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderColor':'#767676','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','borderBottomWidth':'1px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px'}">
      <WHeader v-bind:snapX="false" v-bind:snapY="false" heading="Test Site 1" position="relative"
        v-bind:textMuted="false" v-bind:isClipping="false" ncTypography="custom" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'heading','displayName':'Heading'}]}"
        ncClickFontColor="#0000FF" ncFocusFontColor="#00FF00" ncHoverFontColor="#ff0000" ncDisableFontColor="#4285f4"
        whichHeadTagForSize="h5" id="f227a898-442c-4e35-8cd9-3982b5cb6b3d"
        v-bind:style="{'color':'#000000FF','width':'100%','filter':'none','height':'100%','zIndex':4,'fontStyle':'normal','marginTop':'','textAlign':'center','background':'transparent','fontFamily':'Open Sans','fontWeight':700,'lineHeight':'1.75','marginLeft':'','paddingTop':'','marginRight':'','paddingLeft':'','marginBottom':'','mixBlendMode':'normal','paddingRight':'0px','paddingBottom':'0px','backdropFilter':'none','textDecoration':'none'}"/>
    </NucGroupElement>
    <NucGroupElement v-bind:snapX="true" v-bind:snapY="false" v-bind:isLock="false" bgColor="" ncBgType="bgImage"
      position="relative" ncTooltipText="" backgroundImage="https://i.ibb.co/mthD7HY/6.jpg"
      id="ecee1c38-e146-4943-97c5-fbd6df3045fd"
      v-bind:style="{'color':'#FFFFFF','width':'100%','height':'100%','zIndex':3,'tabIndex':'-1','boxShadow':'','fontStyle':'normal','marginTop':'0px','textAlign':'center','fontFamily':'Roboto','fontWeight':400,'lineHeight':'1.25','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderColor':'#767676','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','borderBottomWidth':'1px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px'}"/>
    <NucGroupElement v-bind:snapX="false" v-bind:snapY="false" v-bind:isLock="false" bgColor="" ncBgType="bgImage"
      position="relative" ncTooltipText=""
      backgroundImage="https://i.pinimg.com/736x/c9/45/5d/c9455d25f89a98d1f36dcb9692554df0.jpg"
      id="8e7dcc90-ea95-4586-928c-a83076aea63f"
      v-bind:style="{'color':'#FFFFFF','width':'100%','height':'100%','zIndex':4,'tabIndex':'-1','boxShadow':'','fontStyle':'normal','marginTop':'0px','textAlign':'center','fontFamily':'Roboto','fontWeight':400,'lineHeight':'1.25','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderColor':'#767676','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','borderBottomWidth':'1px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px'}"/>
  </DropZone>
</template>
<script>
import { mapGetters } from 'vuex';
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: { ...mapGetters('source', ['getApiMappingWithChain'])},
  methods: {bindSource(chain) { return this.getApiMappingWithChain(chain); }},
  watch: {},
};
</script>

<style lang="scss" scoped>@import 'src/assets/styles/scroll';
 @include custom-scroll();
@media (min-width: 1024.05px){
[id='a8e2cb7f-dff6-4701-ae3c-ebad5e2408d3'] {
             display: grid; 
             grid-template-columns: 0 0.15625rem 0 99.84375rem 0.15625rem 0 0;
             grid-template-rows: 0 minmax(60rem, max-content) 0 minmax(60rem, max-content) 0 minmax(60rem, max-content) 0;
          }
[id='dc65826a-97c6-4cf9-9b48-21d48149501a']{
          grid-area: 2/3/3/6;
          }
[id='ecee1c38-e146-4943-97c5-fbd6df3045fd']{
          grid-area: 4/2/5/5;
          }
[id='8e7dcc90-ea95-4586-928c-a83076aea63f']{
          grid-area: 6/4/7/7;
          }[id='dc65826a-97c6-4cf9-9b48-21d48149501a'] /deep/ > .component-wrapper{
             display: grid; 
             grid-template-columns: 33.828125rem 36.015625rem 30.15625rem;
             grid-template-rows: minmax(11.953125rem, max-content) minmax(7.421875rem, max-content) minmax(40.625rem, max-content);
          }
[id='f227a898-442c-4e35-8cd9-3982b5cb6b3d']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(66rem, 12px),5.15625rem);
          }
}
@media (min-width: 768.05px) and (max-width: 1024px){
[id='a8e2cb7f-dff6-4701-ae3c-ebad5e2408d3'] {
             display: grid; 
             grid-template-columns: 3.125rem 0 0 93.75rem 0 0 3.125rem;
             grid-template-rows: 0 minmax(56.25rem, max-content) 0 minmax(56.25rem, max-content) 0 minmax(56.25rem, max-content) minmax(3.125rem, max-content);
          }
[id='dc65826a-97c6-4cf9-9b48-21d48149501a']{
          grid-area: 2/2/3/7;
          }
[id='ecee1c38-e146-4943-97c5-fbd6df3045fd']{
          grid-area: 4/3/5/6;
          }
[id='8e7dcc90-ea95-4586-928c-a83076aea63f']{
          grid-area: 6/4/7/5;
          }[id='dc65826a-97c6-4cf9-9b48-21d48149501a'] /deep/ > .component-wrapper{
             display: grid; 
             grid-template-columns: 3.125rem 87.5rem 3.125rem;
             grid-template-rows: minmax(11.2060546875rem, max-content) minmax(6.9580078125rem, max-content) minmax(38.0859375rem, max-content);
          }
[id='f227a898-442c-4e35-8cd9-3982b5cb6b3d']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(66rem, 12px),12.527114967462039rem);
          }
}
@media (min-width: 480.05px) and (max-width: 768px){
[id='a8e2cb7f-dff6-4701-ae3c-ebad5e2408d3'] {
             display: grid; 
             grid-template-columns: 4.166666667000001rem 0 0 91.666666666rem 0 0 4.166666667000001rem;
             grid-template-rows: 0 minmax(54.9999999996rem, max-content) 0 minmax(54.9999999996rem, max-content) 0 minmax(54.9999999996rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='dc65826a-97c6-4cf9-9b48-21d48149501a']{
          grid-area: 2/2/3/7;
          }
[id='ecee1c38-e146-4943-97c5-fbd6df3045fd']{
          grid-area: 4/3/5/6;
          }
[id='8e7dcc90-ea95-4586-928c-a83076aea63f']{
          grid-area: 6/4/7/5;
          }[id='dc65826a-97c6-4cf9-9b48-21d48149501a'] /deep/ > .component-wrapper{
             display: grid; 
             grid-template-columns: 4.166666667rem 83.333333332rem 4.166666667rem;
             grid-template-rows: minmax(10.957031249920313rem, max-content) minmax(6.803385416617187rem, max-content) minmax(37.239583333062505rem, max-content);
          }
[id='f227a898-442c-4e35-8cd9-3982b5cb6b3d']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(66rem, 12px),11.93058568310629rem);
          }
}
@media (min-width: 375.05px) and (max-width: 480px){
[id='a8e2cb7f-dff6-4701-ae3c-ebad5e2408d3'] {
             display: grid; 
             grid-template-columns: 5rem 0 0 90rem 0 0 5rem;
             grid-template-rows: 0 minmax(53.99999999999999rem, max-content) 0 minmax(53.99999999999999rem, max-content) 0 minmax(53.99999999999999rem, max-content) minmax(5rem, max-content);
          }
[id='dc65826a-97c6-4cf9-9b48-21d48149501a']{
          grid-area: 2/2/3/7;
          }
[id='ecee1c38-e146-4943-97c5-fbd6df3045fd']{
          grid-area: 4/3/5/6;
          }
[id='8e7dcc90-ea95-4586-928c-a83076aea63f']{
          grid-area: 6/4/7/5;
          }[id='dc65826a-97c6-4cf9-9b48-21d48149501a'] /deep/ > .component-wrapper{
             display: grid; 
             grid-template-columns: 5rem 80rem 5rem;
             grid-template-rows: minmax(10.757812499999998rem, max-content) minmax(6.6796875rem, max-content) minmax(36.56249999999999rem, max-content);
          }
[id='f227a898-442c-4e35-8cd9-3982b5cb6b3d']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(66rem, 12px),11.453362255965292rem);
          }
}
@media (min-width: 0px) and (max-width: 375px){
[id='a8e2cb7f-dff6-4701-ae3c-ebad5e2408d3'] {
             display: grid; 
             grid-template-columns: 6.4rem 0 0 87.2rem 0 0 6.4rem;
             grid-template-rows: 0 minmax(52.32000000000001rem, max-content) 0 minmax(52.32000000000001rem, max-content) 0 minmax(52.32000000000001rem, max-content) minmax(6.4rem, max-content);
          }
[id='dc65826a-97c6-4cf9-9b48-21d48149501a']{
          grid-area: 2/2/3/7;
          }
[id='ecee1c38-e146-4943-97c5-fbd6df3045fd']{
          grid-area: 4/3/5/6;
          }
[id='8e7dcc90-ea95-4586-928c-a83076aea63f']{
          grid-area: 6/4/7/5;
          }[id='dc65826a-97c6-4cf9-9b48-21d48149501a'] /deep/ > .component-wrapper{
             display: grid; 
             grid-template-columns: 6.4rem 74.4rem 6.4rem;
             grid-template-rows: minmax(10.423125rem, max-content) minmax(6.471875rem, max-content) minmax(35.42500000000001rem, max-content);
          }
[id='f227a898-442c-4e35-8cd9-3982b5cb6b3d']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(66rem, 12px),10.651626898047724rem);
          }
}
</style>