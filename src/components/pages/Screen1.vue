<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="500"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="47c1a5e6-a44c-4467-bf3d-a3d86253364f" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WMultipleCollapse tag="div" v-bind:pill="false" size="md" text="Multiple Collapse" color="" v-bind:isNav="false"
        theme="theme--light01" v-bind:active="false" v-bind:appear="false" content="I am collapsible content!"
        v-bind:squared="false" variant="secondary" v-bind:visible="false" content2="I am collapsible second content!"
        accordion="" v-bind:isEnabled="true" background="" borderColor="rgb(210, 218, 236)" v-bind:hasAccordion="false"
        ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText="" textAccordion="Accordion 2"
        verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'content','displayName':'Content'},{'type':'string','propName':'text','displayName':'Text'}]}"
        verticalHeight="60px" v-bind:appearAccordion="false" horizontalWidth="72.4479px"
        contentAccordion="Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore VHS."
        horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        v-bind:visibleAccordion="false" ncClickBorderColor="#4285f4" ncDisableFontColor="#FFFFFF"
        ncFocusBorderColor="#4285f4" ncHoverBorderColor="#4285f4" v-bind:controlOfToggleCard="true"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4" ncFocusBackgroundColor="#4285f4"
        ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696" position="absolute" top="20.27373417721519%"
        left="46.81304347826087%" id="6060e42a-c8dc-4f00-8618-81f9954a4355"
        v-bind:style="{'width':'','height':'','fontSize':'8.444999999999999px','maxWidth':'675.5999999999999px','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'','fontFamily':'Roboto-Regular,Roboto','fontWeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'21.132036099999997px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
      <WClearRating id="2fbbd01b-ad2d-4690-8ee3-0a484dd02457" form="" size="md" stars="5" v-bind:inline="false"
        locale="" options="" variant="default" v-bind:disabled="false" iconFull="star-fill" iconHalf="star-half"
        v-bind:noBorder="false" v-bind:readonly="false" iconClear="x" iconEmpty="star" precision=""
        v-bind:showClear="true" v-bind:showValue="false" localValue="3" ratingColor="#495057"
        v-bind:showValueMax="false" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'localValue','displayName':'Value'}]}"
        ncFocusBorderColor="#000000" ncHoverBorderColor="#000000" ncDisableBorderColor="#000000"
        ncFocusBackgroundColor="transparent" ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent"
        position="absolute" top="34.83386075949367%" left="21.693478260869565%"
        v-bind:style="{'width':'','height':'','maxWidth':'','minWidth':'168.89999999999998px','tabIndex':'0px','boxShadow':'','marginTop':'','maxHeight':'','minHeight':'','lineHeight':'0.7881999999999999','marginLeft':'','paddingTop':'','visibility':'visible','borderStyle':'solid','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','borderTopWidth':'0.563px','textDecoration':'none','borderLeftWidth':'0.563px','borderRightWidth':'0.563px','horizontalHeight':'21.132036099999997px','borderBottomWidth':'0.563px','borderTopLeftRadius':'2.252px','borderTopRightRadius':'2.252px','borderBottomLeftRadius':'2.252px','borderBottomRightRadius':'2.252px','zIndex':3}"/>
      <WCarousel v-bind:fade="false" text="Text Content 1" ImgAlt="Blank Image 1" v-bind:noWrap="false"
        caption="Carousel 1" v-bind:noTouch="false" imageUrl="https://picsum.photos/500/250/?image=1082"
        v-bind:interval="5000" v-bind:isEnabled="true" background="" blankColor="#ababab" v-bind:indicators="false"
        secondText="Text Content 2" v-bind:noAnimation="false" v-bind:noHoverPause="false" secondImgAlt="Blank Image 2"
        secondCaption="Carousel 2"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imageUrl','displayName':'ImageUrl'},{'type':'string','propName':'secondImageUrl','displayName':'SecondImageUrl'}]}"
        secondImageUrl="https://picsum.photos/500/250/?image=1002" ncClickBorderColor="black" ncHoverBorderColor="black"
        dataModelForDynamicType="string" position="absolute" top="50.348101265822784%" left="49.63260869565217%"
        id="48905878-4295-406a-a6a8-b48f9258ec6c"
        v-bind:style="{'width':'281.5px','height':'140.75px','maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':4}"/>
      <WCalendar v-bind:fade="false" text="Text Content 1" theme="theme--light01" ImgAlt="Blank Image 1"
        v-bind:noWrap="false" caption="Carousel 1" v-bind:noTouch="false"
        imageUrl="https://picsum.photos/500/250/?image=1082" v-bind:interval="5000" v-bind:isEnabled="true"
        background="" blankColor="#ababab" v-bind:indicators="false" secondText="Text Content 2"
        v-bind:noAnimation="false" ncTypography="body2" v-bind:noHoverPause="false" secondImgAlt="Blank Image 2"
        secondCaption="Carousel 2"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imageUrl','displayName':'ImageUrl'},{'type':'string','propName':'secondImageUrl','displayName':'SecondImageUrl'}]}"
        secondImageUrl="https://picsum.photos/500/250/?image=1002" ncClickBorderColor="black" ncHoverBorderColor="black"
        dataModelForDynamicType="string" position="absolute" top="31.669056566455698%" left="31.919565217391305%"
        id="97303832-30db-4b21-8803-dff315a8b559"
        v-bind:style="{'width':'','height':'','fontSize':'6.755999999999999px','maxWidth':'','minWidth':'','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','fontFamily':'OpenSans-Bold,Open Sans','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':5}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>