(window["canvasWebpackJsonp"]=window["canvasWebpackJsonp"]||[]).push([[30],{"+oik":function(e,t,n){"use strict"
n.d(t,"a",(function(){return r}))
var o=n("VAKy")
var i=n("s54W")
class r{constructor(){this.insertLink=e=>{if(this.focusedEditor){var t
const n=this.focusedEditor.props.tinymce.get(this.focusedEditor.props.textareaId),o=n.selection
e.selectionDetails={node:o.getNode(),range:o.getRng()}
e.text||(e.text=e.title||e.href)
this.focusedEditor.insertLink(e)
null===(t=this.controller(this.focusedEditor.id))||void 0===t||t.hideTray()}else console.warn("clicked sidebar link without a focused editor")}
this.insertFileLink=e=>{const t=Object(i["a"])(e)
if("image"===t.type)return this.insertImage(e)
if("video"===t.type||"audio"===t.type){e.embedded_iframe_url=e.embedded_iframe_url||e.href
return this.embedMedia(e)}return this.insertLink(e)}
this.embedImage=e=>{this.existingContentToLink()&&!this.existingContentToLinkIsImg()?this.insertLink({title:e.display_name,href:e.href,embed:{type:"image"}}):this.insertImage(e)}
this.embedMedia=e=>{const t=Object(i["a"])(e)
"video"===t.type?this.insertVideo(e):this.insertAudio(e)}
this.insertEmbedCode=e=>{this.focusedEditor.insertEmbedCode(e)}
this.insertVideo=e=>{if(this.focusedEditor){var t
this.focusedEditor.insertVideo(e)
null===(t=this.controller(this.focusedEditor.id))||void 0===t||t.hideTray()}}
this.insertAudio=e=>{if(this.focusedEditor){var t
this.focusedEditor.insertAudio(e)
null===(t=this.controller(this.focusedEditor.id))||void 0===t||t.hideTray()}}
this.focusedEditor=null
this.resolveEditorRendered=null
this._editorRendered=new Promise(e=>{this.resolveEditorRendered=e})
this.trayProps=new WeakMap
this._languages=[]
this._controller={}
this._uploadMediaTranslations=null}get editorRendered(){return this._editorRendered}controller(e){return this._controller[e]}activeEditor(){return this.focusedEditor}focusEditor(e){this.focusedEditor!==e&&this.hideTrays()
this.focusedEditor=e}blurEditor(e){if(this.focusedEditor===e){this.hideTrays()
this.focusedEditor=null}}focusActiveEditor(e=false){var t,n,o
null===(t=this.focusedEditor)||void 0===t||null===(n=t.mceInstance)||void 0===n||null===(o=n.call(t))||void 0===o||o.focus(e)}get mediaServerSession(){return this._mediaServerSession}get mediaServerUploader(){return this._mediaServerUploader}setMediaServerSession(e){this._mediaServerSession=e
if(this._mediaServerUploader){this._mediaServerUploader.destroy()
this._mediaServerUploader=null}this._mediaServerUploader=new o["a"](e)}get languages(){return this._languages}set languages(e){this._languages=e}get uploadMediaTranslations(){if(!this._uploadMediaTranslations){const e=n("Wfew")
this._uploadMediaTranslations=e.default}return this._uploadMediaTranslations}detachEditor(e){e===this.focusedEditor&&(this.focusedEditor=null)}getEditor(){return this.focusedEditor}renderEditor(e){this.resolveEditorRendered()
null===this.focusedEditor&&this.focusEditor(e)}attachController(e,t){this._controller[t]=e}detachController(e){delete this._controller[e]}showTrayForPlugin(e,t){var n
null===(n=this._controller[t])||void 0===n||n.showTrayForPlugin(e)}hideTrays(){Object.keys(this._controller).forEach(e=>{this._controller[e].hideTray(true)})}existingContentToLink(){if(this.focusedEditor)return this.focusedEditor.existingContentToLink()
return false}existingContentToLinkIsImg(){if(this.focusedEditor)return this.focusedEditor.existingContentToLinkIsImg()
return false}insertImage(e){if(this.focusedEditor){var t
this.focusedEditor.insertImage(e)
null===(t=this.controller(this.focusedEditor.id))||void 0===t||t.hideTray()}else console.warn("clicked sidebar image without a focused editor")}insertImagePlaceholder(e){this.focusedEditor?this.existingContentToLink()||this.focusedEditor.insertImagePlaceholder(e):console.warn("clicked sidebar image without a focused editor")}removePlaceholders(e){this.focusedEditor&&this.focusedEditor.removePlaceholders(e)}showError(e){this.focusedEditor&&this.focusedEditor.addAlert({text:e.toString(),type:"error"})}}},"/5Zp":function(e,t,n){"use strict"
n.d(t,"a",(function(){return k}))
var o=n("1OyB")
var i=n("vuIU")
var r=n("Ji7U")
var a=n("LK+K")
var c=n("q1tI")
var s=n.n(c)
var l=n("17x9")
var d=n.n(l)
var u=n("cClk")
var x=n("sTNg")
var _=n("BTe1")
var m=n("oXx0")
var p=n("4Awi")
var f=n("II2N")
var h=n("jtGx")
var y=n("GTSS")
var b,g,v,w
var k=(b=Object(m["a"])(),b(g=(w=v=function(e){Object(r["a"])(n,e)
var t=Object(a["a"])(n)
function n(e){var i
Object(o["a"])(this,n)
i=t.call(this)
i.handleChange=function(e){var t=e.target.value
if(i.props.disabled||i.props.readOnly){e.preventDefault()
return}"undefined"===typeof i.props.value&&i.setState({value:t})
"function"===typeof i.props.onChange&&i.props.onChange(e,t)}
"undefined"===typeof e.value&&(i.state={value:e.defaultValue})
i._messagesId=Object(_["a"])("RadioInputGroup-messages")
return i}Object(i["a"])(n,[{key:"renderChildren",value:function(){var e=this
var t=this.props,n=t.children,o=t.name,i=t.variant,r=t.size,a=t.disabled,s=t.readOnly
return c["Children"].map(n,(function(t,n){if(Object(p["a"])(t,[y["a"]])){var c=e.value===t.props.value
var l=!e.value&&0===n
return Object(f["a"])(t,{name:o,disabled:a||t.props.disabled,variant:i,size:r,checked:c,onChange:e.handleChange,readOnly:s||t.props.readOnly,width:t.props.width||"auto","aria-describedby":e.hasMessages&&e._messagesId,tabIndex:c||l?"0":"-1"})}return t}))}},{key:"render",value:function(){var e=this.props,t=e.variant,o=e.layout
return s.a.createElement(x["b"],Object.assign({},Object(h["a"])(this.props,n.propTypes),Object(h["c"])(this.props,x["b"].propTypes),{layout:"columns"===o&&"toggle"===t?"stacked":o,vAlign:"toggle"===t?"middle":"top",rowSpacing:"small",colSpacing:"toggle"===t?"none":"small",startAt:"toggle"===t?"small":void 0,messagesId:this._messagesId}),this.renderChildren())}},{key:"hasMessages",get:function(){return this.props.messages&&this.props.messages.length>0}},{key:"value",get:function(){return"undefined"===typeof this.props.value?this.state.value:this.props.value}}])
n.displayName="RadioInputGroup"
return n}(c["Component"]),v.propTypes={name:d.a.string.isRequired,description:d.a.node.isRequired,defaultValue:d.a.oneOfType([d.a.string,d.a.number]),value:Object(u["a"])(d.a.oneOfType([d.a.string,d.a.number])),onChange:d.a.func,disabled:d.a.bool,readOnly:d.a.bool,messages:d.a.arrayOf(x["d"].message),children:d.a.node,variant:d.a.oneOf(["simple","toggle"]),size:d.a.oneOf(["small","medium","large"]),layout:d.a.oneOf(["stacked","columns","inline"])},v.defaultProps={disabled:false,variant:"simple",size:"medium",layout:"stacked",readOnly:false,defaultValue:void 0,value:void 0,children:null,messages:void 0,onChange:void 0},w))||g)},"/7Jz":function(e,t,n){"use strict"
n.r(t)
n.d(t,"StyleSheet",(function(){return dt}))
n.d(t,"StyleSheetServer",(function(){return ut}))
n.d(t,"StyleSheetTestUtils",(function(){return xt}))
n.d(t,"css",(function(){return _t}))
n.d(t,"minify",(function(){return mt}))
n.d(t,"flushToStyleTag",(function(){return pt}))
n.d(t,"injectAndGetClassName",(function(){return ft}))
n.d(t,"defaultSelectorHandlers",(function(){return ht}))
n.d(t,"reset",(function(){return yt}))
n.d(t,"resetInjectedStyle",(function(){return bt}))
var o=n("9kyW")
var i=n.n(o)
var r=n("IEa/")
var a=n.n(r)
function c(e){c="function"===typeof Symbol&&"symbol"===typeof Symbol.iterator?function(e){return typeof e}:function(e){return e&&"function"===typeof Symbol&&e.constructor===Symbol&&e!==Symbol.prototype?"symbol":typeof e}
return c(e)}function s(e,t,n){t in e?Object.defineProperty(e,t,{value:n,enumerable:true,configurable:true,writable:true}):e[t]=n
return e}function l(e){for(var t=1;t<arguments.length;t++){var n=null!=arguments[t]?arguments[t]:{}
var o=Object.keys(n)
"function"===typeof Object.getOwnPropertySymbols&&(o=o.concat(Object.getOwnPropertySymbols(n).filter((function(e){return Object.getOwnPropertyDescriptor(n,e).enumerable}))))
o.forEach((function(t){s(e,t,n[t])}))}return e}function d(e){return u(e)||x(e)||_()}function u(e){if(Array.isArray(e)){for(var t=0,n=new Array(e.length);t<e.length;t++)n[t]=e[t]
return n}}function x(e){if(Symbol.iterator in Object(e)||"[object Arguments]"===Object.prototype.toString.call(e))return Array.from(e)}function _(){throw new TypeError("Invalid attempt to spread non-iterable instance")}var m=/([A-Z])/g
var p=function(e){return"-".concat(e.toLowerCase())}
var f=function(e){var t=e.replace(m,p)
if("m"===t[0]&&"s"===t[1]&&"-"===t[2])return"-".concat(t)
return t}
var h={animationIterationCount:true,borderImageOutset:true,borderImageSlice:true,borderImageWidth:true,boxFlex:true,boxFlexGroup:true,boxOrdinalGroup:true,columnCount:true,flex:true,flexGrow:true,flexPositive:true,flexShrink:true,flexNegative:true,flexOrder:true,gridRow:true,gridColumn:true,fontWeight:true,lineClamp:true,lineHeight:true,opacity:true,order:true,orphans:true,tabSize:true,widows:true,zIndex:true,zoom:true,fillOpacity:true,floodOpacity:true,stopOpacity:true,strokeDasharray:true,strokeDashoffset:true,strokeMiterlimit:true,strokeOpacity:true,strokeWidth:true}
function y(e,t){return e+t.charAt(0).toUpperCase()+t.substring(1)}var b=["Webkit","ms","Moz","O"]
Object.keys(h).forEach((function(e){b.forEach((function(t){h[y(t,e)]=h[e]}))}))
var g=function(e,t){return"number"===typeof t?h[e]?""+t:t+"px":""+t}
var v=function(e,t){return C(g(e,t))}
var w=function(e,t){return i()(e).toString(36)}
var k=function(e){return w(JSON.stringify(e))}
var C=function(e){return"!"===e[e.length-10]&&" !important"===e.slice(-11)?e:"".concat(e," !important")}
var O="undefined"!==typeof Map
var E=function(){function e(){this.elements={}
this.keyOrder=[]}var t=e.prototype
t.forEach=function(e){for(var t=0;t<this.keyOrder.length;t++)e(this.elements[this.keyOrder[t]],this.keyOrder[t])}
t.set=function(t,n,o){if(this.elements.hasOwnProperty(t)){if(o){var i=this.keyOrder.indexOf(t)
this.keyOrder.splice(i,1)
this.keyOrder.push(t)}}else this.keyOrder.push(t)
if(null==n){this.elements[t]=n
return}if(O&&n instanceof Map||n instanceof e){var r=this.elements.hasOwnProperty(t)?this.elements[t]:new e
n.forEach((function(e,t){r.set(t,e,o)}))
this.elements[t]=r
return}if(!Array.isArray(n)&&"object"===c(n)){var a=this.elements.hasOwnProperty(t)?this.elements[t]:new e
var s=Object.keys(n)
for(var l=0;l<s.length;l+=1)a.set(s[l],n[s[l]],o)
this.elements[t]=a
return}this.elements[t]=n}
t.get=function(e){return this.elements[e]}
t.has=function(e){return this.elements.hasOwnProperty(e)}
t.addStyleType=function(t){var n=this
if(O&&t instanceof Map||t instanceof e)t.forEach((function(e,t){n.set(t,e,true)}))
else{var o=Object.keys(t)
for(var i=0;i<o.length;i++)this.set(o[i],t[o[i]],true)}}
return e}()
function A(e){return e&&e.__esModule&&Object.prototype.hasOwnProperty.call(e,"default")?e.default:e}function S(e,t){return t={exports:{}},e(t,t.exports),t.exports}function j(e){return e&&e.default||e}var I=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=n
function n(e){return e.charAt(0).toUpperCase()+e.slice(1)}}))
A(I)
var T=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=i
var n=o(I)
function o(e){return e&&e.__esModule?e:{default:e}}function i(e,t,o){if(e.hasOwnProperty(t)){var i={}
var r=e[t]
var a=(0,n.default)(t)
var c=Object.keys(o)
for(var s=0;s<c.length;s++){var l=c[s]
if(l===t)for(var d=0;d<r.length;d++)i[r[d]+a]=o[t]
i[l]=o[l]}return i}return o}}))
A(T)
var L=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=n
function n(e,t,n,o,i){for(var r=0,a=e.length;r<a;++r){var c=e[r](t,n,o,i)
if(c)return c}}}))
A(L)
var B=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=o
function n(e,t){-1===e.indexOf(t)&&e.push(t)}function o(e,t){if(Array.isArray(t))for(var o=0,i=t.length;o<i;++o)n(e,t[o])
else n(e,t)}}))
A(B)
var D=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=n
function n(e){return e instanceof Object&&!Array.isArray(e)}}))
A(D)
var R=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=c
var n=a(T)
var o=a(L)
var i=a(B)
var r=a(D)
function a(e){return e&&e.__esModule?e:{default:e}}function c(e){var t=e.prefixMap,a=e.plugins
return function e(c){for(var s in c){var l=c[s]
if((0,r.default)(l))c[s]=e(l)
else if(Array.isArray(l)){var d=[]
for(var u=0,x=l.length;u<x;++u){var _=(0,o.default)(a,s,l[u],c,t);(0,i.default)(d,_||l[u])}d.length>0&&(c[s]=d)}else{var m=(0,o.default)(a,s,l,c,t)
m&&(c[s]=m)
c=(0,n.default)(t,s,c)}}return c}}}))
var F=A(R)
var M=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=n
function n(e,t){if("string"===typeof t&&"text"===t)return["-webkit-text","text"]}}))
var z=A(M)
var P=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=o
var n=/-webkit-|-moz-|-ms-/
function o(e){return"string"===typeof e&&n.test(e)}e.exports=t["default"]}))
A(P)
var N=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=r
var n=o(P)
function o(e){return e&&e.__esModule?e:{default:e}}var i=["-webkit-","-moz-",""]
function r(e,t){if("string"===typeof t&&!(0,n.default)(t)&&t.indexOf("calc(")>-1)return i.map((function(e){return t.replace(/calc\(/g,e+"calc(")}))}}))
var U=A(N)
var $=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=r
var n=o(P)
function o(e){return e&&e.__esModule?e:{default:e}}var i=["-webkit-",""]
function r(e,t){if("string"===typeof t&&!(0,n.default)(t)&&t.indexOf("cross-fade(")>-1)return i.map((function(e){return t.replace(/cross-fade\(/g,e+"cross-fade(")}))}}))
var H=A($)
var W=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=i
var n=["-webkit-","-moz-",""]
var o={"zoom-in":true,"zoom-out":true,grab:true,grabbing:true}
function i(e,t){if("cursor"===e&&o.hasOwnProperty(t))return n.map((function(e){return e+t}))}}))
var q=A(W)
var V=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=r
var n=o(P)
function o(e){return e&&e.__esModule?e:{default:e}}var i=["-webkit-",""]
function r(e,t){if("string"===typeof t&&!(0,n.default)(t)&&t.indexOf("filter(")>-1)return i.map((function(e){return t.replace(/filter\(/g,e+"filter(")}))}}))
var G=A(V)
var K=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=o
var n={flex:["-webkit-box","-moz-box","-ms-flexbox","-webkit-flex","flex"],"inline-flex":["-webkit-inline-box","-moz-inline-box","-ms-inline-flexbox","-webkit-inline-flex","inline-flex"]}
function o(e,t){if("display"===e&&n.hasOwnProperty(t))return n[t]}}))
var Z=A(K)
var Y=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=a
var n={"space-around":"distribute","space-between":"justify","flex-start":"start","flex-end":"end"}
var o={alignContent:"msFlexLinePack",alignSelf:"msFlexItemAlign",alignItems:"msFlexAlign",justifyContent:"msFlexPack",order:"msFlexOrder",flexGrow:"msFlexPositive",flexShrink:"msFlexNegative",flexBasis:"msFlexPreferredSize"}
var i={auto:"1 1 auto",inherit:"inherit",initial:"0 1 auto",none:"0 0 auto",unset:"unset"}
var r=/^\d+(\.\d+)?$/
function a(e,t,a){Object.prototype.hasOwnProperty.call(o,e)&&(a[o[e]]=n[t]||t)
if("flex"===e){if(Object.prototype.hasOwnProperty.call(i,t)){a.msFlex=i[t]
return}if(r.test(t)){a.msFlex=t+" 1 0%"
return}var c=t.split(/\s/)
switch(c.length){case 1:a.msFlex="1 1 "+t
return
case 2:r.test(c[1])?a.msFlex=c[0]+" "+c[1]+" 0%":a.msFlex=c[0]+" 1 "+c[1]
return
default:a.msFlex=t}}}}))
var J=A(Y)
var X=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=i
var n={"space-around":"justify","space-between":"justify","flex-start":"start","flex-end":"end","wrap-reverse":"multiple",wrap:"multiple"}
var o={alignItems:"WebkitBoxAlign",justifyContent:"WebkitBoxPack",flexWrap:"WebkitBoxLines",flexGrow:"WebkitBoxFlex"}
function i(e,t,i){if("flexDirection"===e&&"string"===typeof t){t.indexOf("column")>-1?i.WebkitBoxOrient="vertical":i.WebkitBoxOrient="horizontal"
t.indexOf("reverse")>-1?i.WebkitBoxDirection="reverse":i.WebkitBoxDirection="normal"}o.hasOwnProperty(e)&&(i[o[e]]=n[t]||t)}}))
var Q=A(X)
var ee=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=a
var n=o(P)
function o(e){return e&&e.__esModule?e:{default:e}}var i=["-webkit-","-moz-",""]
var r=/linear-gradient|radial-gradient|repeating-linear-gradient|repeating-radial-gradient/gi
function a(e,t){if("string"===typeof t&&!(0,n.default)(t)&&r.test(t))return i.map((function(e){return t.replace(r,(function(t){return e+t}))}))}}))
var te=A(ee)
var ne=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
var n=function(){function e(e,t){var n=[]
var o=true
var i=false
var r=void 0
try{for(var a,c=e[Symbol.iterator]();!(o=(a=c.next()).done);o=true){n.push(a.value)
if(t&&n.length===t)break}}catch(e){i=true
r=e}finally{try{!o&&c["return"]&&c["return"]()}finally{if(i)throw r}}return n}return function(t,n){if(Array.isArray(t))return t
if(Symbol.iterator in Object(t))return e(t,n)
throw new TypeError("Invalid attempt to destructure non-iterable instance")}}()
t.default=c
function o(e){return"number"===typeof e&&!isNaN(e)}var i=["center","end","start","stretch"]
var r={"inline-grid":["-ms-inline-grid","inline-grid"],grid:["-ms-grid","grid"]}
var a={alignSelf:function(e,t){i.indexOf(e)>-1&&(t.msGridRowAlign=e)},gridColumn:function(e,t){if(o(e))t.msGridColumn=e
else{var i=e.split("/").map((function(e){return+e})),r=n(i,2),c=r[0],s=r[1]
a.gridColumnStart(c,t)
a.gridColumnEnd(s,t)}},gridColumnEnd:function(e,t){var n=t.msGridColumn
o(e)&&o(n)&&(t.msGridColumnSpan=e-n)},gridColumnStart:function(e,t){o(e)&&(t.msGridColumn=e)},gridRow:function(e,t){if(o(e))t.msGridRow=e
else{var i=e.split("/").map((function(e){return+e})),r=n(i,2),c=r[0],s=r[1]
a.gridRowStart(c,t)
a.gridRowEnd(s,t)}},gridRowEnd:function(e,t){var n=t.msGridRow
o(e)&&o(n)&&(t.msGridRowSpan=e-n)},gridRowStart:function(e,t){o(e)&&(t.msGridRow=e)},gridTemplateColumns:function(e,t){t.msGridColumns=e},gridTemplateRows:function(e,t){t.msGridRows=e},justifySelf:function(e,t){i.indexOf(e)>-1&&(t.msGridColumnAlign=e)}}
function c(e,t,n){if("display"===e&&t in r)return r[t]
if(e in a){var o=a[e]
o(t,n)}}}))
var oe=A(ne)
var ie=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=r
var n=o(P)
function o(e){return e&&e.__esModule?e:{default:e}}var i=["-webkit-",""]
function r(e,t){if("string"===typeof t&&!(0,n.default)(t)&&t.indexOf("image-set(")>-1)return i.map((function(e){return t.replace(/image-set\(/g,e+"image-set(")}))}}))
var re=A(ie)
var ae=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=o
var n={marginBlockStart:["WebkitMarginBefore"],marginBlockEnd:["WebkitMarginAfter"],marginInlineStart:["WebkitMarginStart","MozMarginStart"],marginInlineEnd:["WebkitMarginEnd","MozMarginEnd"],paddingBlockStart:["WebkitPaddingBefore"],paddingBlockEnd:["WebkitPaddingAfter"],paddingInlineStart:["WebkitPaddingStart","MozPaddingStart"],paddingInlineEnd:["WebkitPaddingEnd","MozPaddingEnd"],borderBlockStart:["WebkitBorderBefore"],borderBlockStartColor:["WebkitBorderBeforeColor"],borderBlockStartStyle:["WebkitBorderBeforeStyle"],borderBlockStartWidth:["WebkitBorderBeforeWidth"],borderBlockEnd:["WebkitBorderAfter"],borderBlockEndColor:["WebkitBorderAfterColor"],borderBlockEndStyle:["WebkitBorderAfterStyle"],borderBlockEndWidth:["WebkitBorderAfterWidth"],borderInlineStart:["WebkitBorderStart","MozBorderStart"],borderInlineStartColor:["WebkitBorderStartColor","MozBorderStartColor"],borderInlineStartStyle:["WebkitBorderStartStyle","MozBorderStartStyle"],borderInlineStartWidth:["WebkitBorderStartWidth","MozBorderStartWidth"],borderInlineEnd:["WebkitBorderEnd","MozBorderEnd"],borderInlineEndColor:["WebkitBorderEndColor","MozBorderEndColor"],borderInlineEndStyle:["WebkitBorderEndStyle","MozBorderEndStyle"],borderInlineEndWidth:["WebkitBorderEndWidth","MozBorderEndWidth"]}
function o(e,t,o){if(Object.prototype.hasOwnProperty.call(n,e)){var i=n[e]
for(var r=0,a=i.length;r<a;++r)o[i[r]]=t}}}))
var ce=A(ae)
var se=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=n
function n(e,t){if("position"===e&&"sticky"===t)return["-webkit-sticky","sticky"]}}))
var le=A(se)
var de=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=r
var n=["-webkit-","-moz-",""]
var o={maxHeight:true,maxWidth:true,width:true,height:true,columnWidth:true,minWidth:true,minHeight:true}
var i={"min-content":true,"max-content":true,"fill-available":true,"fit-content":true,"contain-floats":true}
function r(e,t){if(o.hasOwnProperty(e)&&i.hasOwnProperty(t))return n.map((function(e){return e+t}))}}))
var ue=A(de)
var xe=/[A-Z]/g
var _e=/^ms-/
var me={}
function pe(e){return"-"+e.toLowerCase()}function fe(e){if(me.hasOwnProperty(e))return me[e]
var t=e.replace(xe,pe)
return me[e]=_e.test(t)?"-"+t:t}var he=Object.freeze({default:fe})
var ye=j(he)
var be=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=i
var n=o(ye)
function o(e){return e&&e.__esModule?e:{default:e}}function i(e){return(0,n.default)(e)}e.exports=t["default"]}))
A(be)
var ge=S((function(e,t){Object.defineProperty(t,"__esModule",{value:true})
t.default=l
var n=r(be)
var o=r(P)
var i=r(I)
function r(e){return e&&e.__esModule?e:{default:e}}var a={transition:true,transitionProperty:true,WebkitTransition:true,WebkitTransitionProperty:true,MozTransition:true,MozTransitionProperty:true}
var c={Webkit:"-webkit-",Moz:"-moz-",ms:"-ms-"}
function s(e,t){if((0,o.default)(e))return e
var i=e.split(/,(?![^()]*(?:\([^()]*\))?\))/g)
for(var r=0,a=i.length;r<a;++r){var s=i[r]
var l=[s]
for(var d in t){var u=(0,n.default)(d)
if(s.indexOf(u)>-1&&"order"!==u){var x=t[d]
for(var _=0,m=x.length;_<m;++_)l.unshift(s.replace(u,c[x[_]]+u))}}i[r]=l.join(",")}return i.join(",")}function l(e,t,n,o){if("string"===typeof t&&a.hasOwnProperty(e)){var r=s(t,o)
var c=r.split(/,(?![^()]*(?:\([^()]*\))?\))/g).filter((function(e){return!/-moz-|-ms-/.test(e)})).join(",")
if(e.indexOf("Webkit")>-1)return c
var l=r.split(/,(?![^()]*(?:\([^()]*\))?\))/g).filter((function(e){return!/-webkit-|-ms-/.test(e)})).join(",")
if(e.indexOf("Moz")>-1)return l
n["Webkit"+(0,i.default)(e)]=c
n["Moz"+(0,i.default)(e)]=l
return r}}}))
var ve=A(ge)
var we=["Webkit"]
var ke=["Moz"]
var Ce=["ms"]
var Oe=["Webkit","Moz"]
var Ee=["Webkit","ms"]
var Ae=["Webkit","Moz","ms"]
var Se={plugins:[z,U,H,q,G,Z,J,Q,te,oe,re,ce,le,ue,ve],prefixMap:{transform:Ee,transformOrigin:Ee,transformOriginX:Ee,transformOriginY:Ee,backfaceVisibility:we,perspective:we,perspectiveOrigin:we,transformStyle:we,transformOriginZ:we,animation:we,animationDelay:we,animationDirection:we,animationFillMode:we,animationDuration:we,animationIterationCount:we,animationName:we,animationPlayState:we,animationTimingFunction:we,appearance:Oe,userSelect:Ae,fontKerning:we,textEmphasisPosition:we,textEmphasis:we,textEmphasisStyle:we,textEmphasisColor:we,boxDecorationBreak:we,clipPath:we,maskImage:we,maskMode:we,maskRepeat:we,maskPosition:we,maskClip:we,maskOrigin:we,maskSize:we,maskComposite:we,mask:we,maskBorderSource:we,maskBorderMode:we,maskBorderSlice:we,maskBorderWidth:we,maskBorderOutset:we,maskBorderRepeat:we,maskBorder:we,maskType:we,textDecorationStyle:Oe,textDecorationSkip:Oe,textDecorationLine:Oe,textDecorationColor:Oe,filter:we,fontFeatureSettings:Oe,breakAfter:Ae,breakBefore:Ae,breakInside:Ae,columnCount:Oe,columnFill:Oe,columnGap:Oe,columnRule:Oe,columnRuleColor:Oe,columnRuleStyle:Oe,columnRuleWidth:Oe,columns:Oe,columnSpan:Oe,columnWidth:Oe,writingMode:Ee,flex:Ee,flexBasis:we,flexDirection:Ee,flexGrow:we,flexFlow:Ee,flexShrink:we,flexWrap:Ee,alignContent:we,alignItems:we,alignSelf:we,justifyContent:we,order:we,transitionDelay:we,transitionDuration:we,transitionProperty:we,transitionTimingFunction:we,backdropFilter:we,scrollSnapType:Ee,scrollSnapPointsX:Ee,scrollSnapPointsY:Ee,scrollSnapDestination:Ee,scrollSnapCoordinate:Ee,shapeImageThreshold:we,shapeImageMargin:we,shapeImageOutside:we,hyphens:Ae,flowInto:Ee,flowFrom:Ee,regionFragment:Ee,textOrientation:we,boxSizing:ke,textAlignLast:ke,tabSize:ke,wrapFlow:Ce,wrapThrough:Ce,wrapMargin:Ce,touchAction:Ce,textSizeAdjust:Ee,borderImage:we,borderImageOutset:we,borderImageRepeat:we,borderImageSlice:we,borderImageSource:we,borderImageWidth:we}}
var je=F(Se)
var Ie=[function(e,t,n){if(":"!==e[0])return null
return n(t+e)},function(e,t,n){if("@"!==e[0])return null
var o=n(t)
return["".concat(e,"{").concat(o.join(""),"}")]}]
var Te=function e(t,n,o,i,r){var a=new E
for(var c=0;c<n.length;c++)a.addStyleType(n[c])
var s=new E
var l=[]
a.forEach((function(n,a){var c=o.some((function(c){var s=c(a,t,(function(t){return e(t,[n],o,i,r)}))
if(null!=s){if(Array.isArray(s))l.push.apply(l,d(s))
else{console.warn("WARNING: Selector handlers should return an array of rules.Returning a string containing multiple rules is deprecated.",c)
l.push("@media all {".concat(s,"}"))}return true}}))
c||s.set(a,n,true)}))
var u=Re(t,s,i,r,o)
u&&l.unshift(u)
return l}
var Le=function(e,t,n){if(!t)return
var o=Object.keys(t)
for(var i=0;i<o.length;i++){var r=o[i]
e.has(r)&&e.set(r,t[r](e.get(r),n),false)}}
var Be=function(e,t,n){return"".concat(f(e),":").concat(n(e,t),";")}
var De=function(e,t){e[t]=true
return e}
var Re=function(e,t,n,o,i){Le(t,n,i)
var r=Object.keys(t.elements).reduce(De,Object.create(null))
var a=je(t.elements)
var c=Object.keys(a)
if(c.length!==t.keyOrder.length)for(var s=0;s<c.length;s++)if(!r[c[s]]){var l=void 0
l="W"===c[s][0]?c[s][6].toLowerCase()+c[s].slice(7):"o"===c[s][1]?c[s][3].toLowerCase()+c[s].slice(4):c[s][2].toLowerCase()+c[s].slice(3)
if(l&&r[l]){var d=t.keyOrder.indexOf(l)
t.keyOrder.splice(d,0,c[s])}else t.keyOrder.unshift(c[s])}var u=false===o?g:v
var x=[]
for(var _=0;_<t.keyOrder.length;_++){var m=t.keyOrder[_]
var p=a[m]
if(Array.isArray(p))for(var f=0;f<p.length;f++)x.push(Be(m,p[f],u))
else x.push(Be(m,p,u))}return x.length?"".concat(e,"{").concat(x.join(""),"}"):""}
var Fe=null
var Me=function(e){if(null==Fe){Fe=document.querySelector("style[data-aphrodite]")
if(null==Fe){var t=document.head||document.getElementsByTagName("head")[0]
Fe=document.createElement("style")
Fe.type="text/css"
Fe.setAttribute("data-aphrodite","")
t.appendChild(Fe)}}var n=Fe.styleSheet||Fe.sheet
if(n.insertRule){var o=n.cssRules.length
e.forEach((function(e){try{n.insertRule(e,o)
o+=1}catch(e){}}))}else Fe.innerText=(Fe.innerText||"")+e.join("")}
var ze={fontFamily:function e(t){if(Array.isArray(t)){var n={}
t.forEach((function(t){n[e(t)]=true}))
return Object.keys(n).join(",")}if("object"===c(t)){He(t.src,"@font-face",[t],false)
return'"'.concat(t.fontFamily,'"')}return t},animationName:function e(t,n){if(Array.isArray(t))return t.map((function(t){return e(t,n)})).join(",")
if("object"===c(t)){var o="keyframe_".concat(k(t))
var i="@keyframes ".concat(o,"{")
t instanceof E?t.forEach((function(e,t){i+=Te(t,[e],n,ze,false).join("")})):Object.keys(t).forEach((function(e){i+=Te(e,[t[e]],n,ze,false).join("")}))
i+="}"
$e(o,[i])
return o}return t}}
var Pe={}
var Ne=[]
var Ue=false
var $e=function(e,t){var n
if(Pe[e])return
if(!Ue){if("undefined"===typeof document)throw new Error("Cannot automatically buffer without a document")
Ue=true
a()(Ze)}(n=Ne).push.apply(n,d(t))
Pe[e]=true}
var He=function(e,t,n,o){var i=arguments.length>4&&void 0!==arguments[4]?arguments[4]:[]
if(Pe[e])return
var r=Te(t,n,i,ze,o)
$e(e,r)}
var We=function(){Ne=[]
Pe={}
Ue=false
Fe=null}
var qe=function(e){delete Pe[e]}
var Ve=function(){if(Ue)throw new Error("Cannot buffer while already buffering")
Ue=true}
var Ge=function(){Ue=false
var e=Ne
Ne=[]
return e}
var Ke=function(){return Ge().join("")}
var Ze=function(){var e=Ge()
e.length>0&&Me(e)}
var Ye=function(){return Object.keys(Pe)}
var Je=function(e){e.forEach((function(e){Pe[e]=true}))}
var Xe=function(e){return"_definition"in e&&"_name"in e&&"_len"in e}
var Qe=function e(t,n,o,i){for(var r=0;r<t.length;r+=1)if(t[r])if(Array.isArray(t[r]))i+=e(t[r],n,o,i)
else{if(!Xe(t[r]))throw new Error("Invalid Style Definition: Styles should be defined using the StyleSheet.create method.")
n.push(t[r]._name)
o.push(t[r]._definition)
i+=t[r]._len}return i}
var et=function(e,t,n){var o=[]
var i=[]
var r=Qe(t,o,i,0)
if(0===o.length)return""
var a
a=1===o.length?"_".concat(o[0]):"_".concat(w(o.join())).concat((r%36).toString(36))
He(a,".".concat(a),i,e,n)
return a}
var tt=function(e,t){return"".concat(t,"_").concat(w(e))}
var nt=function(){return w}
var ot=nt()
var it={create:function(e){var t={}
var n=Object.keys(e)
for(var o=0;o<n.length;o+=1){var i=n[o]
var r=e[i]
var a=JSON.stringify(r)
t[i]={_len:a.length,_name:ot(a,i),_definition:r}}return t},rehydrate:function(){var e=arguments.length>0&&void 0!==arguments[0]?arguments[0]:[]
Je(e)}}
var rt="undefined"!==typeof window?null:{renderStatic:function(e){We()
Ve()
var t=e()
var n=Ke()
return{html:t,css:{content:n,renderedClassNames:Ye()}}}}
var at=null
function ct(e){var t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:Ie
return{StyleSheet:l({},it,{extend:function(n){var o=n.map((function(e){return e.selectorHandler})).filter((function(e){return e}))
return ct(e,t.concat(o))}}),StyleSheetServer:rt,StyleSheetTestUtils:at,minify:function(e){ot=e?w:tt},css:function(){for(var n=arguments.length,o=new Array(n),i=0;i<n;i++)o[i]=arguments[i]
return et(e,o,t)},flushToStyleTag:Ze,injectAndGetClassName:et,defaultSelectorHandlers:Ie,reset:We,resetInjectedStyle:qe}}var st=true
var lt=ct(st)
var dt=lt.StyleSheet,ut=lt.StyleSheetServer,xt=lt.StyleSheetTestUtils,_t=lt.css,mt=lt.minify,pt=lt.flushToStyleTag,ft=lt.injectAndGetClassName,ht=lt.defaultSelectorHandlers,yt=lt.reset,bt=lt.resetInjectedStyle},"/rex":function(e,t,n){"use strict"
n.d(t,"a",(function(){return i}))
const o="buttons_and_icons"
function i(e){let t
try{t=new URL(e)}catch(t){throw`Error parsing ${e}. 'buildButtonAndIconURL' only supports absolute URLs.`}t.searchParams.append(o,1)
return t.toString()}},"01jY":function(e,t,n){o=function(e,t){"use strict"
e=e&&e.hasOwnProperty("default")?e["default"]:e
t=t&&t.hasOwnProperty("default")?t["default"]:t
function n(e,t){return t={exports:{}},e(t,t.exports),t.exports}function o(e){return function(){return e}}var i=function(){}
i.thatReturns=o
i.thatReturnsFalse=o(false)
i.thatReturnsTrue=o(true)
i.thatReturnsNull=o(null)
i.thatReturnsThis=function(){return this}
i.thatReturnsArgument=function(e){return e}
var r=i
var a=function(e){}
a=function(e){if(void 0===e)throw new Error("invariant requires an error message argument")}
function c(e,t,n,o,i,r,c,s){a(t)
if(!e){var l
if(void 0===t)l=new Error("Minified exception occurred; use the non-minified dev environment for the full error message and additional helpful warnings.")
else{var d=[n,o,i,r,c,s]
var u=0
l=new Error(t.replace(/%s/g,(function(){return d[u++]})))
l.name="Invariant Violation"}l.framesToPop=1
throw l}}var s=c
var l=r
var d=function(e){for(var t=arguments.length,n=Array(t>1?t-1:0),o=1;o<t;o++)n[o-1]=arguments[o]
var i=0
var r="Warning: "+e.replace(/%s/g,(function(){return n[i++]}))
"undefined"!==typeof console&&console.error(r)
try{throw new Error(r)}catch(e){}}
l=function(e,t){if(void 0===t)throw new Error("`warning(condition, format, ...args)` requires a warning message argument")
if(0===t.indexOf("Failed Composite propType: "))return
if(!e){for(var n=arguments.length,o=Array(n>2?n-2:0),i=2;i<n;i++)o[i-2]=arguments[i]
d.apply(void 0,[t].concat(o))}}
var u=l
var x=Object.getOwnPropertySymbols
var _=Object.prototype.hasOwnProperty
var m=Object.prototype.propertyIsEnumerable
function p(e){if(null===e||void 0===e)throw new TypeError("Object.assign cannot be called with null or undefined")
return Object(e)}function f(){try{if(!Object.assign)return false
var e=new String("abc")
e[5]="de"
if("5"===Object.getOwnPropertyNames(e)[0])return false
var t={}
for(var n=0;n<10;n++)t["_"+String.fromCharCode(n)]=n
var o=Object.getOwnPropertyNames(t).map((function(e){return t[e]}))
if("0123456789"!==o.join(""))return false
var i={}
"abcdefghijklmnopqrst".split("").forEach((function(e){i[e]=e}))
if("abcdefghijklmnopqrst"!==Object.keys(Object.assign({},i)).join(""))return false
return true}catch(e){return false}}var h=f()?Object.assign:function(e,t){var n
var o=p(e)
var i
for(var r=1;r<arguments.length;r++){n=Object(arguments[r])
for(var a in n)_.call(n,a)&&(o[a]=n[a])
if(x){i=x(n)
for(var c=0;c<i.length;c++)m.call(n,i[c])&&(o[i[c]]=n[i[c]])}}return o}
var y="SECRET_DO_NOT_PASS_THIS_OR_YOU_WILL_BE_FIRED"
var b=y
var g=s
var v=u
var w=b
var k={}
function C(e,t,n,o,i){for(var r in e)if(e.hasOwnProperty(r)){var a
try{g("function"===typeof e[r],"%s: %s type `%s` is invalid; it must be a function, usually from the `prop-types` package, but received `%s`.",o||"React class",n,r,typeof e[r])
a=e[r](t,r,o,n,null,w)}catch(e){a=e}v(!a||a instanceof Error,"%s: type specification of %s `%s` is invalid; the type checker function must return `null` or an `Error` but returned a %s. You may have forgotten to pass an argument to the type checker creator (arrayOf, instanceOf, objectOf, oneOf, oneOfType, and shape all require an argument).",o||"React class",n,r,typeof a)
if(a instanceof Error&&!(a.message in k)){k[a.message]=true
var c=i?i():""
v(false,"Failed %s type: %s%s",n,a.message,null!=c?c:"")}}}var O=C
var E=function(e,t){var n="function"===typeof Symbol&&Symbol.iterator
var o="@@iterator"
function i(e){var t=e&&(n&&e[n]||e[o])
if("function"===typeof t)return t}var a="<<anonymous>>"
var c={array:_("array"),bool:_("boolean"),func:_("function"),number:_("number"),object:_("object"),string:_("string"),symbol:_("symbol"),any:m(),arrayOf:p,element:f(),instanceOf:y,node:k(),objectOf:v,oneOf:g,oneOfType:w,shape:C,exact:E}
function l(e,t){return e===t?0!==e||1/e===1/t:e!==e&&t!==t}function d(e){this.message=e
this.stack=""}d.prototype=Error.prototype
function x(e){var n={}
var o=0
function i(i,r,c,l,x,_,m){l=l||a
_=_||c
if(m!==b)if(t)s(false,"Calling PropTypes validators directly is not supported by the `prop-types` package. Use `PropTypes.checkPropTypes()` to call them. Read more at http://fb.me/use-check-prop-types")
else if("undefined"!==typeof console){var p=l+":"+c
if(!n[p]&&o<3){u(false,"You are manually calling a React.PropTypes validation function for the `%s` prop on `%s`. This is deprecated and will throw in the standalone `prop-types` package. You may be seeing this warning due to a third-party PropTypes library. See https://fb.me/react-warning-dont-call-proptypes for details.",_,l)
n[p]=true
o++}}if(null==r[c]){if(i){if(null===r[c])return new d("The "+x+" `"+_+"` is marked as required in `"+l+"`, but its value is `null`.")
return new d("The "+x+" `"+_+"` is marked as required in `"+l+"`, but its value is `undefined`.")}return null}return e(r,c,l,x,_)}var r=i.bind(null,false)
r.isRequired=i.bind(null,true)
return r}function _(e){function t(t,n,o,i,r,a){var c=t[n]
var s=j(c)
if(s!==e){var l=I(c)
return new d("Invalid "+i+" `"+r+"` of type `"+l+"` supplied to `"+o+"`, expected `"+e+"`.")}return null}return x(t)}function m(){return x(r.thatReturnsNull)}function p(e){function t(t,n,o,i,r){if("function"!==typeof e)return new d("Property `"+r+"` of component `"+o+"` has invalid PropType notation inside arrayOf.")
var a=t[n]
if(!Array.isArray(a)){var c=j(a)
return new d("Invalid "+i+" `"+r+"` of type `"+c+"` supplied to `"+o+"`, expected an array.")}for(var s=0;s<a.length;s++){var l=e(a,s,o,i,r+"["+s+"]",b)
if(l instanceof Error)return l}return null}return x(t)}function f(){function t(t,n,o,i,r){var a=t[n]
if(!e(a)){var c=j(a)
return new d("Invalid "+i+" `"+r+"` of type `"+c+"` supplied to `"+o+"`, expected a single ReactElement.")}return null}return x(t)}function y(e){function t(t,n,o,i,r){if(!(t[n]instanceof e)){var c=e.name||a
var s=L(t[n])
return new d("Invalid "+i+" `"+r+"` of type `"+s+"` supplied to `"+o+"`, expected instance of `"+c+"`.")}return null}return x(t)}function g(e){if(!Array.isArray(e)){u(false,"Invalid argument supplied to oneOf, expected an instance of array.")
return r.thatReturnsNull}function t(t,n,o,i,r){var a=t[n]
for(var c=0;c<e.length;c++)if(l(a,e[c]))return null
var s=JSON.stringify(e)
return new d("Invalid "+i+" `"+r+"` of value `"+a+"` supplied to `"+o+"`, expected one of "+s+".")}return x(t)}function v(e){function t(t,n,o,i,r){if("function"!==typeof e)return new d("Property `"+r+"` of component `"+o+"` has invalid PropType notation inside objectOf.")
var a=t[n]
var c=j(a)
if("object"!==c)return new d("Invalid "+i+" `"+r+"` of type `"+c+"` supplied to `"+o+"`, expected an object.")
for(var s in a)if(a.hasOwnProperty(s)){var l=e(a,s,o,i,r+"."+s,b)
if(l instanceof Error)return l}return null}return x(t)}function w(e){if(!Array.isArray(e)){u(false,"Invalid argument supplied to oneOfType, expected an instance of array.")
return r.thatReturnsNull}for(var t=0;t<e.length;t++){var n=e[t]
if("function"!==typeof n){u(false,"Invalid argument supplied to oneOfType. Expected an array of check functions, but received %s at index %s.",T(n),t)
return r.thatReturnsNull}}function o(t,n,o,i,r){for(var a=0;a<e.length;a++){var c=e[a]
if(null==c(t,n,o,i,r,b))return null}return new d("Invalid "+i+" `"+r+"` supplied to `"+o+"`.")}return x(o)}function k(){function e(e,t,n,o,i){if(!A(e[t]))return new d("Invalid "+o+" `"+i+"` supplied to `"+n+"`, expected a ReactNode.")
return null}return x(e)}function C(e){function t(t,n,o,i,r){var a=t[n]
var c=j(a)
if("object"!==c)return new d("Invalid "+i+" `"+r+"` of type `"+c+"` supplied to `"+o+"`, expected `object`.")
for(var s in e){var l=e[s]
if(!l)continue
var u=l(a,s,o,i,r+"."+s,b)
if(u)return u}return null}return x(t)}function E(e){function t(t,n,o,i,r){var a=t[n]
var c=j(a)
if("object"!==c)return new d("Invalid "+i+" `"+r+"` of type `"+c+"` supplied to `"+o+"`, expected `object`.")
var s=h({},t[n],e)
for(var l in s){var u=e[l]
if(!u)return new d("Invalid "+i+" `"+r+"` key `"+l+"` supplied to `"+o+"`.\nBad object: "+JSON.stringify(t[n],null,"  ")+"\nValid keys: "+JSON.stringify(Object.keys(e),null,"  "))
var x=u(a,l,o,i,r+"."+l,b)
if(x)return x}return null}return x(t)}function A(t){switch(typeof t){case"number":case"string":case"undefined":return true
case"boolean":return!t
case"object":if(Array.isArray(t))return t.every(A)
if(null===t||e(t))return true
var n=i(t)
if(!n)return false
var o=n.call(t)
var r
if(n!==t.entries){while(!(r=o.next()).done)if(!A(r.value))return false}else while(!(r=o.next()).done){var a=r.value
if(a&&!A(a[1]))return false}return true
default:return false}}function S(e,t){if("symbol"===e)return true
if("Symbol"===t["@@toStringTag"])return true
if("function"===typeof Symbol&&t instanceof Symbol)return true
return false}function j(e){var t=typeof e
if(Array.isArray(e))return"array"
if(e instanceof RegExp)return"object"
if(S(t,e))return"symbol"
return t}function I(e){if("undefined"===typeof e||null===e)return""+e
var t=j(e)
if("object"===t){if(e instanceof Date)return"date"
if(e instanceof RegExp)return"regexp"}return t}function T(e){var t=I(e)
switch(t){case"array":case"object":return"an "+t
case"boolean":case"date":case"regexp":return"a "+t
default:return t}}function L(e){if(!e.constructor||!e.constructor.name)return a
return e.constructor.name}c.checkPropTypes=O
c.PropTypes=c
return c}
var A=n((function(e){var t="function"===typeof Symbol&&Symbol.for&&Symbol.for("react.element")||60103
var n=function(e){return"object"===typeof e&&null!==e&&e.$$typeof===t}
var o=true
e.exports=E(n,o)}))
var S=n((function(e){(function(){var t={}.hasOwnProperty
function n(){var e=[]
for(var o=0;o<arguments.length;o++){var i=arguments[o]
if(!i)continue
var r=typeof i
if("string"===r||"number"===r)e.push(i)
else if(Array.isArray(i))e.push(n.apply(null,i))
else if("object"===r)for(var a in i)t.call(i,a)&&i[a]&&e.push(a)}return e.join(" ")}e.exports?e.exports=n:window.classNames=n})()}))
function j(e,t){for(var n=0,o=e.length;n<o;n++)if(t.apply(t,[e[n],n,e]))return e[n]}function I(e){return"function"===typeof e||"[object Function]"===Object.prototype.toString.call(e)}function T(e){return"number"===typeof e&&!isNaN(e)}function L(e){return parseInt(e,10)}function B(e,t,n){if(e[t])return new Error("Invalid prop "+t+" passed to "+n+" - do not set this, set it on the child.")}var D=["Moz","Webkit","O","ms"]
function R(){var e=arguments.length>0&&void 0!==arguments[0]?arguments[0]:"transform"
if("undefined"===typeof window||"undefined"===typeof window.document)return""
var t=window.document.documentElement.style
if(e in t)return""
for(var n=0;n<D.length;n++)if(F(e,D[n])in t)return D[n]
return""}function F(e,t){return t?""+t+M(e):e}function M(e){var t=""
var n=true
for(var o=0;o<e.length;o++)if(n){t+=e[o].toUpperCase()
n=false}else"-"===e[o]?n=true:t+=e[o]
return t}var z=R()
var P=function(e,t){if(!(e instanceof t))throw new TypeError("Cannot call a class as a function")}
var N=function(){function e(e,t){for(var n=0;n<t.length;n++){var o=t[n]
o.enumerable=o.enumerable||false
o.configurable=true
"value"in o&&(o.writable=true)
Object.defineProperty(e,o.key,o)}}return function(t,n,o){n&&e(t.prototype,n)
o&&e(t,o)
return t}}()
var U=function(e,t,n){t in e?Object.defineProperty(e,t,{value:n,enumerable:true,configurable:true,writable:true}):e[t]=n
return e}
var $=Object.assign||function(e){for(var t=1;t<arguments.length;t++){var n=arguments[t]
for(var o in n)Object.prototype.hasOwnProperty.call(n,o)&&(e[o]=n[o])}return e}
var H=function(e,t){if("function"!==typeof t&&null!==t)throw new TypeError("Super expression must either be null or a function, not "+typeof t)
e.prototype=Object.create(t&&t.prototype,{constructor:{value:e,enumerable:false,writable:true,configurable:true}})
t&&(Object.setPrototypeOf?Object.setPrototypeOf(e,t):e.__proto__=t)}
var W=function(e,t){if(!e)throw new ReferenceError("this hasn't been initialised - super() hasn't been called")
return!t||"object"!==typeof t&&"function"!==typeof t?e:t}
var q=function(){function e(e,t){var n=[]
var o=true
var i=false
var r=void 0
try{for(var a,c=e[Symbol.iterator]();!(o=(a=c.next()).done);o=true){n.push(a.value)
if(t&&n.length===t)break}}catch(e){i=true
r=e}finally{try{!o&&c["return"]&&c["return"]()}finally{if(i)throw r}}return n}return function(t,n){if(Array.isArray(t))return t
if(Symbol.iterator in Object(t))return e(t,n)
throw new TypeError("Invalid attempt to destructure non-iterable instance")}}()
var V=""
function G(e,t){V||(V=j(["matches","webkitMatchesSelector","mozMatchesSelector","msMatchesSelector","oMatchesSelector"],(function(t){return I(e[t])})))
if(!I(e[V]))return false
return e[V](t)}function K(e,t,n){var o=e
do{if(G(o,t))return true
if(o===n)return false
o=o.parentNode}while(o)
return false}function Z(e,t,n){if(!e)return
e.attachEvent?e.attachEvent("on"+t,n):e.addEventListener?e.addEventListener(t,n,true):e["on"+t]=n}function Y(e,t,n){if(!e)return
e.detachEvent?e.detachEvent("on"+t,n):e.removeEventListener?e.removeEventListener(t,n,true):e["on"+t]=null}function J(e){var t=e.clientHeight
var n=e.ownerDocument.defaultView.getComputedStyle(e)
t+=L(n.borderTopWidth)
t+=L(n.borderBottomWidth)
return t}function X(e){var t=e.clientWidth
var n=e.ownerDocument.defaultView.getComputedStyle(e)
t+=L(n.borderLeftWidth)
t+=L(n.borderRightWidth)
return t}function Q(e){var t=e.clientHeight
var n=e.ownerDocument.defaultView.getComputedStyle(e)
t-=L(n.paddingTop)
t-=L(n.paddingBottom)
return t}function ee(e){var t=e.clientWidth
var n=e.ownerDocument.defaultView.getComputedStyle(e)
t-=L(n.paddingLeft)
t-=L(n.paddingRight)
return t}function te(e,t){var n=t===t.ownerDocument.body
var o=n?{left:0,top:0}:t.getBoundingClientRect()
var i=e.clientX+t.scrollLeft-o.left
var r=e.clientY+t.scrollTop-o.top
return{x:i,y:r}}function ne(e,t){var n=ie(e,t,"px")
return U({},F("transform",z),n)}function oe(e,t){var n=ie(e,t,"")
return n}function ie(e,t,n){var o=e.x,i=e.y
var r="translate("+o+n+","+i+n+")"
if(t){var a=""+("string"===typeof t.x?t.x:t.x+n)
var c=""+("string"===typeof t.y?t.y:t.y+n)
r="translate("+a+", "+c+")"+r}return r}function re(e,t){return e.targetTouches&&j(e.targetTouches,(function(e){return t===e.identifier}))||e.changedTouches&&j(e.changedTouches,(function(e){return t===e.identifier}))}function ae(e){if(e.targetTouches&&e.targetTouches[0])return e.targetTouches[0].identifier
if(e.changedTouches&&e.changedTouches[0])return e.changedTouches[0].identifier}function ce(e){if(!e)return
var t=e.getElementById("react-draggable-style-el")
if(!t){t=e.createElement("style")
t.type="text/css"
t.id="react-draggable-style-el"
t.innerHTML=".react-draggable-transparent-selection *::-moz-selection {all: inherit;}\n"
t.innerHTML+=".react-draggable-transparent-selection *::selection {all: inherit;}\n"
e.getElementsByTagName("head")[0].appendChild(t)}e.body&&de(e.body,"react-draggable-transparent-selection")}function se(e){try{e&&e.body&&ue(e.body,"react-draggable-transparent-selection")
e.selection?e.selection.empty():window.getSelection().removeAllRanges()}catch(e){}}function le(){var e=arguments.length>0&&void 0!==arguments[0]?arguments[0]:{}
return $({touchAction:"none"},e)}function de(e,t){e.classList?e.classList.add(t):e.className.match(new RegExp("(?:^|\\s)"+t+"(?!\\S)"))||(e.className+=" "+t)}function ue(e,t){e.classList?e.classList.remove(t):e.className=e.className.replace(new RegExp("(?:^|\\s)"+t+"(?!\\S)","g"),"")}function xe(e,t,n){if(!e.props.bounds)return[t,n]
var o=e.props.bounds
o="string"===typeof o?o:be(o)
var i=ge(e)
if("string"===typeof o){var r=i.ownerDocument
var a=r.defaultView
var c=void 0
c="parent"===o?i.parentNode:r.querySelector(o)
if(!(c instanceof a.HTMLElement))throw new Error('Bounds selector "'+o+'" could not find an element.')
var s=a.getComputedStyle(i)
var l=a.getComputedStyle(c)
o={left:-i.offsetLeft+L(l.paddingLeft)+L(s.marginLeft),top:-i.offsetTop+L(l.paddingTop)+L(s.marginTop),right:ee(c)-X(i)-i.offsetLeft+L(l.paddingRight)-L(s.marginRight),bottom:Q(c)-J(i)-i.offsetTop+L(l.paddingBottom)-L(s.marginBottom)}}T(o.right)&&(t=Math.min(t,o.right))
T(o.bottom)&&(n=Math.min(n,o.bottom))
T(o.left)&&(t=Math.max(t,o.left))
T(o.top)&&(n=Math.max(n,o.top))
return[t,n]}function _e(e,t,n){var o=Math.round(t/e[0])*e[0]
var i=Math.round(n/e[1])*e[1]
return[o,i]}function me(e){return"both"===e.props.axis||"x"===e.props.axis}function pe(e){return"both"===e.props.axis||"y"===e.props.axis}function fe(e,t,n){var o="number"===typeof t?re(e,t):null
if("number"===typeof t&&!o)return null
var i=ge(n)
var r=n.props.offsetParent||i.offsetParent||i.ownerDocument.body
return te(o||e,r)}function he(e,t,n){var o=e.state
var i=!T(o.lastX)
var r=ge(e)
return i?{node:r,deltaX:0,deltaY:0,lastX:t,lastY:n,x:t,y:n}:{node:r,deltaX:t-o.lastX,deltaY:n-o.lastY,lastX:o.lastX,lastY:o.lastY,x:t,y:n}}function ye(e,t){var n=e.props.scale
return{node:t.node,x:e.state.x+t.deltaX/n,y:e.state.y+t.deltaY/n,deltaX:t.deltaX/n,deltaY:t.deltaY/n,lastX:e.state.x,lastY:e.state.y}}function be(e){return{left:e.left,top:e.top,right:e.right,bottom:e.bottom}}function ge(t){var n=e.findDOMNode(t)
if(!n)throw new Error("<DraggableCore>: Unmounted during event!")
return n}function ve(){}var we={touch:{start:"touchstart",move:"touchmove",stop:"touchend"},mouse:{start:"mousedown",move:"mousemove",stop:"mouseup"}}
var ke=we.mouse
var Ce=function(n){H(o,n)
function o(){var t
var n,i,r
P(this,o)
for(var a=arguments.length,c=Array(a),s=0;s<a;s++)c[s]=arguments[s]
return r=(n=(i=W(this,(t=o.__proto__||Object.getPrototypeOf(o)).call.apply(t,[this].concat(c))),i),i.state={dragging:false,lastX:NaN,lastY:NaN,touchIdentifier:null},i.handleDragStart=function(t){i.props.onMouseDown(t)
if(!i.props.allowAnyClick&&"number"===typeof t.button&&0!==t.button)return false
var n=e.findDOMNode(i)
if(!n||!n.ownerDocument||!n.ownerDocument.body)throw new Error("<DraggableCore> not mounted on DragStart!")
var o=n.ownerDocument
if(i.props.disabled||!(t.target instanceof o.defaultView.Node)||i.props.handle&&!K(t.target,i.props.handle,n)||i.props.cancel&&K(t.target,i.props.cancel,n))return
var r=ae(t)
i.setState({touchIdentifier:r})
var a=fe(t,r,i)
if(null==a)return
var c=a.x,s=a.y
var l=he(i,c,s)
ve("calling",i.props.onStart)
var d=i.props.onStart(t,l)
if(false===d)return
i.props.enableUserSelectHack&&ce(o)
i.setState({dragging:true,lastX:c,lastY:s})
Z(o,ke.move,i.handleDrag)
Z(o,ke.stop,i.handleDragStop)},i.handleDrag=function(e){"touchmove"===e.type&&e.preventDefault()
var t=fe(e,i.state.touchIdentifier,i)
if(null==t)return
var n=t.x,o=t.y
if(Array.isArray(i.props.grid)){var r=n-i.state.lastX,a=o-i.state.lastY
var c=_e(i.props.grid,r,a)
var s=q(c,2)
r=s[0]
a=s[1]
if(!r&&!a)return
n=i.state.lastX+r,o=i.state.lastY+a}var l=he(i,n,o)
var d=i.props.onDrag(e,l)
if(false===d){try{i.handleDragStop(new MouseEvent("mouseup"))}catch(e){var u=document.createEvent("MouseEvents")
u.initMouseEvent("mouseup",true,true,window,0,0,0,0,0,false,false,false,false,0,null)
i.handleDragStop(u)}return}i.setState({lastX:n,lastY:o})},i.handleDragStop=function(t){if(!i.state.dragging)return
var n=fe(t,i.state.touchIdentifier,i)
if(null==n)return
var o=n.x,r=n.y
var a=he(i,o,r)
var c=e.findDOMNode(i)
c&&i.props.enableUserSelectHack&&se(c.ownerDocument)
i.setState({dragging:false,lastX:NaN,lastY:NaN})
i.props.onStop(t,a)
if(c){Y(c.ownerDocument,ke.move,i.handleDrag)
Y(c.ownerDocument,ke.stop,i.handleDragStop)}},i.onMouseDown=function(e){ke=we.mouse
return i.handleDragStart(e)},i.onMouseUp=function(e){ke=we.mouse
return i.handleDragStop(e)},i.onTouchStart=function(e){ke=we.touch
return i.handleDragStart(e)},i.onTouchEnd=function(e){ke=we.touch
return i.handleDragStop(e)},n),W(i,r)}N(o,[{key:"componentWillUnmount",value:function(){var t=e.findDOMNode(this)
if(t){var n=t.ownerDocument
Y(n,we.mouse.move,this.handleDrag)
Y(n,we.touch.move,this.handleDrag)
Y(n,we.mouse.stop,this.handleDragStop)
Y(n,we.touch.stop,this.handleDragStop)
this.props.enableUserSelectHack&&se(n)}}},{key:"render",value:function(){return t.cloneElement(t.Children.only(this.props.children),{style:le(this.props.children.props.style),onMouseDown:this.onMouseDown,onTouchStart:this.onTouchStart,onMouseUp:this.onMouseUp,onTouchEnd:this.onTouchEnd})}}])
return o}(t.Component)
Ce.displayName="DraggableCore"
Ce.propTypes={allowAnyClick:A.bool,disabled:A.bool,enableUserSelectHack:A.bool,offsetParent:function(e,t){if(e[t]&&1!==e[t].nodeType)throw new Error("Draggable's offsetParent must be a DOM Node.")},grid:A.arrayOf(A.number),scale:A.number,handle:A.string,cancel:A.string,onStart:A.func,onDrag:A.func,onStop:A.func,onMouseDown:A.func,className:B,style:B,transform:B}
Ce.defaultProps={allowAnyClick:false,cancel:null,disabled:false,enableUserSelectHack:true,offsetParent:null,handle:null,grid:null,transform:null,onStart:function(){},onDrag:function(){},onStop:function(){},onMouseDown:function(){}}
var Oe=function(n){H(o,n)
function o(e){P(this,o)
var t=W(this,(o.__proto__||Object.getPrototypeOf(o)).call(this,e))
t.onDragStart=function(e,n){var o=t.props.onStart(e,ye(t,n))
if(false===o)return false
t.setState({dragging:true,dragged:true})}
t.onDrag=function(e,n){if(!t.state.dragging)return false
var o=ye(t,n)
var i={x:o.x,y:o.y}
if(t.props.bounds){var r=i.x,a=i.y
i.x+=t.state.slackX
i.y+=t.state.slackY
var c=xe(t,i.x,i.y),s=q(c,2),l=s[0],d=s[1]
i.x=l
i.y=d
i.slackX=t.state.slackX+(r-i.x)
i.slackY=t.state.slackY+(a-i.y)
o.x=i.x
o.y=i.y
o.deltaX=i.x-t.state.x
o.deltaY=i.y-t.state.y}var u=t.props.onDrag(e,o)
if(false===u)return false
t.setState(i)}
t.onDragStop=function(e,n){if(!t.state.dragging)return false
var o=t.props.onStop(e,ye(t,n))
if(false===o)return false
var i={dragging:false,slackX:0,slackY:0}
var r=Boolean(t.props.position)
if(r){var a=t.props.position,c=a.x,s=a.y
i.x=c
i.y=s}t.setState(i)}
t.state={dragging:false,dragged:false,x:e.position?e.position.x:e.defaultPosition.x,y:e.position?e.position.y:e.defaultPosition.y,slackX:0,slackY:0,isElementSVG:false}
e.position&&!(e.onDrag||e.onStop)&&console.warn("A `position` was applied to this <Draggable>, without drag handlers. This will make this component effectively undraggable. Please attach `onDrag` or `onStop` handlers so you can adjust the `position` of this element.")
return t}N(o,[{key:"componentDidMount",value:function(){"undefined"!==typeof window.SVGElement&&e.findDOMNode(this)instanceof window.SVGElement&&this.setState({isElementSVG:true})}},{key:"componentWillReceiveProps",value:function(e){!e.position||this.props.position&&e.position.x===this.props.position.x&&e.position.y===this.props.position.y||this.setState({x:e.position.x,y:e.position.y})}},{key:"componentWillUnmount",value:function(){this.setState({dragging:false})}},{key:"render",value:function(){var e
var n={},o=null
var i=Boolean(this.props.position)
var r=!i||this.state.dragging
var a=this.props.position||this.props.defaultPosition
var c={x:me(this)&&r?this.state.x:a.x,y:pe(this)&&r?this.state.y:a.y}
this.state.isElementSVG?o=oe(c,this.props.positionOffset):n=ne(c,this.props.positionOffset)
var s=this.props,l=s.defaultClassName,d=s.defaultClassNameDragging,u=s.defaultClassNameDragged
var x=t.Children.only(this.props.children)
var _=S(x.props.className||"",l,(e={},U(e,d,this.state.dragging),U(e,u,this.state.dragged),e))
return t.createElement(Ce,$({},this.props,{onStart:this.onDragStart,onDrag:this.onDrag,onStop:this.onDragStop}),t.cloneElement(x,{className:_,style:$({},x.props.style,n),transform:o}))}}])
return o}(t.Component)
Oe.displayName="Draggable"
Oe.propTypes=$({},Ce.propTypes,{axis:A.oneOf(["both","x","y","none"]),bounds:A.oneOfType([A.shape({left:A.number,right:A.number,top:A.number,bottom:A.number}),A.string,A.oneOf([false])]),defaultClassName:A.string,defaultClassNameDragging:A.string,defaultClassNameDragged:A.string,defaultPosition:A.shape({x:A.number,y:A.number}),positionOffset:A.shape({x:A.oneOfType([A.number,A.string]),y:A.oneOfType([A.number,A.string])}),position:A.shape({x:A.number,y:A.number}),className:B,style:B,transform:B})
Oe.defaultProps=$({},Ce.defaultProps,{axis:"both",bounds:false,defaultClassName:"react-draggable",defaultClassNameDragging:"react-draggable-dragging",defaultClassNameDragged:"react-draggable-dragged",defaultPosition:{x:0,y:0},position:null,scale:1})
Oe.default=Oe
Oe.DraggableCore=Ce
return Oe},e.exports=o(n("i8i4"),n("q1tI"))
var o},"0T/Z":function(e,t,n){"use strict"
n.d(t,"a",(function(){return r}))
const o={"ar-SA":"ar","da-DK":"da","de-DE":"de","en-US":"en","es-ES":"es",fa:"fa-IR","fr-FR":"fr","he-IL":"he","hy-AM":"hy","ja-JP":"ja","ko-KR":"ko","mi-NZ":"mi","nb-NO":"nb","nl-NL":"nl","pl-PL":"pl","pt-PT":"pt","ru-RU":"ru","sv-SE":"sv","tr-TR":"tr",uk:"uk-UA","zh-CN":"zh-Hans","zh-HK":"zh-Hant"}
const i=["ar","bg","ca","cs","cy","da","da-x-k12","de","el","en","en-AU","en-AU-x-unimelb","en-GB","en-GB-x-lbs","en-GB-x-ukhe","es","es-ES","fa-IR","fi","fr","fr-CA","he","ht","hu","hy","is","it","ja","ko","mi","nb","nb-x-k12","nl","nn","pl","pt","pt-BR","ro","ru","sq","sr","sl","sv","sv-x-k12","th","tr","vi","zh-Hans","zh-Hant"]
function r(e){if(e){if(i.indexOf(e)>=0)return e
if(o[e])return o[e]
if(e.match("-x-")){e=e.split("-x-")[0]
return r(e)}return"en"}return"en"}},"0k/6":function(e,t,n){"use strict"
n.d(t,"a",(function(){return a}))
n.d(t,"b",(function(){return c}))
n.d(t,"c",(function(){return s}))
n.d(t,"d",(function(){return d}))
var o=n("NFDp")
const i="inst-button-and-icons-edit"
const r="inst-button-and-icons-edit-toolbar"
const a="data-inst-buttons-and-icons"
const c="data-download-url"
const s="buttons_and_icons"
const l=e=>!!(null!==e&&void 0!==e&&e.getAttribute(a))
function d(e,t){u(e,t)
x(e)}function u(e,t){e.ui.registry.addButton(i,{onAction:t,text:Object(o["a"])("Edit"),tooltip:Object(o["a"])("Edit Existing Button / Icon")})}function x(e){e.ui.registry.addContextToolbar(r,{items:i,position:"node",scope:"node",predicate:l})}},"1pz7":function(e,t,n){"use strict"
n.d(t,"a",(function(){return x}))
var o=n("VTBJ")
var i=n("1OyB")
var r=n("vuIU")
var a=n("Ji7U")
var c=n("LK+K")
var s=n("q1tI")
var l=n.n(s)
var d=n("hPGw")
var u=l.a.createElement("path",{d:"M1420.81129,1342.11624 C1450.74071,1297.39153 1468.24659,1243.63153 1468.24659,1185.91859 C1468.24659,1049.59859 1371.11718,935.528 1242.36424,909.325647 L1242.36424,1169.99388 L1420.81129,1342.11624 Z M903.540706,1185.91859 C903.540706,1341.66447 1030.14776,1468.27153 1185.89365,1468.27153 C1243.04188,1468.27153 1296.12424,1450.99153 1340.62306,1421.62682 L1129.42306,1217.99388 L1129.42306,909.325647 C1000.67012,935.528 903.540706,1049.59859 903.540706,1185.91859 Z M1185.89365,790.624471 C1403.87012,790.624471 1581.18776,967.942118 1581.18776,1185.91859 C1581.18776,1403.89506 1403.87012,1581.21271 1185.89365,1581.21271 C967.917176,1581.21271 790.599529,1403.89506 790.599529,1185.91859 C790.599529,967.942118 967.917176,790.624471 1185.89365,790.624471 Z M1355.29412,225.941176 L1355.29412,677.705882 L1807.05882,677.705882 L1807.05882,1694.17647 L112.941176,1694.17647 L112.941176,225.941176 L1355.29412,225.941176 Z M677.647059,677.705882 L338.823529,677.705882 L338.823529,790.647059 L677.647059,790.647059 L677.647059,677.705882 Z M1016.47059,451.823529 L1016.47059,564.764706 L338.823529,564.764706 L338.823529,451.823529 L1016.47059,451.823529 Z M1468.23529,249.32 L1783.68,564.764706 L1468.23529,564.764706 L1468.23529,249.32 Z M1870.41882,491.804706 L1541.19529,162.581176 C1509.68471,131.070588 1465.97647,113 1421.47765,113 L0,113 L0,1807.11765 L1920,1807.11765 L1920,611.522353 C1920,566.345882 1902.38118,523.767059 1870.41882,491.804706 L1870.41882,491.804706 Z",fillRule:"evenodd",stroke:"none",strokeWidth:"1"})
var x=function(e){Object(a["a"])(n,e)
var t=Object(c["a"])(n)
function n(){Object(i["a"])(this,n)
return t.apply(this,arguments)}Object(r["a"])(n,[{key:"render",value:function(){return l.a.createElement(d["a"],Object.assign({},this.props,{name:"IconMsPpt",viewBox:"0 0 1920 1920"}),u)}}])
n.displayName="IconMsPptLine"
return n}(s["Component"])
x.glyphName="ms-ppt"
x.variant="Line"
x.propTypes=Object(o["a"])({},d["a"].propTypes)},"20cW":function(e,t){const n={ar:"ar_SA",bg:"bg_BG",ca:"ca",cs:"cs",cy:"cy",da:"da",de:"de",el:"el",en:void 0,"en-AU":"en_GB","en-GB":"en_GB",es:"es","es-ES":"es",fa:"fa_IR","fa-IR":"fa_IR",fi:"fi",fr:"fr_FR","fr-CA":"fr_FR",he:"he_IL",ht:void 0,hu:"hu_HU",hy:"hy",is:void 0,it:"it",ja:"ja",ko:"ko_KR",mi:void 0,nb:"nb_NO",nl:"nl",nn:"nb_NO",pl:"pl",pt:"pt_PT","pt-BR":"pt_BR",ro:"ro",ru:"ru",sq:void 0,sr:"sr",sl:"sl",sv:"sv_SE",th:"th",tr:"tr_TR","uk-UA":"uk_UA",uk:"uk_UA",vi:"vi_VN",zh:"zh_CN","zh-HK":"zh_TW","zh-Hans":"zh_CN","zh-Hant":"zh_TW"}
function o(e){if(!e)return n.en
e.match("_")&&(e=e.replace("_","-"))
e.match("-x-")&&(e=e.split("-x-")[0])
return n[e]}e.exports=o},"3Sge":function(e,t,n){"use strict"
n.d(t,"a",(function(){return x}))
var o=n("VTBJ")
var i=n("1OyB")
var r=n("vuIU")
var a=n("Ji7U")
var c=n("LK+K")
var s=n("q1tI")
var l=n.n(s)
var d=n("hPGw")
var u=l.a.createElement("path",{d:"M954.63973 826.4177L426.666667 298.444637 298.444637 426.666667 826.4177 954.63973 298.444637 1482.61279 426.666667 1610.83482 954.63973 1082.86176 1482.61279 1610.83482 1610.83482 1482.61279 1082.86176 954.63973 1610.83482 426.666667 1482.61279 298.444637z",fillRule:"nonzero",stroke:"none",strokeWidth:"1"})
var x=function(e){Object(a["a"])(n,e)
var t=Object(c["a"])(n)
function n(){Object(i["a"])(this,n)
return t.apply(this,arguments)}Object(r["a"])(n,[{key:"render",value:function(){return l.a.createElement(d["a"],Object.assign({},this.props,{name:"IconX",viewBox:"0 0 1920 1920"}),u)}}])
n.displayName="IconXLine"
return n}(s["Component"])
x.glyphName="x"
x.variant="Line"
x.propTypes=Object(o["a"])({},d["a"].propTypes)},"4LsN":function(e,t,n){"use strict"
n.r(t)
n.d(t,"default",(function(){return j}))
var o=n("q1tI")
var i=n.n(o)
var r=n("17x9")
var a=n("/HcR")
var c=n.n(a)
var s=n("L+/K")
var l=n("Zgll")
var d=n("RqKb")
var u=n("n12J")
var x=n("Xx/m")
var _=n("TstA")
var m=n("xHhu")
var p=n("6SzX")
var f=n("ZbPE")
var h=n("Ff2n")
var y=n("LvDl")
var b=n("Oioo")
var g=n("4Awi")
const v=["id","label","value","onChange","children","noOptionsLabel","liveRegion"],w=["id","children"],k=["id","label"]
const C="_noOptionsOption"
function O(){return i.a.createElement("div",null)}O.propTypes={id:r["string"].isRequired,value:r["string"].isRequired}
function E(){return i.a.createElement("div",null)}E.propTypes={label:r["string"].isRequired}
class A extends i.a.Component{constructor(e){super(e)
this.backupKey=0
this.handleBlur=e=>{this.setState({highlightedOptionId:null,announcement:null})
this.props.onBlur&&this.props.onBlur(e)}
this.handleShowOptions=()=>{this.setState({isShowingOptions:true})}
this.handleHideOptions=e=>{this.setState(e=>{const t=this.getOptionLabelById(e.selectedOptionId)
return{isShowingOptions:false,highlightedOptionId:null,inputValue:t}})}
this.handleHighlightOption=(e,{id:t})=>{if(t===C)return
const n=this.getOptionLabelById(t)
const o=this.state.isShowingOptions?"":this.props.translatedStrings.LIST_EXPANDED
const i="keydown"===e.type?n:this.state.inputValue
this.setState({highlightedOptionId:t,inputValue:i,announcement:`${n} ${o}`})}
this.handleSelectOption=(e,{id:t})=>{if(t===C)this.setState({isShowingOptions:false,announcement:this.props.translatedStrings.LIST_COLLAPSED})
else{const n=this.getOptionLabelById(t)
const o=this.state.selectedOptionId
this.setState({selectedOptionId:t,inputValue:n,isShowingOptions:false,announcement:c()(this.props.translatedStrings.OPTION_SELECTED,{option:n})})
const i=this.getOptionByFieldValue("id",t)
o!==t&&this.props.onChange(e,i.props.value)}}
const t=this.getOptionByFieldValue("value",e.value)
this.state={inputValue:t?t.props.children:"",isShowingOptions:false,highlightedOptionId:null,selectedOptionId:t?t.props.id:null,announcement:null}
this._selectRef=i.a.createRef()}focus(){var e
null===(e=this._selectRef.current)||void 0===e||e.focus()}componentDidUpdate(e){if(this.props.value!==e.value||!Object(y["isEqual"])(this.props.children,e.children)){const e=this.getOptionByFieldValue("value",this.props.value)
this.setState({inputValue:e?e.props.children:"",selectedOptionId:e?e.props.id:""})}}render(){const e=this.props,t=e.id,n=e.label,o=(e.value,e.onChange,e.children),r=(e.noOptionsLabel,e.liveRegion),a=Object(h["a"])(e,v)
return i.a.createElement(i.a.Fragment,null,i.a.createElement(b["a"],Object.assign({ref:this._selectRef,id:t,renderLabel:()=>n,assistiveText:this.props.translatedStrings.USE_ARROWS,inputValue:this.state.inputValue,isShowingOptions:this.state.isShowingOptions,onBlur:this.handleBlur,onRequestShowOptions:this.handleShowOptions,onRequestHideOptions:this.handleHideOptions,onRequestHighlightOption:this.handleHighlightOption,onRequestSelectOption:this.handleSelectOption},a),this.renderChildren(o)),i.a.createElement(s["a"],{liveRegion:r,liveRegionPoliteness:"assertive",screenReaderOnly:true},this.state.announcement))}renderChildren(e){if(!Array.isArray(e))return Object(g["a"])(e,[O])?this.renderOption(e):Object(g["a"])(e,[E])?this.renderGroup(e):this.renderNoOptionsOption()
const t=e.map(e=>{if(Array.isArray(e))return this.renderChildren(e)
if(Object(g["a"])(e,[O]))return this.renderOption(e)
if(Object(g["a"])(e,[E]))return this.renderGroup(e)
return null}).filter(e=>!!e)
if(0===t.length)return this.renderNoOptionsOption()
return t}renderOption(e){const t=e.props,n=t.id,o=t.children,r=Object(h["a"])(t,w)
return i.a.createElement(b["a"].Option,Object.assign({id:n,key:e.key||n||++this.backupKey,isHighlighted:n===this.state.highlightedOptionId,isSelected:n===this.state.selectedOptionId},r),o)}renderGroup(e){const t=e.props,n=t.id,o=t.label,r=Object(h["a"])(t,k)
const a=Object(y["compact"])(Object(y["castArray"])(e.props.children))
return i.a.createElement(b["a"].Group,Object.assign({"data-testid":"Group:"+o,renderLabel:()=>o,key:e.key||n||++this.backupKey},r),a.map(e=>this.renderOption(e)))}renderNoOptionsOption(){return i.a.createElement(b["a"].Option,{id:C,isHighlighted:false,isSelected:false},this.props.noOptionsLabel)}getOptionLabelById(e){const t=this.getOptionByFieldValue("id",e)
return t?t.props.children:""}getOptionByFieldValue(e,t,n=Object(y["castArray"])(this.props.children)){if(!this.props.children)return null
let o=null
for(let i=0;i<n.length;++i){const r=n[i]
if(Array.isArray(r))o=this.getOptionByFieldValue(e,t,r)
else if(Object(g["a"])(r,[O]))r.props[e]===t&&(o=r)
else if(Object(g["a"])(r,[E])){const n=Object(y["castArray"])(r.props.children)
for(let i=0;i<n.length;++i){const r=n[i]
if(r.props[e]===t){o=r
break}}}if(o)break}return o}}A.Option=O
A.Group=E
A.propTypes={id:r["string"],label:Object(r["oneOfType"])([r["node"],r["func"]]).isRequired,liveRegion:r["func"],value:r["string"],onChange:r["func"].isRequired,children:r["node"],noOptionsLabel:r["string"],translatedStrings:Object(r["shape"])({USE_ARROWS:r["string"].isRequired,LIST_COLLAPSED:r["string"].isRequired,LIST_EXPANDED:r["string"].isRequired,OPTION_SELECTED:r["string"].isRequired}),onBlur:r["func"]}
A.defaultProps={noOptionsLabel:"---"}
class S extends o["Component"]{constructor(...e){super(...e)
this._langSelectRef=i.a.createRef()
this._deleteCCBtnRef=i.a.createRef()
this.handleLanguageChange=(e,t)=>{this.props.onLanguageSelected(this.props.languages.find(e=>e.id===t))}
this.handleDeleteRow=e=>{this.props.onDeleteRow(this.props.selectedLanguage.id)}}get isReadonly(){return this.props.selectedFile&&this.props.selectedLanguage}focus(){this._langSelectRef.current?this._langSelectRef.current.focus():this._deleteCCBtnRef.current&&this._deleteCCBtnRef.current.focus()}renderChoosing(){return i.a.createElement(_["a"],{as:"div",wrap:"wrap",justifyItems:"start",alignItems:"end","data-testid":"CC-CreatorRow-choosing"},this.renderSelectLanguage(),this.renderChooseFile())}renderSelectLanguage(){var e
const t=this.props.uploadMediaTranslations.UploadMediaStrings.CLOSED_CAPTIONS_SELECT_LANGUAGE
return i.a.createElement(_["a"].Item,{margin:"0 small small 0"},i.a.createElement(A,{ref:this._langSelectRef,value:null===(e=this.props.selectedLanguage)||void 0===e?void 0:e.id,label:i.a.createElement(p["a"],null,t),liveRegion:this.props.liveRegion,onChange:this.handleLanguageChange,placeholder:t,translatedStrings:this.props.uploadMediaTranslations.SelectStrings},this.props.languages.map(e=>i.a.createElement(A.Option,{key:e.id,id:e.id,value:e.id},e.label))))}renderChooseFile(){const e=this.props.uploadMediaTranslations.UploadMediaStrings,t=e.NO_FILE_CHOSEN,n=e.SUPPORTED_FILE_TYPES,o=e.CLOSED_CAPTIONS_CHOOSE_FILE
return i.a.createElement(_["a"].Item,{margin:"0 small small 0"},i.a.createElement("input",{id:"attachmentFile",accept:".vtt, .srt",ref:e=>{this.fileInput=e},onChange:e=>{this.props.onFileSelected(e.target.files[0])},style:{display:"none"},type:"file"}),i.a.createElement(u["a"],{as:"div"},i.a.createElement(f["a"],{as:"div"},n),i.a.createElement(x["a"],{margin:"xx-small 0 0 0",id:"attachmentFileButton",onClick:()=>{this.fileInput.click()},ref:e=>{this.attachmentFileButton=e}},this.props.selectedFile?this.props.selectedFile.name:o),!this.props.selectedFile&&i.a.createElement(u["a"],{display:"inline-block",margin:"0 0 0 small"},i.a.createElement(f["a"],{color:"secondary"},t))))}renderChosen(){const e=this.props.uploadMediaTranslations.UploadMediaStrings.REMOVE_FILE
return i.a.createElement(_["a"],{as:"div",wrap:"wrap",justifyItems:"start",alignItems:"end","data-testid":"CC-CreatorRow-chosen"},i.a.createElement(_["a"].Item,{margin:"0 0 small 0"},i.a.createElement(u["a"],{as:"div",borderWidth:"small",padding:"0 0 0 small",borderRadius:"medium",width:"100%"},i.a.createElement(_["a"],{justifyItems:"space-between"},i.a.createElement(_["a"].Item,null,i.a.createElement(f["a"],{weight:"bold"},this.props.selectedLanguage.label)),i.a.createElement(_["a"].Item,{margin:"0 0 0 x-small"},i.a.createElement(l["a"],{ref:this._deleteCCBtnRef,withBackground:false,withBorder:false,onClick:this.handleDeleteRow,screenReaderLabel:c()(e,{lang:this.props.selectedLanguage.label})},i.a.createElement(m["a"],null)))))))}render(){return this.isReadonly?this.renderChosen():this.renderChoosing()}}S.propTypes={languages:Object(r["arrayOf"])(Object(r["shape"])({id:r["string"],label:r["string"]})),liveRegion:r["func"],uploadMediaTranslations:Object(r["shape"])({UploadMediaStrings:Object(r["objectOf"])(r["string"]),SelectStrings:Object(r["objectOf"])(r["string"])}),onDeleteRow:r["func"],onFileSelected:r["func"],onLanguageSelected:r["func"],selectedFile:Object(r["shape"])({name:r["string"].isRequired}),selectedLanguage:Object(r["shape"])({id:r["string"].isRequired,label:r["string"].isRequired})}
class j extends o["Component"]{constructor(e){var t
super(e)
this.newButtonClick=()=>{this.setState({addingNewClosedCaption:true,newSelectedFile:null,newSelectedLanguage:null,announcement:null})}
this.onFileSelected=e=>{this.state.newSelectedLanguage&&e?this.setState(t=>{const n=t.subtitles.concat([{locale:t.newSelectedLanguage.id,file:e,isNew:true}])
this.props.updateSubtitles(n)
return{subtitles:n,addingNewClosedCaption:false,newSelectedFile:null,newSelectedLanguage:null,announcement:c()(this.props.uploadMediaTranslations.UploadMediaStrings.ADDED_CAPTION,{lang:t.newSelectedLanguage.label})}}):this.setState({newSelectedFile:e,announcement:null})}
this.onLanguageSelected=e=>{this.state.newSelectedFile?this.setState(t=>{const n=t.subtitles.concat([{locale:e.id,file:t.newSelectedFile,isNew:true}])
this.props.updateSubtitles(n)
return{subtitles:n,addingNewClosedCaption:false,newSelectedFile:null,newSelectedLanguage:null,announcement:c()(this.props.uploadMediaTranslations.UploadMediaStrings.ADDED_CAPTION,{lang:e.label})}}):this.setState({newSelectedLanguage:e,announcement:null})}
this.onRowDelete=e=>{this.setState(t=>{const n=this.props.languages.findIndex(t=>t.id===e)
const o=t.subtitles.findIndex(t=>t.locale===e)
const i=t.subtitles.filter(t=>t.locale!==e)
this.props.updateSubtitles(i)
return{subtitles:i,addingNewClosedCaption:!(i.length>0)||t.addingNewClosedCaption,announcement:c()(this.props.uploadMediaTranslations.UploadMediaStrings.DELETED_CAPTION,{lang:null===n||void 0===n?void 0:n.label}),lastDeletedCCIndex:o}})}
this.state={addingNewClosedCaption:!(null!==e&&void 0!==e&&null!==(t=e.subtitles)&&void 0!==t&&t.length),newSelectedFile:null,newSelectedLanguage:null,lastDeletedCCIndex:-1,subtitles:e.subtitles||[],announcement:null}
this._addButtonRef=i.a.createRef()
this._newCreatorRef=i.a.createRef()
this._nextCCRef=i.a.createRef()}componentDidUpdate(){if(document.activeElement===document.body){if(this._newCreatorRef.current)this._newCreatorRef.current.focus()
else if(this._nextCCRef.current)this._nextCCRef.current.focus()
else{var e
null===(e=this._addButtonRef.current)||void 0===e||e.focus()}this.setState(e=>{if(-1!==e.lastDeletedCCIndex)return{lastDeletedCCIndex:-1}
return null})}}render(){const e=this.props.uploadMediaTranslations.UploadMediaStrings.ADD_NEW_CAPTION_OR_SUBTITLE
return i.a.createElement(u["a"],{display:"inline-block","data-testid":"ClosedCaptionPanel"},this.state.announcement&&i.a.createElement(s["a"],{liveRegion:this.props.liveRegion,screenReaderOnly:true,isLiveRegionAtomic:true,liveRegionPoliteness:"assertive"},this.state.announcement),i.a.createElement(u["a"],{display:"inline-block"},this.state.subtitles.map((e,t)=>i.a.createElement(S,{ref:t===this.state.lastDeletedCCIndex?this._nextCCRef:void 0,key:e.locale,liveRegion:this.props.liveRegion,uploadMediaTranslations:this.props.uploadMediaTranslations,onDeleteRow:this.onRowDelete,onLanguageSelected:this.onLanguageSelected,onFileSelected:this.onFileSelected,languages:this.props.languages,selectedLanguage:this.props.languages.find(t=>t.id===e.locale),selectedFile:e.file}))),this.state.addingNewClosedCaption?i.a.createElement(u["a"],{as:"div"},i.a.createElement(S,{ref:this._newCreatorRef,liveRegion:this.props.liveRegion,uploadMediaTranslations:this.props.uploadMediaTranslations,onDeleteRow:this.onRowDelete,onLanguageSelected:this.onLanguageSelected,onFileSelected:this.onFileSelected,languages:this.props.languages.filter(e=>!this.state.subtitles.find(t=>t.locale===e.id)),selectedLanguage:this.state.newSelectedLanguage,selectedFile:this.state.newSelectedFile})):i.a.createElement("div",{style:{position:"relative",textAlign:"center"}},i.a.createElement(l["a"],{ref:this._addButtonRef,shape:"circle",color:"primary",screenReaderLabel:e,onClick:this.newButtonClick,margin:"x-small auto"},i.a.createElement(d["a"],null))))}}j.propTypes={liveRegion:r["func"].isRequired,subtitles:Object(r["arrayOf"])(Object(r["shape"])({locale:r["string"].isRequired,file:Object(r["shape"])({name:r["string"].isRequired}).isRequired})),updateSubtitles:r["func"].isRequired,uploadMediaTranslations:Object(r["shape"])({UploadMediaStrings:Object(r["objectOf"])(r["string"]),SelectStrings:Object(r["objectOf"])(r["string"])}).isRequired,languages:Object(r["arrayOf"])(Object(r["shape"])({id:r["string"],language:r["string"]})).isRequired}},"4le0":function(e,t,n){"use strict";(function(e){n.d(t,"a",(function(){return i}))
var o=function(){return"undefined"!==typeof window?window:e}
var i=function(){var e=o()
return e&&e.tinymce?e.tinymce:null}}).call(this,n("yLpj"))},"7Jtz":function(e,t,n){"use strict"
n.d(t,"a",(function(){return r}))
var o=n("ouhR")
var i=n.n(o)
function r(e,t){const n=t.init_instance_callback
t.init_instance_callback=function(t){const o=e||{}
const r=t.getElement()
r&&Object.keys(o).forEach(e=>{r.setAttribute(e,o[e])})
const a=i()("#"+t.id)
t.on("keyup",e=>{i()(document).trigger("editorKeyUp",[e])})
t.on("change",()=>{a.trigger("change")})
i()(window).triggerHandler("resize")
"onfocusout"in t.contentWindow||i()(t.contentWindow).blur(()=>{if(!t.removed&&t.undoManager.typing){t.undoManager.typing=false
t.undoManager.add()}})
n&&n(t)}
return t}},"9dNb":function(e,t,n){"use strict"
n.d(t,"a",(function(){return s}))
var o=n("0k/6")
const i="image/svg"
const r=400
const a="image/svg+xml-buttons-and-icons"
async function c(e){try{const t=await e.slice(0,r).text()
if(t.includes(a))return{category:o["c"]}}catch{}}async function s(e){var t
if(null!==e&&void 0!==e&&null!==(t=e.type)&&void 0!==t&&t.includes(i))return await c(e)}},"9kyW":function(e,t,n){"use strict"
function o(e){var t=5381,n=e.length
while(n)t=33*t^e.charCodeAt(--n)
return t>>>0}e.exports=o},"Cp+0":function(e,t,n){"use strict"
n.d(t,"a",(function(){return w}))
var o=n("Ff2n")
var i=n("1OyB")
var r=n("vuIU")
var a=n("Ji7U")
var c=n("LK+K")
var s=n("q1tI")
var l=n.n(s)
var d=n("17x9")
var u=n.n(d)
var x=n("oXx0")
var _=n("J2CL")
var m=n("jtGx")
var p=n("C6Zt")
var f=n("tPrY")
var h,y,b,g,v
var w=(h=Object(x["a"])(),y=Object(_["j"])(f["a"]),h(b=y(b=(v=g=function(e){Object(a["a"])(n,e)
var t=Object(c["a"])(n)
function n(){var e
Object(i["a"])(this,n)
for(var o=arguments.length,r=new Array(o),a=0;a<o;a++)r[a]=arguments[a]
e=t.call.apply(t,[this].concat(r))
e._baseButton=null
return e}Object(r["a"])(n,[{key:"focus",value:function(){this._baseButton&&this._baseButton.focus()}},{key:"render",value:function(){var e=this
var t=this.props,n=t.children,i=t.type,r=t.size,a=t.elementRef,c=t.as,s=t.interaction,d=t.color,u=t.margin,x=t.cursor,_=t.href,f=t.renderIcon,h=Object(o["a"])(t,["children","type","size","elementRef","as","interaction","color","margin","cursor","href","renderIcon"])
var y=this.theme
return l.a.createElement(p["a"],Object.assign({},Object(m["b"])(h),{isCondensed:true,withBackground:false,withBorder:false,type:i,size:r,elementRef:a,as:c,interaction:s,color:d,margin:u,cursor:x,href:_,renderIcon:f,theme:y,ref:function(t){e._baseButton=t}}),n)}},{key:"focused",get:function(){return this._baseButton&&this._baseButton.focused}}])
n.displayName="CondensedButton"
return n}(s["Component"]),g.propTypes={children:u.a.node,type:u.a.oneOf(["button","submit","reset"]),size:u.a.oneOf(["small","medium","large"]),elementRef:u.a.func,as:u.a.elementType,interaction:u.a.oneOf(["enabled","disabled","readonly"]),color:u.a.oneOf(["primary","primary-inverse"]),margin:_["c"].spacing,cursor:u.a.string,href:u.a.string,renderIcon:u.a.oneOfType([u.a.node,u.a.func])},g.defaultProps={children:null,type:"button",size:"medium",elementRef:function(e){},as:"button",interaction:void 0,color:"primary",margin:"0",cursor:"pointer",href:void 0,renderIcon:void 0},v))||b)||b)},CpOe:function(e,t,n){"use strict"
var o=/[{}#]+/g
var i=/[{}\s]+/
var r=/[{}]+/g
var a="'"
var c="''"
var s="#"
e.exports=function(e){return l(e,null)}
function l(e,t){return e.map((function(e){if("string"===typeof e)return d(e,t)
return u(e,t)})).join("")}function d(e,t){var n="plural"===t?o:r
return e.replace(/'/g,c).replace(n,"'$&'")}function u(e,t){if(e[0]===s)return s
if("number"===typeof e[2])return m(e)
return x(e)}function x(e){var t=e[0]
var n=e[1]
var o=e[2]
var i="object"===typeof o?","+p(o,n)+"\n":o?", "+_(o)+" ":" "
return"{ "+t+(n?", "+n:"")+i+"}"}function _(e){if(!i.test(e))return e.replace(/'/g,c)
return a+e.replace(/'/g,c)+a}function m(e){var t=e[0]
var n=e[1]
var o=e[2]
var i=e[3]
return"{ "+t+", "+n+","+(o?" offset:"+o:"")+p(i,n)+"\n}"}function p(e,t){var n=Object.keys(e)
var o=n.reduce((function(e,t){return Math.max(e,t.length)}),0)
return n.map((function(n){return"\n  "+f(n,o)+" {"+l(e[n],t)+"}"})).join("")}function f(e,t){var n=""
for(var o=e.length;o<t;++o)n+=" "
return n+e}},DWdj:function(e,t,n){"use strict"
n.d(t,"a",(function(){return o}))
n.d(t,"b",(function(){return i}))
n.d(t,"e",(function(){return a}))
n.d(t,"d",(function(){return c}))
n.d(t,"c",(function(){return s}))
function o(e){let t=e
if(e){!e.match(/@/)||e.match(/\//)||e.match(/^mailto:/)?e.match(/^\w+:\/\//)||e.match(/^(?:mailto|skype|tel):/)||e.match(/^\//)||(t="http://"+e):t="mailto:"+e;-1==t.indexOf("@")||0==t.indexOf("mailto:")||t.match(/^http/)||(t="mailto:"+t)}return t}function i(e,t){t=t||e.selection.getNode()
return s(t)?e.dom.select("a[href]",t)[0]:e.dom.getParent(t,"a[href]")}const r=document.createElement("div")
function a(e){r.innerHTML=e
return!r.querySelector("img,iframe,video,audio")}function c(e){if(/(?:<(iframe|audio|video)|data-placeholder-for)/.test(e))return false
return true}function s(e){return e&&"FIGURE"===e.nodeName&&/\bimage\b/i.test(e.className)}},FeGr:function(e,t,n){"use strict";(function(t){e.exports=n
function n(e){if(!o.length){i()
true}o[o.length]=e}var o=[]
var i
var r=0
var a=1024
function c(){while(r<o.length){var e=r
r+=1
o[e].call()
if(r>a){for(var t=0,n=o.length-r;t<n;t++)o[t]=o[t+r]
o.length-=r
r=0}}o.length=0
r=0
false}var s="undefined"!==typeof t?t:self
var l=s.MutationObserver||s.WebKitMutationObserver
i="function"===typeof l?d(c):u(c)
n.requestFlush=i
function d(e){var t=1
var n=new l(e)
var o=document.createTextNode("")
n.observe(o,{characterData:true})
return function(){t=-t
o.data=t}}function u(e){return function(){var t=setTimeout(o,0)
var n=setInterval(o,50)
function o(){clearTimeout(t)
clearInterval(n)
e()}}}n.makeRequestCallFromTimer=u}).call(this,n("yLpj"))},FkO2:function(e,t,n){"use strict"
Object.defineProperty(t,"__esModule",{value:true})
var o=t.type="@@redux-batch-middleware/BATCH"
t.batch=function(e){var t=e.dispatch
return function(e){return function(n){Array.isArray(n)?t({type:o,payload:n}):e(n)}}}
t.batching=function(e){return function t(n,i){return i.type===o?i.payload.reduce(t,n):e(n,i)}}},G1G5:function(e,t,n){"use strict"
n.d(t,"b",(function(){return D}))
n.d(t,"a",(function(){return R}))
n.d(t,"c",(function(){return F}))
var o=n("q1tI")
var i=n.n(o)
var r=n("i8i4")
var a=n.n(r)
var c=n("QV6e")
var s=n("WRSb")
var l=n("ODXe")
var d=n("17x9")
var u=n("6SzX")
var x=n("Xx/m")
var _=n("Mmr1")
var m=n("msMH")
var p=n("/5Zp")
var f=n("GTSS")
var h=n("2zZe")
var y=n("M8//")
var b=n("gW/U")
var g=n("TstA")
var v=n("sTNg")
var w=n("n12J")
var k=n("bZJi")
var C=n("Ci/e")
var O=n("eHui")
var E=n("4LsN")
var A=n("hlkS")
var S=n("NFDp")
var j=n("Mesd")
var I=n("z7I/")
const T=()=>document.getElementById("flash_screenreader_holder")
function L(e){const t=e.videoOptions,n=e.onEntered,r=e.onExited,a=e.onRequestClose,s=e.onSave,d=e.open,L=e.trayProps,B=e.id
const D=t.naturalHeight,R=t.naturalWidth
const F=t.appliedHeight||D
const M=t.appliedWidth||R
const z=Object(o["useState"])(t.titleText),P=Object(l["a"])(z,2),N=P[0],U=P[1]
const $=Object(o["useState"])("embed"),H=Object(l["a"])($,2),W=H[0],q=H[1]
const V=Object(o["useState"])(t.videoSize),G=Object(l["a"])(V,2),K=G[0],Z=G[1]
const Y=Object(o["useState"])(F),J=Object(l["a"])(Y,2),X=J[0],Q=J[1]
const ee=Object(o["useState"])(M),te=Object(l["a"])(ee,2),ne=te[0],oe=te[1]
const ie=Object(o["useState"])(t.tracks||[]),re=Object(l["a"])(ie,2),ae=re[0],ce=re[1]
const se=Object(o["useState"])(A["e"]),le=Object(l["a"])(se,1),de=le[0]
const ue=Object(o["useState"])(Math.round(X/ne*A["e"])),xe=Object(l["a"])(ue,1),_e=xe[0]
const me=Object(o["useState"])(A["c"]),pe=Object(l["a"])(me,1),fe=pe[0]
const he=Object(j["b"])(t,{minHeight:_e,minWidth:de,minPercentage:fe})
function ye(e){U(e.target.value)}function be(e){e.target.focus()
q(e.target.value)}function ge(e,t){Z(t.value)
if(t.value===A["a"]){Q(F)
oe(M)}else{const e=Object(A["j"])(t.value,R,D),n=e.height,o=e.width
Q(n)
oe(o)}}function ve(e){ce(e)}function we(e,n){e.preventDefault()
let o=X
let i=ne
if(K===A["a"]){o=he.height
i=he.width}s({media_object_id:t.id,titleText:N,appliedHeight:o,appliedWidth:i,displayAs:W,subtitles:ae,updateMediaObject:n})}const ke=Object(S["a"])("Used by screen readers to describe the video")
const Ce=i.a.createElement(g["a"],{alignItems:"center"},i.a.createElement(g["a"].Item,null,Object(S["a"])("Title")),i.a.createElement(g["a"].Item,{margin:"0 0 0 xx-small"},i.a.createElement(k["a"],{on:["hover","focus"],placement:"top",tip:i.a.createElement(w["a"],{display:"block",id:"alt-text-label-tooltip",maxWidth:"14rem"},ke)},i.a.createElement(x["a"],{icon:b["a"],size:"small",variant:"icon"},i.a.createElement(u["a"],null,ke)))))
const Oe=[]
K!==A["a"]&&Oe.push({text:Object(S["a"])("{width} x {height}px",{height:X,width:ne}),type:"hint"})
const Ee="embed"===W&&(""===N||K===A["a"]&&!he.isValid)
return i.a.createElement(O["a"],L,e=>i.a.createElement(C["a"],{key:"video-options-tray","data-mce-component":true,label:Object(S["a"])("Video Options Tray"),onDismiss:a,onEntered:n,onExited:r,open:d,placement:"end",shouldCloseOnDocumentClick:true,shouldContainFocus:true,shouldReturnFocus:true,size:"regular"},i.a.createElement(g["a"],{direction:"column",height:Object(I["a"])()},i.a.createElement(g["a"].Item,{as:"header",padding:"medium"},i.a.createElement(g["a"],{direction:"row"},i.a.createElement(g["a"].Item,{grow:true,shrink:true},i.a.createElement(m["a"],{as:"h2"},Object(S["a"])("Video Options"))),i.a.createElement(g["a"].Item,null,i.a.createElement(_["a"],{placemet:"static",variant:"icon",onClick:a},Object(S["a"])("Close"))))),i.a.createElement(g["a"].Item,{as:"form",grow:true,margin:"none",shrink:true},i.a.createElement(g["a"],{justifyItems:"space-between",direction:"column",height:"100%"},i.a.createElement(g["a"].Item,{grow:true,padding:"small",shrink:true},i.a.createElement(g["a"],{direction:"column"},i.a.createElement(g["a"].Item,{padding:"small"},i.a.createElement(y["a"],{"aria-describedby":"alt-text-label-tooltip",disabled:"link"===W,height:"4rem",label:Ce,onChange:ye,placeholder:Object(S["a"])("(Describe the video)"),resize:"vertical",value:N})),i.a.createElement(g["a"].Item,{margin:"small none none none",padding:"small"},i.a.createElement(p["a"],{description:Object(S["a"])("Display Options"),name:"display-video-as",onChange:be,value:W},i.a.createElement(f["a"],{label:Object(S["a"])("Embed Video"),value:"embed"}),i.a.createElement(f["a"],{label:Object(S["a"])("Display Text Link (Opens in a new tab)"),value:"link"}))),i.a.createElement(g["a"].Item,{margin:"small none xx-small none"},i.a.createElement(w["a"],{as:"div",padding:"small small xx-small small"},i.a.createElement(h["a"],{id:B+"-size",disabled:"embed"!==W,renderLabel:Object(S["a"])("Size"),messages:Oe,assistiveText:Object(S["a"])("Use arrow keys to navigate options."),onChange:ge,value:K},A["k"].map(e=>i.a.createElement(h["a"].Option,{id:`${B}-size-${e}`,key:e,value:e},Object(A["i"])(e))))),K===A["a"]&&i.a.createElement(w["a"],{as:"div",padding:"xx-small small"},i.a.createElement(j["a"],{dimensionsState:he,disabled:"embed"!==W,minHeight:_e,minWidth:de,minPercentage:fe}))),i.a.createElement(g["a"].Item,{padding:"small"},i.a.createElement(v["b"],{description:Object(S["a"])("Closed Captions/Subtitles")},i.a.createElement(E["default"],{subtitles:ae.map(e=>({locale:e.locale,file:{name:e.language||e.locale}})),uploadMediaTranslations:c["a"].uploadMediaTranslations,languages:c["a"].languages,updateSubtitles:ve,liveRegion:T}))))),i.a.createElement(g["a"].Item,{background:"secondary",borderWidth:"small none none none",padding:"small medium",textAlign:"end"},i.a.createElement(x["a"],{disabled:Ee,onClick:t=>we(t,e.updateMediaObject),variant:"primary"},Object(S["a"])("Done"))))))))}L.propTypes={videoOptions:Object(d["shape"])({titleText:d["string"].isRequired,appliedHeight:d["number"],appliedWidth:d["number"],naturalHeight:d["number"].isRequired,naturalWidth:d["number"].isRequired,tracks:Object(d["arrayOf"])(Object(d["shape"])({locale:d["string"].isRequired}))}).isRequired,onEntered:d["func"],onExited:d["func"],onRequestClose:d["func"].isRequired,onSave:d["func"].isRequired,open:d["bool"].isRequired,trayProps:Object(d["shape"])({host:d["string"].isRequired,jwt:d["string"].isRequired}),id:d["string"]}
L.defaultProps={onEntered:null,onExited:null,id:"video-options-tray"}
const B="instructure-video-options-tray-container"
const D={height:"225px",width:"400px"}
const R={width:"320px",height:"14.25rem"}
class F{constructor(){this._editor=null
this._isOpen=false
this._shouldOpen=false
this._renderId=0}get $container(){let e=document.getElementById(B)
if(null==e){e=document.createElement("div")
e.id=B
document.body.appendChild(e)}return e}get isOpen(){return this._isOpen}showTrayForEditor(e){this._editor=e
this.$videoContainer=Object(s["g"])(e.selection.getNode())
this._shouldOpen=true
c["a"].focusedEditor&&c["a"].hideTrays()
const t=c["a"].trayProps.get(e)
this._renderTray(t)}hideTrayForEditor(e){this._editor===e&&this._dismissTray()}_applyVideoOptions(e){var t
if("IFRAME"===(null===(t=this.$videoContainer)||void 0===t?void 0:t.tagName)){const t=this.$videoContainer.parentElement
if("embed"===e.displayAs){var n
const o=e.appliedHeight>e.appliedWidth
const i=null!==(n=e.subtitles)&&void 0!==n&&n.length?400:320
const r={height:e.appliedHeight+"px",width:Math.max(i,o?e.appliedHeight:e.appliedWidth)+"px"}
this._editor.dom.setStyles(t,r)
this._editor.dom.setStyles(this.$videoContainer,r)
const a=e.titleText
this._editor.dom.setAttrib(t,"data-mce-p-title",a)
this._editor.dom.setAttrib(t,"data-mce-p-data-titleText",e.titleText)
this._editor.dom.setAttrib(this.$videoContainer,"title",a)
this._editor.dom.setAttrib(this.$videoContainer,"data-titleText",e.titleText)
this._editor.fire("ObjectResized",{target:this.$videoContainer,width:e.appliedWidth,height:e.appliedHeight})}else{const n=this._editor.dom.getAttrib(t,"data-mce-p-src")
const o=e.titleText||this._editor.dom.getAttrib(this.$videoContainer,"title")
const i=document.createElement("a")
i.setAttribute("href",n)
i.setAttribute("target","_blank")
i.setAttribute("rel","noreferrer noopener")
i.textContent=o
this._editor.dom.replace(i,t)
this._editor.selection.select(i)
this.$videoContainer=null}e.media_object_id&&"undefined"!==e.media_object_id&&e.updateMediaObject({media_object_id:e.media_object_id,title:e.titleText,subtitles:e.subtitles}).then(()=>{this.$videoContainer&&"embed"===e.displayAs&&this.$videoContainer.contentWindow.location.reload()}).catch(e=>{console.error("failed updating video captions",e)})}this._dismissTray()}_dismissTray(){this.$videoContainer&&this._editor.selection.select(this.$videoContainer)
this._shouldOpen=false
this._renderTray()
this._editor=null}_renderTray(e){let t={}
if(this._shouldOpen){this._renderId++
t=Object(s["f"])(this.$videoContainer)||{}}const n=i.a.createElement(L,{id:"video-options-tray",key:this._renderId,videoOptions:t,onEntered:()=>{this._isOpen=true},onExited:()=>{c["a"].focusActiveEditor(false)
this._isOpen=false},onSave:e=>{this._applyVideoOptions(e)},onRequestClose:()=>this._dismissTray(),open:this._shouldOpen,trayProps:e})
a.a.render(n,this.$container)}}},GEYT:function(e,t,n){var o=n("xEkU"),i="complete",r="canceled",a="skipped"
function c(e,t,n){if(_(e))e.scrollTo(t,n)
else{e.scrollLeft=t
e.scrollTop=n}}function s(e,t,n){var o,i,r,a,c,s=e.getBoundingClientRect(),l=n&&null!=n.left?n.left:.5,d=n&&null!=n.top?n.top:.5,u=l,x=d
if(_(t)){i=s.left+window.scrollX-window.innerWidth*u+Math.min(s.width,window.innerWidth)*u
r=s.top+window.scrollY-window.innerHeight*x+Math.min(s.height,window.innerHeight)*x
i=Math.max(Math.min(i,document.body.scrollWidth-window.innerWidth*u),0)
r=Math.max(Math.min(r,document.body.scrollHeight-window.innerHeight*x),0)
a=i-window.scrollX
c=r-window.scrollY}else{o=t.getBoundingClientRect()
var m=s.top-(o.top-t.scrollTop)
var p=s.left-(o.left-t.scrollLeft)
i=p+s.width*u-t.clientWidth*u
r=m+s.height*x-t.clientHeight*x
i=Math.max(Math.min(i,t.scrollWidth-t.clientWidth),0)
r=Math.max(Math.min(r,t.scrollHeight-t.clientHeight),0)
a=i-t.scrollLeft
c=r-t.scrollTop}return{x:i,y:r,differenceX:a,differenceY:c}}function l(e){o((function(){var t=e._scrollSettings
if(!t)return
var n=s(t.target,e,t.align),o=Date.now()-t.startTime,r=Math.min(1/t.time*o,1)
if(o>t.time+20||Math.abs(n.differenceY)<=1&&Math.abs(n.differenceX)<=1){c(e,n.x,n.y)
e._scrollSettings=null
return t.end(i)}var a=1-t.ease(r)
c(e,n.x-n.differenceX*a,n.y-n.differenceY*a)
l(e)}))}function d(e){return _(e)?{top:0,left:0,right:window.innerWidth,bottom:window.innerHeight}:e.getBoundingClientRect?e.getBoundingClientRect():null}function u(e,t){var n=d(e)
var o=d(t)
return n&&o&&n.bottom<=o.bottom&&n.right<=o.right&&n.top>=o.top&&n.left>=o.left}function x(e,t,n,o){var i,c=!t._scrollSettings,s=t._scrollSettings,d=Date.now()
s&&s.end(r)
function x(e,n){t._scrollSettings=null
o(e)
t.removeEventListener("touchstart",i)}t._scrollSettings={startTime:s?s.startTime:Date.now(),target:e,time:n.time+(s?d-s.startTime:0),ease:n.ease,align:n.align,end:x}
i=x.bind(null,r)
t.addEventListener("touchstart",i)
if(c&&!u(e,t)){l(t)
return true}x(a)
return false}function _(e){return e===window}function m(e,t,n){if(!e)return
if("function"===typeof t){n=t
t=null}t||(t={})
t.time=isNaN(t.time)?1e3:t.time
t.ease=t.ease||function(e){return 1-Math.pow(1-e,e/2)}
var o=e.parentElement,i={traversed:0,validated:0,scrolled:0}
function r(e){i.validated-1||n&&n(e)}while(o){if((!t.validTarget||t.validTarget(o,i))&&(_(o)||(o.scrollHeight!==o.clientHeight||o.scrollWidth!==o.clientWidth)&&"hidden"!==getComputedStyle(o).overflow)){i.validated++
i.scrolled+=x(e,o,t,r)?1:0}i.traversed++
o=o.parentElement
if(!o)return
"BODY"===o.tagName&&(o=window)}}e.exports.scrollIntoView=m},HoBo:function(e,t,n){"use strict"
n.d(t,"a",(function(){return i}))
n.d(t,"b",(function(){return r}))
function o(e,t,n,o){const i=o.minHeight||0
const r=o.minWidth||0
const a=e*n
const c=t*n
let s=n
if(a<r){const t=Math.max(a,r)
s=t/e}if(c<i){const e=Math.max(c,i)
s=Math.max(e/t,s)}return{height:Math.round(t*s),width:Math.round(e*s)}}function i(e,t,n,i={}){if(null==n)return{height:null,width:null}
return o(e,t,n/t,i)}function r(e,t,n,i={}){if(null==n)return{height:null,width:null}
return o(e,t,n/e,i)}},IDhZ:function(e,t,n){"use strict"
var o=n("MgzW"),i=n("q1tI")
function r(e){for(var t="https://reactjs.org/docs/error-decoder.html?invariant="+e,n=1;n<arguments.length;n++)t+="&args[]="+encodeURIComponent(arguments[n])
return"Minified React error #"+e+"; visit "+t+" for the full message or use the non-minified dev environment for full errors and additional helpful warnings."}var a="function"===typeof Symbol&&Symbol.for,c=a?Symbol.for("react.portal"):60106,s=a?Symbol.for("react.fragment"):60107,l=a?Symbol.for("react.strict_mode"):60108,d=a?Symbol.for("react.profiler"):60114,u=a?Symbol.for("react.provider"):60109,x=a?Symbol.for("react.context"):60110,_=a?Symbol.for("react.concurrent_mode"):60111,m=a?Symbol.for("react.forward_ref"):60112,p=a?Symbol.for("react.suspense"):60113,f=a?Symbol.for("react.suspense_list"):60120,h=a?Symbol.for("react.memo"):60115,y=a?Symbol.for("react.lazy"):60116,b=a?Symbol.for("react.block"):60121,g=a?Symbol.for("react.fundamental"):60117,v=a?Symbol.for("react.scope"):60119
function w(e){if(-1===e._status){e._status=0
var t=e._ctor
t=t()
e._result=t
t.then((function(t){0===e._status&&(t=t.default,e._status=1,e._result=t)}),(function(t){0===e._status&&(e._status=2,e._result=t)}))}}function k(e){if(null==e)return null
if("function"===typeof e)return e.displayName||e.name||null
if("string"===typeof e)return e
switch(e){case s:return"Fragment"
case c:return"Portal"
case d:return"Profiler"
case l:return"StrictMode"
case p:return"Suspense"
case f:return"SuspenseList"}if("object"===typeof e)switch(e.$$typeof){case x:return"Context.Consumer"
case u:return"Context.Provider"
case m:var t=e.render
t=t.displayName||t.name||""
return e.displayName||(""!==t?"ForwardRef("+t+")":"ForwardRef")
case h:return k(e.type)
case b:return k(e.render)
case y:if(e=1===e._status?e._result:null)return k(e)}return null}var C=i.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED
C.hasOwnProperty("ReactCurrentDispatcher")||(C.ReactCurrentDispatcher={current:null})
C.hasOwnProperty("ReactCurrentBatchConfig")||(C.ReactCurrentBatchConfig={suspense:null})
var O={}
function E(e,t){for(var n=0|e._threadCount;n<=t;n++)e[n]=e._currentValue2,e._threadCount=n+1}function A(e,t,n,o){if(o&&(o=e.contextType,"object"===typeof o&&null!==o))return E(o,n),o[n]
if(e=e.contextTypes){n={}
for(var i in e)n[i]=t[i]
t=n}else t=O
return t}for(var S=new Uint16Array(16),j=0;15>j;j++)S[j]=j+1
S[15]=0
var I=/^[:A-Z_a-z\u00C0-\u00D6\u00D8-\u00F6\u00F8-\u02FF\u0370-\u037D\u037F-\u1FFF\u200C-\u200D\u2070-\u218F\u2C00-\u2FEF\u3001-\uD7FF\uF900-\uFDCF\uFDF0-\uFFFD][:A-Z_a-z\u00C0-\u00D6\u00D8-\u00F6\u00F8-\u02FF\u0370-\u037D\u037F-\u1FFF\u200C-\u200D\u2070-\u218F\u2C00-\u2FEF\u3001-\uD7FF\uF900-\uFDCF\uFDF0-\uFFFD\-.0-9\u00B7\u0300-\u036F\u203F-\u2040]*$/,T=Object.prototype.hasOwnProperty,L={},B={}
function D(e){if(T.call(B,e))return!0
if(T.call(L,e))return!1
if(I.test(e))return B[e]=!0
L[e]=!0
return!1}function R(e,t,n,o){if(null!==n&&0===n.type)return!1
switch(typeof t){case"function":case"symbol":return!0
case"boolean":if(o)return!1
if(null!==n)return!n.acceptsBooleans
e=e.toLowerCase().slice(0,5)
return"data-"!==e&&"aria-"!==e
default:return!1}}function F(e,t,n,o){if(null===t||"undefined"===typeof t||R(e,t,n,o))return!0
if(o)return!1
if(null!==n)switch(n.type){case 3:return!t
case 4:return!1===t
case 5:return isNaN(t)
case 6:return isNaN(t)||1>t}return!1}function M(e,t,n,o,i,r){this.acceptsBooleans=2===t||3===t||4===t
this.attributeName=o
this.attributeNamespace=i
this.mustUseProperty=n
this.propertyName=e
this.type=t
this.sanitizeURL=r}var z={}
"children dangerouslySetInnerHTML defaultValue defaultChecked innerHTML suppressContentEditableWarning suppressHydrationWarning style".split(" ").forEach((function(e){z[e]=new M(e,0,!1,e,null,!1)}));[["acceptCharset","accept-charset"],["className","class"],["htmlFor","for"],["httpEquiv","http-equiv"]].forEach((function(e){var t=e[0]
z[t]=new M(t,1,!1,e[1],null,!1)}));["contentEditable","draggable","spellCheck","value"].forEach((function(e){z[e]=new M(e,2,!1,e.toLowerCase(),null,!1)}));["autoReverse","externalResourcesRequired","focusable","preserveAlpha"].forEach((function(e){z[e]=new M(e,2,!1,e,null,!1)}))
"allowFullScreen async autoFocus autoPlay controls default defer disabled disablePictureInPicture formNoValidate hidden loop noModule noValidate open playsInline readOnly required reversed scoped seamless itemScope".split(" ").forEach((function(e){z[e]=new M(e,3,!1,e.toLowerCase(),null,!1)}));["checked","multiple","muted","selected"].forEach((function(e){z[e]=new M(e,3,!0,e,null,!1)}));["capture","download"].forEach((function(e){z[e]=new M(e,4,!1,e,null,!1)}));["cols","rows","size","span"].forEach((function(e){z[e]=new M(e,6,!1,e,null,!1)}));["rowSpan","start"].forEach((function(e){z[e]=new M(e,5,!1,e.toLowerCase(),null,!1)}))
var P=/[\-:]([a-z])/g
function N(e){return e[1].toUpperCase()}"accent-height alignment-baseline arabic-form baseline-shift cap-height clip-path clip-rule color-interpolation color-interpolation-filters color-profile color-rendering dominant-baseline enable-background fill-opacity fill-rule flood-color flood-opacity font-family font-size font-size-adjust font-stretch font-style font-variant font-weight glyph-name glyph-orientation-horizontal glyph-orientation-vertical horiz-adv-x horiz-origin-x image-rendering letter-spacing lighting-color marker-end marker-mid marker-start overline-position overline-thickness paint-order panose-1 pointer-events rendering-intent shape-rendering stop-color stop-opacity strikethrough-position strikethrough-thickness stroke-dasharray stroke-dashoffset stroke-linecap stroke-linejoin stroke-miterlimit stroke-opacity stroke-width text-anchor text-decoration text-rendering underline-position underline-thickness unicode-bidi unicode-range units-per-em v-alphabetic v-hanging v-ideographic v-mathematical vector-effect vert-adv-y vert-origin-x vert-origin-y word-spacing writing-mode xmlns:xlink x-height".split(" ").forEach((function(e){var t=e.replace(P,N)
z[t]=new M(t,1,!1,e,null,!1)}))
"xlink:actuate xlink:arcrole xlink:role xlink:show xlink:title xlink:type".split(" ").forEach((function(e){var t=e.replace(P,N)
z[t]=new M(t,1,!1,e,"http://www.w3.org/1999/xlink",!1)}));["xml:base","xml:lang","xml:space"].forEach((function(e){var t=e.replace(P,N)
z[t]=new M(t,1,!1,e,"http://www.w3.org/XML/1998/namespace",!1)}));["tabIndex","crossOrigin"].forEach((function(e){z[e]=new M(e,1,!1,e.toLowerCase(),null,!1)}))
z.xlinkHref=new M("xlinkHref",1,!1,"xlink:href","http://www.w3.org/1999/xlink",!0);["src","href","action","formAction"].forEach((function(e){z[e]=new M(e,1,!1,e.toLowerCase(),null,!0)}))
var U=/["'&<>]/
function $(e){if("boolean"===typeof e||"number"===typeof e)return""+e
e=""+e
var t=U.exec(e)
if(t){var n,o="",i=0
for(n=t.index;n<e.length;n++){switch(e.charCodeAt(n)){case 34:t="&quot;"
break
case 38:t="&amp;"
break
case 39:t="&#x27;"
break
case 60:t="&lt;"
break
case 62:t="&gt;"
break
default:continue}i!==n&&(o+=e.substring(i,n))
i=n+1
o+=t}e=i!==n?o+e.substring(i,n):o}return e}function H(e,t){var n=z.hasOwnProperty(e)?z[e]:null
var o;(o="style"!==e)&&(o=null!==n?0===n.type:2<e.length&&("o"===e[0]||"O"===e[0])&&("n"===e[1]||"N"===e[1]))
if(o||F(e,t,n,!1))return""
if(null!==n){e=n.attributeName
o=n.type
if(3===o||4===o&&!0===t)return e+'=""'
n.sanitizeURL&&(t=""+t)
return e+'="'+$(t)+'"'}return D(e)?e+'="'+$(t)+'"':""}function W(e,t){return e===t&&(0!==e||1/e===1/t)||e!==e&&t!==t}var q="function"===typeof Object.is?Object.is:W,V=null,G=null,K=null,Z=!1,Y=!1,J=null,X=0
function Q(){if(null===V)throw Error(r(321))
return V}function ee(){if(0<X)throw Error(r(312))
return{memoizedState:null,queue:null,next:null}}function te(){null===K?null===G?(Z=!1,G=K=ee()):(Z=!0,K=G):null===K.next?(Z=!1,K=K.next=ee()):(Z=!0,K=K.next)
return K}function ne(e,t,n,o){for(;Y;)Y=!1,X+=1,K=null,n=e(t,o)
G=V=null
X=0
K=J=null
return n}function oe(e,t){return"function"===typeof t?t(e):t}function ie(e,t,n){V=Q()
K=te()
if(Z){var o=K.queue
t=o.dispatch
if(null!==J&&(n=J.get(o),void 0!==n)){J.delete(o)
o=K.memoizedState
do{o=e(o,n.action),n=n.next}while(null!==n)
K.memoizedState=o
return[o,t]}return[K.memoizedState,t]}e=e===oe?"function"===typeof t?t():t:void 0!==n?n(t):t
K.memoizedState=e
e=K.queue={last:null,dispatch:null}
e=e.dispatch=re.bind(null,V,e)
return[K.memoizedState,e]}function re(e,t,n){if(!(25>X))throw Error(r(301))
if(e===V)if(Y=!0,e={action:n,next:null},null===J&&(J=new Map),n=J.get(t),void 0===n)J.set(t,e)
else{for(t=n;null!==t.next;)t=t.next
t.next=e}}function ae(){}var ce=0,se={readContext:function(e){var t=ce
E(e,t)
return e[t]},useContext:function(e){Q()
var t=ce
E(e,t)
return e[t]},useMemo:function(e,t){V=Q()
K=te()
t=void 0===t?null:t
if(null!==K){var n=K.memoizedState
if(null!==n&&null!==t){e:{var o=n[1]
if(null===o)o=!1
else{for(var i=0;i<o.length&&i<t.length;i++)if(!q(t[i],o[i])){o=!1
break e}o=!0}}if(o)return n[0]}}e=e()
K.memoizedState=[e,t]
return e},useReducer:ie,useRef:function(e){V=Q()
K=te()
var t=K.memoizedState
return null===t?(e={current:e},K.memoizedState=e):t},useState:function(e){return ie(oe,e)},useLayoutEffect:function(){},useCallback:function(e){return e},useImperativeHandle:ae,useEffect:ae,useDebugValue:ae,useResponder:function(e,t){return{props:t,responder:e}},useDeferredValue:function(e){Q()
return e},useTransition:function(){Q()
return[function(e){e()},!1]}},le={html:"http://www.w3.org/1999/xhtml",mathml:"http://www.w3.org/1998/Math/MathML",svg:"http://www.w3.org/2000/svg"}
function de(e){switch(e){case"svg":return"http://www.w3.org/2000/svg"
case"math":return"http://www.w3.org/1998/Math/MathML"
default:return"http://www.w3.org/1999/xhtml"}}var ue={area:!0,base:!0,br:!0,col:!0,embed:!0,hr:!0,img:!0,input:!0,keygen:!0,link:!0,meta:!0,param:!0,source:!0,track:!0,wbr:!0},xe=o({menuitem:!0},ue),_e={animationIterationCount:!0,borderImageOutset:!0,borderImageSlice:!0,borderImageWidth:!0,boxFlex:!0,boxFlexGroup:!0,boxOrdinalGroup:!0,columnCount:!0,columns:!0,flex:!0,flexGrow:!0,flexPositive:!0,flexShrink:!0,flexNegative:!0,flexOrder:!0,gridArea:!0,gridRow:!0,gridRowEnd:!0,gridRowSpan:!0,gridRowStart:!0,gridColumn:!0,gridColumnEnd:!0,gridColumnSpan:!0,gridColumnStart:!0,fontWeight:!0,lineClamp:!0,lineHeight:!0,opacity:!0,order:!0,orphans:!0,tabSize:!0,widows:!0,zIndex:!0,zoom:!0,fillOpacity:!0,floodOpacity:!0,stopOpacity:!0,strokeDasharray:!0,strokeDashoffset:!0,strokeMiterlimit:!0,strokeOpacity:!0,strokeWidth:!0},me=["Webkit","ms","Moz","O"]
Object.keys(_e).forEach((function(e){me.forEach((function(t){t=t+e.charAt(0).toUpperCase()+e.substring(1)
_e[t]=_e[e]}))}))
var pe=/([A-Z])/g,fe=/^ms-/,he=i.Children.toArray,ye=C.ReactCurrentDispatcher,be={listing:!0,pre:!0,textarea:!0},ge=/^[a-zA-Z][a-zA-Z:_\.\-\d]*$/,ve={},we={}
function ke(e){if(void 0===e||null===e)return e
var t=""
i.Children.forEach(e,(function(e){null!=e&&(t+=e)}))
return t}var Ce=Object.prototype.hasOwnProperty,Oe={children:null,dangerouslySetInnerHTML:null,suppressContentEditableWarning:null,suppressHydrationWarning:null}
function Ee(e,t){if(void 0===e)throw Error(r(152,k(t)||"Component"))}function Ae(e,t,n){function a(i,a){var c=a.prototype&&a.prototype.isReactComponent,s=A(a,t,n,c),l=[],d=!1,u={isMounted:function(){return!1},enqueueForceUpdate:function(){if(null===l)return null},enqueueReplaceState:function(e,t){d=!0
l=[t]},enqueueSetState:function(e,t){if(null===l)return null
l.push(t)}}
if(c){if(c=new a(i.props,s,u),"function"===typeof a.getDerivedStateFromProps){var x=a.getDerivedStateFromProps.call(null,i.props,c.state)
null!=x&&(c.state=o({},c.state,x))}}else if(V={},c=a(i.props,s,u),c=ne(a,i.props,c,s),null==c||null==c.render){e=c
Ee(e,a)
return}c.props=i.props
c.context=s
c.updater=u
u=c.state
void 0===u&&(c.state=u=null)
if("function"===typeof c.UNSAFE_componentWillMount||"function"===typeof c.componentWillMount)if("function"===typeof c.componentWillMount&&"function"!==typeof a.getDerivedStateFromProps&&c.componentWillMount(),"function"===typeof c.UNSAFE_componentWillMount&&"function"!==typeof a.getDerivedStateFromProps&&c.UNSAFE_componentWillMount(),l.length){u=l
var _=d
l=null
d=!1
if(_&&1===u.length)c.state=u[0]
else{x=_?u[0]:c.state
var m=!0
for(_=_?1:0;_<u.length;_++){var p=u[_]
p="function"===typeof p?p.call(c,x,i.props,s):p
null!=p&&(m?(m=!1,x=o({},x,p)):o(x,p))}c.state=x}}else l=null
e=c.render()
Ee(e,a)
if("function"===typeof c.getChildContext&&(i=a.childContextTypes,"object"===typeof i)){var f=c.getChildContext()
for(var h in f)if(!(h in i))throw Error(r(108,k(a)||"Unknown",h))}f&&(t=o({},t,f))}for(;i.isValidElement(e);){var c=e,s=c.type
if("function"!==typeof s)break
a(c,s)}return{child:e,context:t}}var Se=function(){function e(e,t){i.isValidElement(e)?e.type!==s?e=[e]:(e=e.props.children,e=i.isValidElement(e)?[e]:he(e)):e=he(e)
e={type:null,domNamespace:le.html,children:e,childIndex:0,context:O,footer:""}
var n=S[0]
if(0===n){var o=S
n=o.length
var a=2*n
if(!(65536>=a))throw Error(r(304))
var c=new Uint16Array(a)
c.set(o)
S=c
S[0]=n+1
for(o=n;o<a-1;o++)S[o]=o+1
S[a-1]=0}else S[0]=S[n]
this.threadID=n
this.stack=[e]
this.exhausted=!1
this.currentSelectValue=null
this.previousWasTextNode=!1
this.makeStaticMarkup=t
this.suspenseDepth=0
this.contextIndex=-1
this.contextStack=[]
this.contextValueStack=[]}var t=e.prototype
t.destroy=function(){if(!this.exhausted){this.exhausted=!0
this.clearProviders()
var e=this.threadID
S[e]=S[0]
S[0]=e}}
t.pushProvider=function(e){var t=++this.contextIndex,n=e.type._context,o=this.threadID
E(n,o)
var i=n[o]
this.contextStack[t]=n
this.contextValueStack[t]=i
n[o]=e.props.value}
t.popProvider=function(){var e=this.contextIndex,t=this.contextStack[e],n=this.contextValueStack[e]
this.contextStack[e]=null
this.contextValueStack[e]=null
this.contextIndex--
t[this.threadID]=n}
t.clearProviders=function(){for(var e=this.contextIndex;0<=e;e--)this.contextStack[e][this.threadID]=this.contextValueStack[e]}
t.read=function(e){if(this.exhausted)return null
var t=ce
ce=this.threadID
var n=ye.current
ye.current=se
try{for(var o=[""],i=!1;o[0].length<e;){if(0===this.stack.length){this.exhausted=!0
var a=this.threadID
S[a]=S[0]
S[0]=a
break}var c=this.stack[this.stack.length-1]
if(i||c.childIndex>=c.children.length){var s=c.footer
""!==s&&(this.previousWasTextNode=!1)
this.stack.pop()
if("select"===c.type)this.currentSelectValue=null
else if(null!=c.type&&null!=c.type.type&&c.type.type.$$typeof===u)this.popProvider(c.type)
else if(c.type===p){this.suspenseDepth--
var l=o.pop()
if(i){i=!1
var d=c.fallbackFrame
if(!d)throw Error(r(303))
this.stack.push(d)
o[this.suspenseDepth]+="\x3c!--$!--\x3e"
continue}o[this.suspenseDepth]+=l}o[this.suspenseDepth]+=s}else{var x=c.children[c.childIndex++],_=""
try{_+=this.render(x,c.context,c.domNamespace)}catch(e){if(null!=e&&"function"===typeof e.then)throw Error(r(294))
throw e}o.length<=this.suspenseDepth&&o.push("")
o[this.suspenseDepth]+=_}}return o[0]}finally{ye.current=n,ce=t}}
t.render=function(e,t,n){if("string"===typeof e||"number"===typeof e){n=""+e
if(""===n)return""
if(this.makeStaticMarkup)return $(n)
if(this.previousWasTextNode)return"\x3c!-- --\x3e"+$(n)
this.previousWasTextNode=!0
return $(n)}t=Ae(e,t,this.threadID)
e=t.child
t=t.context
if(null===e||!1===e)return""
if(!i.isValidElement(e)){if(null!=e&&null!=e.$$typeof){n=e.$$typeof
if(n===c)throw Error(r(257))
throw Error(r(258,n.toString()))}e=he(e)
this.stack.push({type:null,domNamespace:n,children:e,childIndex:0,context:t,footer:""})
return""}var a=e.type
if("string"===typeof a)return this.renderDOM(e,t,n)
switch(a){case l:case _:case d:case f:case s:return e=he(e.props.children),this.stack.push({type:null,domNamespace:n,children:e,childIndex:0,context:t,footer:""}),""
case p:throw Error(r(294))}if("object"===typeof a&&null!==a)switch(a.$$typeof){case m:V={}
var b=a.render(e.props,e.ref)
b=ne(a.render,e.props,b,e.ref)
b=he(b)
this.stack.push({type:null,domNamespace:n,children:b,childIndex:0,context:t,footer:""})
return""
case h:return e=[i.createElement(a.type,o({ref:e.ref},e.props))],this.stack.push({type:null,domNamespace:n,children:e,childIndex:0,context:t,footer:""}),""
case u:return a=he(e.props.children),n={type:e,domNamespace:n,children:a,childIndex:0,context:t,footer:""},this.pushProvider(e),this.stack.push(n),""
case x:a=e.type
b=e.props
var k=this.threadID
E(a,k)
a=he(b.children(a[k]))
this.stack.push({type:e,domNamespace:n,children:a,childIndex:0,context:t,footer:""})
return""
case g:throw Error(r(338))
case y:switch(a=e.type,w(a),a._status){case 1:return e=[i.createElement(a._result,o({ref:e.ref},e.props))],this.stack.push({type:null,domNamespace:n,children:e,childIndex:0,context:t,footer:""}),""
case 2:throw a._result
default:throw Error(r(295))}case v:throw Error(r(343))}throw Error(r(130,null==a?a:typeof a,""))}
t.renderDOM=function(e,t,n){var i=e.type.toLowerCase()
n===le.html&&de(i)
if(!ve.hasOwnProperty(i)){if(!ge.test(i))throw Error(r(65,i))
ve[i]=!0}var a=e.props
if("input"===i)a=o({type:void 0},a,{defaultChecked:void 0,defaultValue:void 0,value:null!=a.value?a.value:a.defaultValue,checked:null!=a.checked?a.checked:a.defaultChecked})
else if("textarea"===i){var c=a.value
if(null==c){c=a.defaultValue
var s=a.children
if(null!=s){if(null!=c)throw Error(r(92))
if(Array.isArray(s)){if(!(1>=s.length))throw Error(r(93))
s=s[0]}c=""+s}null==c&&(c="")}a=o({},a,{value:void 0,children:""+c})}else if("select"===i)this.currentSelectValue=null!=a.value?a.value:a.defaultValue,a=o({},a,{value:void 0})
else if("option"===i){s=this.currentSelectValue
var l=ke(a.children)
if(null!=s){var d=null!=a.value?a.value+"":l
c=!1
if(Array.isArray(s)){for(var u=0;u<s.length;u++)if(""+s[u]===d){c=!0
break}}else c=""+s===d
a=o({selected:void 0,children:void 0},a,{selected:c,children:l})}}if(c=a){if(xe[i]&&(null!=c.children||null!=c.dangerouslySetInnerHTML))throw Error(r(137,i,""))
if(null!=c.dangerouslySetInnerHTML){if(null!=c.children)throw Error(r(60))
if(!("object"===typeof c.dangerouslySetInnerHTML&&"__html"in c.dangerouslySetInnerHTML))throw Error(r(61))}if(null!=c.style&&"object"!==typeof c.style)throw Error(r(62,""))}c=a
s=this.makeStaticMarkup
l=1===this.stack.length
d="<"+e.type
for(b in c)if(Ce.call(c,b)){var x=c[b]
if(null!=x){if("style"===b){u=void 0
var _="",m=""
for(u in x)if(x.hasOwnProperty(u)){var p=0===u.indexOf("--"),f=x[u]
if(null!=f){if(p)var h=u
else if(h=u,we.hasOwnProperty(h))h=we[h]
else{var y=h.replace(pe,"-$1").toLowerCase().replace(fe,"-ms-")
h=we[h]=y}_+=m+h+":"
m=u
p=null==f||"boolean"===typeof f||""===f?"":p||"number"!==typeof f||0===f||_e.hasOwnProperty(m)&&_e[m]?(""+f).trim():f+"px"
_+=p
m=";"}}x=_||null}u=null
e:if(p=i,f=c,-1===p.indexOf("-"))p="string"===typeof f.is
else switch(p){case"annotation-xml":case"color-profile":case"font-face":case"font-face-src":case"font-face-uri":case"font-face-format":case"font-face-name":case"missing-glyph":p=!1
break e
default:p=!0}p?Oe.hasOwnProperty(b)||(u=b,u=D(u)&&null!=x?u+'="'+$(x)+'"':""):u=H(b,x)
u&&(d+=" "+u)}}s||l&&(d+=' data-reactroot=""')
var b=d
c=""
ue.hasOwnProperty(i)?b+="/>":(b+=">",c="</"+e.type+">")
e:{s=a.dangerouslySetInnerHTML
if(null!=s){if(null!=s.__html){s=s.__html
break e}}else if(s=a.children,"string"===typeof s||"number"===typeof s){s=$(s)
break e}s=null}null!=s?(a=[],be.hasOwnProperty(i)&&"\n"===s.charAt(0)&&(b+="\n"),b+=s):a=he(a.children)
e=e.type
n=null==n||"http://www.w3.org/1999/xhtml"===n?de(e):"http://www.w3.org/2000/svg"===n&&"foreignObject"===e?"http://www.w3.org/1999/xhtml":n
this.stack.push({domNamespace:n,type:i,children:a,childIndex:0,context:t,footer:c})
this.previousWasTextNode=!1
return b}
return e}(),je={renderToString:function(e){e=new Se(e,!1)
try{return e.read(Infinity)}finally{e.destroy()}},renderToStaticMarkup:function(e){e=new Se(e,!0)
try{return e.read(Infinity)}finally{e.destroy()}},renderToNodeStream:function(){throw Error(r(207))},renderToStaticNodeStream:function(){throw Error(r(208))},version:"16.14.0"}
e.exports=je.default||je},"IEa/":function(e,t,n){"use strict"
var o=n("FeGr")
var i=[]
var r=[]
var a=o.makeRequestCallFromTimer(c)
function c(){if(r.length)throw r.shift()}e.exports=s
function s(e){var t
t=i.length?i.pop():new l
t.task=e
o(t)}function l(){this.task=null}l.prototype.call=function(){try{this.task.call()}catch(e){if(s.onerror)s.onerror(e)
else{r.push(e)
a()}}finally{this.task=null
i[i.length]=this}}},Jvcl:function(e,t,n){"use strict"
n.d(t,"b",(function(){return zt}))
n.d(t,"c",(function(){return Mt}))
var o=n("Ff2n")
var i=n("VTBJ")
var r=n("17x9")
var a=n.n(r)
var c=n("q1tI")
var s=n.n(c)
var l=function(){l=Object.assign||function(e){for(var t,n=1,o=arguments.length;n<o;n++){t=arguments[n]
for(var i in t)Object.prototype.hasOwnProperty.call(t,i)&&(e[i]=t[i])}return e}
return l.apply(this,arguments)}
var d={onActivate:r["func"],onAddUndo:r["func"],onBeforeAddUndo:r["func"],onBeforeExecCommand:r["func"],onBeforeGetContent:r["func"],onBeforeRenderUI:r["func"],onBeforeSetContent:r["func"],onBeforePaste:r["func"],onBlur:r["func"],onChange:r["func"],onClearUndos:r["func"],onClick:r["func"],onContextMenu:r["func"],onCopy:r["func"],onCut:r["func"],onDblclick:r["func"],onDeactivate:r["func"],onDirty:r["func"],onDrag:r["func"],onDragDrop:r["func"],onDragEnd:r["func"],onDragGesture:r["func"],onDragOver:r["func"],onDrop:r["func"],onExecCommand:r["func"],onFocus:r["func"],onFocusIn:r["func"],onFocusOut:r["func"],onGetContent:r["func"],onHide:r["func"],onInit:r["func"],onKeyDown:r["func"],onKeyPress:r["func"],onKeyUp:r["func"],onLoadContent:r["func"],onMouseDown:r["func"],onMouseEnter:r["func"],onMouseLeave:r["func"],onMouseMove:r["func"],onMouseOut:r["func"],onMouseOver:r["func"],onMouseUp:r["func"],onNodeChange:r["func"],onObjectResizeStart:r["func"],onObjectResized:r["func"],onObjectSelected:r["func"],onPaste:r["func"],onPostProcess:r["func"],onPostRender:r["func"],onPreProcess:r["func"],onProgressState:r["func"],onRedo:r["func"],onRemove:r["func"],onReset:r["func"],onSaveContent:r["func"],onSelectionChange:r["func"],onSetAttrib:r["func"],onSetContent:r["func"],onShow:r["func"],onSubmit:r["func"],onUndo:r["func"],onVisualAid:r["func"]}
var u=l({apiKey:r["string"],id:r["string"],inline:r["bool"],init:r["object"],initialValue:r["string"],onEditorChange:r["func"],outputFormat:r["oneOf"](["html","text"]),value:r["string"],tagName:r["string"],cloudChannel:r["string"],plugins:r["oneOfType"]([r["string"],r["array"]]),toolbar:r["oneOfType"]([r["string"],r["array"]]),disabled:r["bool"],textareaName:r["string"],tinymceScriptSrc:r["string"],scriptLoading:r["shape"]({async:r["bool"],defer:r["bool"],delay:r["number"]})},d)
var x=function(){for(var e=0,t=0,n=arguments.length;t<n;t++)e+=arguments[t].length
var o=Array(e),i=0
for(t=0;t<n;t++)for(var r=arguments[t],a=0,c=r.length;a<c;a++,i++)o[i]=r[a]
return o}
var _=function(e){return"function"===typeof e}
var m=function(e){return e in d}
var p=function(e){return e.substr(2)}
var f=function(e,t,n,o){return h(e.on.bind(e),e.off.bind(e),(function(t){return function(n){return t(n,e)}}),t,n,o)}
var h=function(e,t,n,o,i,r){var a=Object.keys(o).filter(m)
var c=Object.keys(i).filter(m)
var s=a.filter((function(e){return void 0===i[e]}))
var l=c.filter((function(e){return void 0!==o[e]&&o[e]!=i[e]}))
var d=c.filter((function(e){return void 0===o[e]}))
x(s,l).forEach((function(e){var n=p(e)
var o=r[n]
t(n,o)
delete r[n]}))
x(l,d).forEach((function(t){var o=i[t]
if(void 0!==o){var a=p(t)
var c=n(o)
r[a]=c
e(a,c)}}))}
var y=0
var b=function(e){var t=Date.now()
var n=Math.floor(1e9*Math.random())
y++
return e+"_"+n+y+String(t)}
var g=function(e){return null!==e&&"textarea"===e.tagName.toLowerCase()}
var v=function(e){if("undefined"===typeof e||""===e)return[]
return Array.isArray(e)?e:e.split(" ")}
var w=function(e,t){return v(e).concat(v(t))}
var k=function(){return{listeners:[],scriptId:b("tiny-script"),scriptLoading:false,scriptLoaded:false}}
var C=function(){var e=k()
var t=function(e,t,n,o,i,r){var a=t.createElement("script")
a.referrerPolicy="origin"
a.type="application/javascript"
a.id=e
a.src=n
a.async=o
a.defer=i
var c=function(){a.removeEventListener("load",c)
r()}
a.addEventListener("load",c)
t.head&&t.head.appendChild(a)}
var n=function(n,o,i,r,a,c){var s=function(){return t(e.scriptId,n,o,i,r,(function(){e.listeners.forEach((function(e){return e()}))
e.scriptLoaded=true}))}
if(e.scriptLoaded)c()
else{e.listeners.push(c)
if(!e.scriptLoading){e.scriptLoading=true
a>0?setTimeout(s,a):s()}}}
var o=function(){e=k()}
return{load:n,reinitialize:o}}
var O=C()
var E=n("4le0")
var A=(S=function(e,t){S=Object.setPrototypeOf||{__proto__:[]}instanceof Array&&function(e,t){e.__proto__=t}||function(e,t){for(var n in t)Object.prototype.hasOwnProperty.call(t,n)&&(e[n]=t[n])}
return S(e,t)},function(e,t){S(e,t)
function n(){this.constructor=e}e.prototype=null===t?Object.create(t):(n.prototype=t.prototype,new n)})
var S
var j=function(){j=Object.assign||function(e){for(var t,n=1,o=arguments.length;n<o;n++){t=arguments[n]
for(var i in t)Object.prototype.hasOwnProperty.call(t,i)&&(e[i]=t[i])}return e}
return j.apply(this,arguments)}
var I=function(e){A(t,e)
function t(t){var n,o,i
var r=e.call(this,t)||this
r.handleEditorChange=function(e){var t
var n=r.editor
if(n){var o=n.getContent({format:r.props.outputFormat})
if(o!==r.currentContent){r.currentContent=o
_(r.props.onEditorChange)&&r.props.onEditorChange(null!==(t=r.currentContent)&&void 0!==t?t:"",n)}}}
r.handleInit=function(e){var t=r.editor
if(t){t.setContent(r.getInitialValue())
t.undoManager.clear()
t.undoManager.add()
t.setDirty(false)
_(r.props.onEditorChange)&&t.on("change keyup setcontent",r.handleEditorChange)
_(r.props.onInit)&&r.props.onInit(e,t)
f(t,{},r.props,r.boundHandlers)}}
r.initialise=function(){var e=r.elementRef.current
if(!e)return
var t=Object(E["a"])()
if(!t)throw new Error("tinymce should have been loaded into global scope")
var n=j(j({},r.props.init),{selector:void 0,target:e,readonly:r.props.disabled,inline:r.inline,plugins:w(r.props.init&&r.props.init.plugins,r.props.plugins),toolbar:r.props.toolbar||r.props.init&&r.props.init.toolbar,setup:function(e){r.editor=e
e.on("init",r.handleInit)
r.props.init&&_(r.props.init.setup)&&r.props.init.setup(e)}})
g(r.elementRef.current)&&(r.elementRef.current.style.visibility="")
t.init(n)}
r.id=r.props.id||b("tiny-react")
r.elementRef=c["createRef"]()
r.inline=null!==(i=null!==(n=r.props.inline)&&void 0!==n?n:null===(o=r.props.init)||void 0===o?void 0:o.inline)&&void 0!==i&&i
r.boundHandlers={}
return r}t.prototype.componentDidUpdate=function(e){var t=this
var n
if(this.editor&&this.editor.initialized){f(this.editor,e,this.props,this.boundHandlers)
this.currentContent=null!==(n=this.currentContent)&&void 0!==n?n:this.editor.getContent({format:this.props.outputFormat})
if("string"===typeof this.props.value&&this.props.value!==e.value&&this.props.value!==this.currentContent){var o=this.editor
o.undoManager.transact((function(){return o.setContent(t.props.value)}))}"boolean"===typeof this.props.disabled&&this.props.disabled!==e.disabled&&this.editor.setMode(this.props.disabled?"readonly":"design")}}
t.prototype.componentDidMount=function(){var e,t,n,o,i,r
null!==Object(E["a"])()?this.initialise():this.elementRef.current&&this.elementRef.current.ownerDocument&&O.load(this.elementRef.current.ownerDocument,this.getScriptSrc(),null!==(t=null===(e=this.props.scriptLoading)||void 0===e?void 0:e.async)&&void 0!==t&&t,null!==(o=null===(n=this.props.scriptLoading)||void 0===n?void 0:n.defer)&&void 0!==o&&o,null!==(r=null===(i=this.props.scriptLoading)||void 0===i?void 0:i.delay)&&void 0!==r?r:0,this.initialise)}
t.prototype.componentWillUnmount=function(){var e=this
var t=this.editor
if(t){t.off("init",this.handleInit)
if(t.initialized){t.off("change keyup setcontent",this.handleEditorChange)
Object.keys(this.boundHandlers).forEach((function(n){t.off(n,e.boundHandlers[n])}))
this.boundHandlers={}}t.remove()}}
t.prototype.render=function(){return this.inline?this.renderInline():this.renderIframe()}
t.prototype.renderInline=function(){var e=this.props.tagName,t=void 0===e?"div":e
return c["createElement"](t,{ref:this.elementRef,id:this.id})}
t.prototype.renderIframe=function(){return c["createElement"]("textarea",{ref:this.elementRef,style:{visibility:"hidden"},name:this.props.textareaName,id:this.id})}
t.prototype.getScriptSrc=function(){if("string"===typeof this.props.tinymceScriptSrc)return this.props.tinymceScriptSrc
var e=this.props.cloudChannel
var t=this.props.apiKey?this.props.apiKey:"no-api-key"
return"https://cdn.tiny.cloud/1/"+t+"/tinymce/"+e+"/tinymce.min.js"}
t.prototype.getInitialValue=function(){return"string"===typeof this.props.value?this.props.value:"string"===typeof this.props.initialValue?this.props.initialValue:""}
t.propTypes=u
t.defaultProps={cloudChannel:"5"}
return t}(c["Component"])
var T=n("LvDl")
var L=n.n(T)
var B=n("J2CL")
var D=n("1OyB")
var R=n("vuIU")
var F=n("Ji7U")
var M=n("LK+K")
var z=n("hPGw")
var P=s.a.createElement("path",{d:"M1807.05882,1637.70588 C1807.05882,1668.76471 1781.76,1694.17647 1750.58824,1694.17647 L169.411765,1694.17647 C138.24,1694.17647 112.941176,1668.76471 112.941176,1637.70588 L112.941176,734.176471 C112.941176,703.117647 138.24,677.705882 169.411765,677.705882 L1750.58824,677.705882 C1781.76,677.705882 1807.05882,703.117647 1807.05882,734.176471 L1807.05882,1637.70588 Z M1750.58824,564.764706 L1021.32706,564.764706 C1036.23529,477.8 1087.28471,451.258824 1154.71059,417.602353 C1244.04706,372.990588 1355.29412,317.310588 1355.29412,113 L1242.35294,113 C1242.35294,247.512941 1184.41412,276.425882 1104.11294,316.632941 C1023.81176,356.727059 926.569412,406.872941 907.595294,564.764706 L169.411765,564.764706 C76.0094118,564.764706 0,640.774118 0,734.176471 L0,1637.70588 C0,1731.10824 76.0094118,1807.11765 169.411765,1807.11765 L1750.58824,1807.11765 C1843.99059,1807.11765 1920,1731.10824 1920,1637.70588 L1920,734.176471 C1920,640.774118 1843.99059,564.764706 1750.58824,564.764706 L1750.58824,564.764706 Z M1185.88235,1242.41176 L734.117647,1242.41176 C702.945882,1242.41176 677.647059,1267.71059 677.647059,1298.88235 L677.647059,1411.82353 C677.647059,1442.99529 702.945882,1468.29412 734.117647,1468.29412 L1185.88235,1468.29412 C1217.05412,1468.29412 1242.35294,1442.99529 1242.35294,1411.82353 L1242.35294,1298.88235 C1242.35294,1267.71059 1217.05412,1242.41176 1185.88235,1242.41176 M1524.70588,1242.41176 L1411.76471,1242.41176 C1380.59294,1242.41176 1355.29412,1267.71059 1355.29412,1298.88235 L1355.29412,1411.82353 C1355.29412,1442.99529 1380.59294,1468.29412 1411.76471,1468.29412 L1524.70588,1468.29412 C1555.87765,1468.29412 1581.17647,1442.99529 1581.17647,1411.82353 L1581.17647,1298.88235 C1581.17647,1267.71059 1555.87765,1242.41176 1524.70588,1242.41176 M508.235294,1242.41176 L395.294118,1242.41176 C364.122353,1242.41176 338.823529,1267.71059 338.823529,1298.88235 L338.823529,1411.82353 C338.823529,1442.99529 364.122353,1468.29412 395.294118,1468.29412 L508.235294,1468.29412 C539.407059,1468.29412 564.705882,1442.99529 564.705882,1411.82353 L564.705882,1298.88235 C564.705882,1267.71059 539.407059,1242.41176 508.235294,1242.41176 M508.235294,903.588235 L395.294118,903.588235 C364.122353,903.588235 338.823529,928.887059 338.823529,960.058824 L338.823529,1073 C338.823529,1104.17176 364.122353,1129.47059 395.294118,1129.47059 L508.235294,1129.47059 C539.407059,1129.47059 564.705882,1104.17176 564.705882,1073 L564.705882,960.058824 C564.705882,928.887059 539.407059,903.588235 508.235294,903.588235 M734.117647,1129.47059 L847.058824,1129.47059 C878.230588,1129.47059 903.529412,1104.17176 903.529412,1073 L903.529412,960.058824 C903.529412,928.887059 878.230588,903.588235 847.058824,903.588235 L734.117647,903.588235 C702.945882,903.588235 677.647059,928.887059 677.647059,960.058824 L677.647059,1073 C677.647059,1104.17176 702.945882,1129.47059 734.117647,1129.47059 M1185.88235,903.588235 L1072.94118,903.588235 C1041.76941,903.588235 1016.47059,928.887059 1016.47059,960.058824 L1016.47059,1073 C1016.47059,1104.17176 1041.76941,1129.47059 1072.94118,1129.47059 L1185.88235,1129.47059 C1217.05412,1129.47059 1242.35294,1104.17176 1242.35294,1073 L1242.35294,960.058824 C1242.35294,928.887059 1217.05412,903.588235 1185.88235,903.588235 M1524.70588,903.588235 L1411.76471,903.588235 C1380.59294,903.588235 1355.29412,928.887059 1355.29412,960.058824 L1355.29412,1073 C1355.29412,1104.17176 1380.59294,1129.47059 1411.76471,1129.47059 L1524.70588,1129.47059 C1555.87765,1129.47059 1581.17647,1104.17176 1581.17647,1073 L1581.17647,960.058824 C1581.17647,928.887059 1555.87765,903.588235 1524.70588,903.588235",fillRule:"evenodd",stroke:"none",strokeWidth:"1"})
var N=function(e){Object(F["a"])(n,e)
var t=Object(M["a"])(n)
function n(){Object(D["a"])(this,n)
return t.apply(this,arguments)}Object(R["a"])(n,[{key:"render",value:function(){return s.a.createElement(z["a"],Object.assign({},this.props,{name:"IconKeyboardShortcuts",viewBox:"0 0 1920 1920"}),P)}}])
n.displayName="IconKeyboardShortcutsLine"
return n}(c["Component"])
N.glyphName="keyboard-shortcuts"
N.variant="Line"
N.propTypes=Object(i["a"])({},z["a"].propTypes)
var U=n("L+/K")
var $=n("uSnb")
var H=n("n12J")
var W=n("eGSd")
function q(e){const t=document.cookie.match("(^|[^;]+)\\s*"+e+"\\s*=\\s*([^;]+)")
return t?decodeURIComponent(t.pop()):void 0}var V=n("NFDp")
var G=n("TSYQ")
var K=n.n(G)
var Z=n("b5/e")
var Y=n("GEYT")
var J=n.n(Y)
var X={INTERIM_DELAY:100,scrollIntoViewWDelay(e,t){setTimeout(()=>{J.a.scrollIntoView(e,t)},this.INTERIM_DELAY)}}
var Q=n("DWdj")
var ee=n("kyQv")
function te(e,t){const n=e.getElement()
if("selectionStart"in n){const e=n.value.substr(0,n.selectionStart)
const o=n.value.substr(n.selectionEnd,n.value.length)
n.value=e+t+o}else if(document.selection){n.focus()
document.selection.createRange().text=t}else n.value+=t}function ne(e,t){if(e.isHidden()){te(e,t)
return null}X.scrollIntoViewWDelay(e.iframeElement,{})
e.execCommand("mceInsertContent",false,t,{skip_focus:true})
return e.selection.getEnd()}function oe(e){return e&&"img"===e.nodeName.toLowerCase()}function ie(e){return e&&"a"===e.nodeName.toLowerCase()}function re(e){const t=e.selection
const n=t.getRng()
return oe(t.getNode())&&ie(n.startContainer)&&n.startContainer===n.endContainer}function ae(e,t){let n=""
n=re(e)?Object(Z["d"])(e.selection.getRng().startContainer,t):Object(Z["b"])(Object(i["a"])({},t))
return ne(e,n)}function ce(e,t,n){const o=parseFloat(e.dom.doc.defaultView.getComputedStyle(e.dom.doc.body).getPropertyValue("font-size"))||1
const i=e.selection.getNode()
const r=i?parseFloat(e.dom.doc.defaultView.getComputedStyle(i).getPropertyValue("font-size"))||1:o
let a=`/equation_images/${encodeURIComponent(encodeURIComponent(t))}?scale=${r/o}`
n&&(a=n+a)
const c=document.createElement("img")
c.setAttribute("alt","LaTeX: "+t)
c.setAttribute("title",t)
c.setAttribute("class","equation_image")
c.setAttribute("data-equation-content",t)
c.setAttribute("src",a)
c.setAttribute("data-ignore-a11y-check","")
return ne(e,c.outerHTML)}function se(e,t){const n=t.selectionDetails&&t.selectionDetails.node?t.selectionDetails.node:e.selection.getNode()
return e.dom.getParent(n,"a")}function le(e){let t=e.selection.getContent()
t=e.dom.decode(t)
return!!t&&""!=t}function de(e,t){return!e.isHidden()&&(t&&(se(e,t)||!!t.selectedContent)||le(e))}function ue(e){const t=document.implementation.createHTMLDocument()
t.body.innerHTML=e.trim()
return t.body.children}function xe(e){const t=e.selection.getContent()
return e.dom.$(ue(t)).is("img")}function _e(e){return!e.isHidden()&&xe(e)}function me(e){const t=e.embed&&e.embed.type
e.class=K()(e.class,{instructure_file_link:true,instructure_scribd_file:"scribd"===t||e["data-canvas-previewable"],instructure_image_thumbnail:"image"===t,instructure_video_link:"video"===t,instructure_audio_link:"audio"===t,auto_open:e.embed&&e.embed.autoOpenPreview,inline_disabled:e.embed&&e.embed.disablePreview})
"video"!=e.embed.type&&"audio"!=e.embed.type||(e.id="media_comment_"+(e.embed.id||"maybe"))}function pe(e,t){const n=Object(i["a"])({},t)
if(n.embed){me(n)
delete n.embed}return he(e,n)}function fe(e,t,n){if(e.forceRename)return e.text
return ye(t.selection,n)||e.text}function he(e,t){const n=e.selection.getNode()
const o=Object(Q["b"])(e,n)
const i=e.selection.getContent()
const r=e.selection.getContent({format:"text"})
const a=Object(Q["e"])(i)
const c=a&&fe(t,e,o)
const s={id:t.id,href:Object(Q["a"])(t.href||t.url),target:t.target,class:t.class,title:t.title,"data-canvas-previewable":t["data-canvas-previewable"]}
"_blank"===s.target&&(s.rel="noopener noreferrer")
o&&!e.selection.isCollapsed()?be(e,o,c,s):i?t.userText&&r!==c?ge(e,n,c,s):ge(e,n,void 0,s):ge(e,n,c,s)
return e.selection.getEnd()}function ye(e,t){return t?t.innerText:e.getContent({format:"text"})}function be(e,t,n,o){n&&t.innerText!==n&&(t.innerText=n)
e.dom.setAttribs(t,o)
e.selection.select(t)
e.undoManager.add()}function ge(e,t,n,o){Object(Q["c"])(t)?ve(e,t,o):n?ne(e,e.dom.createHTML("a",o,e.dom.encode(n))):e.execCommand("mceInsertLink",false,o)}function ve(e,t,n){const o="IMG"===t.tagName?t:e.dom.select("img",t)[0]
if(o){const t=e.dom.create("a",n)
o.parentNode.insertBefore(t,o)
t.appendChild(o)}}function we(e,t){if(e.selection.isCollapsed()){var n
let o=ne(e,Object(Z["e"])(t))
const i=Object(ee["g"])(t)
o=o.querySelector(`iframe[src="${i}"]`)
null!==(n=o)&&void 0!==n&&n.parentElement&&e.dom.setAttrib(o.parentElement,"contenteditable",false)
return o}return pe(e,Object(i["a"])(Object(i["a"])({},t),{},{href:Object(ee["g"])(t)}))}function ke(e,t){if(e.selection.isCollapsed()){var n
let o=ne(e,Object(Z["a"])(t))
const i=Object(ee["g"])(t)
o=o.querySelector(`iframe[src="${i}"]`)
null!==(n=o)&&void 0!==n&&n.parentElement&&e.dom.setAttrib(o.parentElement,"contenteditable",false)
return o}return pe(e,Object(i["a"])(Object(i["a"])({},t),{},{href:Object(ee["g"])(t)}))}var Ce=n("QUlp")
var Oe=n("20cW")
var Ee=n.n(Oe)
var Ae=n("0T/Z")
function Se(e){if(void 0!==e){let t=e
"string"===typeof e&&(t=e.split(",").map(e=>e.replace(/\s/g,"")))
return t}return e}var je=n("n/1O")
async function Ie(e){if(!e||!e.jwt||!e.host)return null
const t=new je["a"](e)
try{const e=await t.getSession()
return e.canvasUrl}catch(e){return null}}var Te=n("uTvJ")
var Le=n("QV6e")
var Be=n("lcQH")
var De=n("ODXe")
var Re=n("i8i4")
var Fe=n.n(Re)
var Me=n("/7Jz")
var ze=n("3zPy")
var Pe=n.n(ze)
var Ne=n("Zgll")
var Ue=n("Cp+0")
var $e=n("TstA")
var He=n("sULQ")
var We=n("ZbPE")
var qe=s.a.createElement("path",{d:"M925.966182,1226.25955 C944.762449,1253.5558 975.234883,1253.55919 994.033486,1226.25955 L1345.1073,716.424242 C1363.90357,689.127987 1352.28747,667 1319.14817,667 L600.851498,667 C567.718398,667 556.093763,689.124596 574.892365,716.424242 L925.966182,1226.25955 Z",fillRule:"evenodd",stroke:"none",strokeWidth:"1",transform:"matrix(0 1 1 0 -.278 .278)"})
var Ve=function(e){Object(F["a"])(n,e)
var t=Object(M["a"])(n)
function n(){Object(D["a"])(this,n)
return t.apply(this,arguments)}Object(R["a"])(n,[{key:"render",value:function(){return s.a.createElement(z["a"],Object.assign({},this.props,{name:"IconMiniArrowEnd",viewBox:"0 0 1920 1920",bidirectional:true}),qe)}}])
n.displayName="IconMiniArrowEndLine"
return n}(c["Component"])
Ve.glyphName="mini-arrow-end"
Ve.variant="Line"
Ve.propTypes=Object(i["a"])({},z["a"].propTypes)
var Ge=s.a.createElement("path",{d:"M960,2 C1489.35529,2 1920,432.644706 1920,962 C1920,1491.35529 1489.35529,1922 960,1922 C430.644706,1922 0,1491.35529 0,962 C0,432.644706 430.644706,2 960,2 Z M960,114.941176 C492.875294,114.941176 112.941176,494.875294 112.941176,962 C112.941176,1429.12471 492.875294,1809.05882 960,1809.05882 C1427.12471,1809.05882 1807.05882,1429.12471 1807.05882,962 C1807.05882,494.875294 1427.12471,114.941176 960,114.941176 Z M1396.704,635.232 L1121.504,635.232 L757.450667,635.232 L482.144,635.232 C451.104,635.232 426.677333,659.658667 426.677333,690.698667 C426.677333,721.845333 451.104,746.272 482.144,746.272 L757.450667,746.272 L757.450667,1125.792 L757.450667,1259.01867 L757.450667,1634.05867 C757.450667,1665.20533 781.770667,1689.632 812.917333,1689.632 C843.957333,1689.632 868.384,1665.20533 868.384,1634.05867 L868.384,1259.01867 L1014.83733,1259.01867 L1014.83733,1634.05867 C1014.83733,1665.20533 1039.264,1689.632 1070.304,1689.632 C1101.45067,1689.632 1125.87733,1665.20533 1125.87733,1634.05867 L1125.87733,1259.01867 L1125.87733,1125.792 L1125.87733,744.032 L1401.184,744.032 C1432.224,744.032 1456.65067,719.605333 1456.65067,688.565333 C1449.93067,659.658667 1425.61067,635.232 1396.704,635.232 M939.413333,320.021333 C1013.01333,320.021333 1072.64,379.648 1072.64,453.248 C1072.64,526.741333 1013.01333,586.368 939.413333,586.368 C865.92,586.368 806.186667,526.741333 806.186667,453.248 C806.186667,379.648 865.92,320.021333 939.413333,320.021333",fillRule:"evenodd",stroke:"none",strokeWidth:"1"})
var Ke=function(e){Object(F["a"])(n,e)
var t=Object(M["a"])(n)
function n(){Object(D["a"])(this,n)
return t.apply(this,arguments)}Object(R["a"])(n,[{key:"render",value:function(){return s.a.createElement(z["a"],Object.assign({},this.props,{name:"IconA11y",viewBox:"0 0 1920 1920"}),Ge)}}])
n.displayName="IconA11yLine"
return n}(c["Component"])
Ke.glyphName="a11y"
Ke.variant="Line"
Ke.propTypes=Object(i["a"])({},z["a"].propTypes)
var Ze=s.a.createElement("path",{d:"M1158.513 -0.0123680261L1158.513 123.667893 1709.01384 123.667893 123.680261 1708.87779 123.680261 1158.50063 0 1158.50063 0 1920 761.499365 1920 761.499365 1796.31974 211.122205 1796.31974 1796.33211 211.109837 1796.33211 761.610678 1920.01237 761.610678 1920.01237 -0.0123680261z",fillRule:"evenodd",stroke:"none",strokeWidth:"1"})
var Ye=function(e){Object(F["a"])(n,e)
var t=Object(M["a"])(n)
function n(){Object(D["a"])(this,n)
return t.apply(this,arguments)}Object(R["a"])(n,[{key:"render",value:function(){return s.a.createElement(z["a"],Object.assign({},this.props,{name:"IconFullScreen",viewBox:"0 0 1920 1920"}),Ze)}}])
n.displayName="IconFullScreenLine"
return n}(c["Component"])
Ye.glyphName="full-screen"
Ye.variant="Line"
Ye.propTypes=Object(i["a"])({},z["a"].propTypes)
var Je=n("01jY")
var Xe=n("q8CT")
function Qe(e){return e.dragging?s.a.createElement("div",{style:{cursor:"ns-resize",position:"fixed",top:0,left:0,width:"100%",height:"100%",zIndex:"1000000000000"}}):null}Qe.propTypes={dragging:r["bool"].isRequired}
const et=16
function tt(e){const t=Object(c["useState"])(false),n=Object(De["a"])(t,2),o=n[0],i=n[1]
const r=Object(c["useState"])(false),a=Object(De["a"])(r,2),l=a[0],d=a[1]
return s.a.createElement(H["a"],{"aria-label":Object(V["a"])("Drag handle. Use up and down arrows to resize"),title:Object(V["a"])("Resize"),as:"span",borderRadius:"medium",display:"inline-block",withFocusOutline:l,padding:"0 xx-small",position:"relative",role:"button","data-btn-id":e["data-btn-id"],tabIndex:e.tabIndex,onKeyDown:function(t){if(t.keyCode===Pe.a.codes.up){t.preventDefault()
t.stopPropagation()
e.onDrag(t,{deltaY:-16})}else if(t.keyCode===Pe.a.codes.down){t.preventDefault()
t.stopPropagation()
e.onDrag(t,{deltaY:et})}},onFocus:function(t){var n
d(true)
null===(n=e.onFocus)||void 0===n||n.call(e,t)},onBlur:function(){d(false)}},s.a.createElement(Je["DraggableCore"],{offsetParent:document.body,onDrag:e.onDrag,onStart:function(){i(true)},onStop:function(){i(false)}},s.a.createElement(H["a"],{cursor:"ns-resize"},s.a.createElement(Xe["a"],null))),s.a.createElement(Qe,{dragging:o}))}tt.propTypes={onDrag:r["func"],onFocus:r["func"],tabIndex:r["string"],"data-btn-id":r["string"]}
tt.defaultProps={onDrag:()=>{},tabIndex:"-1"}
const nt="WYSIWYG"
const ot="PRETTY"
const it="RAW"
st.propTypes={onChangeView:r["func"].isRequired,path:Object(r["arrayOf"])(r["string"]),wordCount:r["number"],editorView:Object(r["oneOf"])(["WYSIWYG","PRETTY","RAW"]),onResize:r["func"],onKBShortcutModalOpen:r["func"].isRequired,onA11yChecker:r["func"].isRequired,onFullscreen:r["func"].isRequired,use_rce_a11y_checker_notifications:r["bool"],preferredHtmlEditor:Object(r["oneOf"])(["PRETTY","RAW"]),readOnly:r["bool"],a11yBadgeColor:r["string"],a11yErrorsCount:r["number"]}
st.defaultProps={a11yBadgeColor:"#0374B5",a11yErrorsCount:0}
function rt({path:e}){return e.reduce((e,t,n)=>e.concat(s.a.createElement("span",{key:`${t}-${n}`},s.a.createElement(We["a"],null,n>0?s.a.createElement(Ve,null):null,t))),[])}function at(){return s.a.createElement(z["a"],{viewBox:"0 0 24 24",fontSize:"24px"},s.a.createElement("g",{role:"presentation"},s.a.createElement("text",{textAnchor:"middle",x:"12px",y:"18px",fontSize:"16"},"</>")))}function ct(e){const t=Fe.a.findDOMNode(e)
return t?Array.from(t.querySelectorAll("[tabindex]")):[]}function st(e){const t=Object(c["useState"])(null),n=Object(De["a"])(t,2),o=n[0],i=n[1]
const r=Object(c["useState"])(false),a=Object(De["a"])(r,2),l=a[0],d=a[1]
const u=Object(c["useRef"])(null)
Object(c["useEffect"])(()=>{const e=ct(u.current)
i(e[0].getAttribute("data-btn-id"))
e[0].setAttribute("tabIndex","0")},[])
Object(c["useEffect"])(()=>{m()&&/rce-kbshortcut-btn|rce-a11y-btn/.test(o)&&i("rce-edit-btn")
const e=setTimeout(()=>{d(!m())},100)
return()=>clearTimeout(e)},[e.editorView])
function x(){if(e.preferredHtmlEditor)return e.preferredHtmlEditor
return ot}function _(e){if(!e.shiftKey)return x()
return x()===it?ot:it}function m(){return e.editorView!==nt}function p(e){const t=o===e?"0":"-1"
return t}function f(){const t=Object(V["a"])("Accessibility Checker")
const n=s.a.createElement(Ne["a"],{"data-btn-id":"rce-a11y-btn",color:"primary",title:t,tabIndex:p("rce-a11y-btn"),onClick:t=>{t.target.focus()
e.onA11yChecker()},onFocus:()=>i("rce-a11y-btn"),screenReaderLabel:t,withBackground:false,withBorder:false},s.a.createElement(Ke,null))
if(!e.use_rce_a11y_checker_notifications||e.a11yErrorsCount<=0)return n
return s.a.createElement(B["a"],{theme:{[He["a"].theme]:{colorPrimary:e.a11yBadgeColor}}},s.a.createElement(He["a"],{count:e.a11yErrorsCount,countUntil:100},n))}function h(){return x()===it?Object(V["a"])("Shift-O to open the pretty html editor."):Object(V["a"])("The pretty html editor is not keyboard accessible. Press Shift O to open the raw html editor.")}function y(){if(e.readOnly)return null
if(e.editorView===it&&!("requestFullscreen"in document.body))return null
const t=Object(V["a"])("Fullscreen")
return s.a.createElement(Ne["a"],{"data-btn-id":"rce-fullscreen-btn",color:"primary",title:t,tabIndex:p("rce-fullscreen-btn"),onClick:t=>{t.target.focus()
e.onFullscreen()},onFocus:()=>i("rce-fullscreen-btn"),screenReaderLabel:t,withBackground:false,withBorder:false},s.a.createElement(Ye,null))}const b=m()?"end":"start"
return s.a.createElement($e["a"],{margin:"x-small 0 x-small x-small","data-testid":"RCEStatusBar",justifyItems:b,ref:u,onKeyDown:function(e){const t=ct(u.current).filter(e=>!e.disabled)
const n=t.findIndex(e=>e.getAttribute("data-btn-id")===o)
let r
if(e.keyCode===Pe.a.codes.right)r=(n+1)%t.length
else{if(e.keyCode!==Pe.a.codes.left)return
r=(n+t.length-1)%t.length}t[r].focus()
i(t[r].getAttribute("data-btn-id"))}},s.a.createElement($e["a"].Item,{shouldGrow:true},m()?function(){const t=e.editorView===ot?Object(V["a"])("Sadly, the pretty HTML editor is not keyboard accessible. Access the raw HTML editor here."):Object(V["a"])("Access the pretty HTML editor")
const n=e.editorView===ot?Object(V["a"])("Raw HTML Editor"):Object(V["a"])("Pretty HTML Editor")
return s.a.createElement(H["a"],{"data-testid":"html-editor-message"},s.a.createElement(Ue["a"],{"data-btn-id":"rce-editormessage-btn",margin:"0 small",title:t,tabIndex:p("rce-editormessage-btn"),onClick:t=>{t.target.focus()
e.onChangeView(e.editorView===ot?it:ot)},onFocus:()=>i("rce-editormessage-btn")},n))}():s.a.createElement(H["a"],{"data-testid":"whole-status-bar-path"},rt(e))),s.a.createElement($e["a"].Item,{role:"toolbar",title:Object(V["a"])("Editor Statusbar")},function(){if(m())return null
const t=Object(V["a"])("View keyboard shortcuts")
return s.a.createElement(H["a"],{display:"inline-block",padding:"0 x-small"},s.a.createElement(Ne["a"],{"data-btn-id":"rce-kbshortcut-btn",color:"primary","aria-haspopup":"dialog",title:t,tabIndex:p("rce-kbshortcut-btn"),onClick:t=>{t.target.focus()
e.onKBShortcutModalOpen()},onFocus:()=>i("rce-kbshortcut-btn"),screenReaderLabel:t,withBackground:false,withBorder:false},s.a.createElement(N,null)),e.readOnly||f())}(),s.a.createElement("div",{className:Object(Me["css"])(lt.separator)}),function(){if(m())return null
const t=Object(V["a"])("{count, plural,\n         =0 {0 words}\n        one {1 word}\n      other {# words}\n    }",{count:e.wordCount})
return s.a.createElement(H["a"],{display:"inline-block",padding:"0 small","data-testid":"status-bar-word-count"},s.a.createElement(We["a"],null,t))}(),s.a.createElement("div",{className:Object(Me["css"])(lt.separator)}),function(){const t=Object(V["a"])("Switch to the html editor")
const n=Object(V["a"])("Switch to the rich text editor")
const o=Object(V["a"])("Click or shift-click for the html editor.")
const r=m()?n:t
const a=m()?n:o
return s.a.createElement(H["a"],{display:"inline-block",padding:"0 0 0 x-small"},e.readOnly||s.a.createElement(Ne["a"],{"data-btn-id":"rce-edit-btn",color:"primary",onClick:t=>{e.onChangeView(m()?nt:_(t))},onKeyUp:t=>{if(e.editorView===nt&&t.shiftKey&&79===t.keyCode){const t=x()===it?ot:it
e.onChangeView(t)}},onFocus:()=>i("rce-edit-btn"),title:a,tabIndex:p("rce-edit-btn"),"aria-describedby":l?"edit-button-desc":void 0,screenReaderLabel:r,withBackground:false,withBorder:false},at()),l&&s.a.createElement("span",{style:{display:"none"},id:"edit-button-desc"},h()))}(),y(),s.a.createElement(tt,{"data-btn-id":"rce-resize-handle",onDrag:e.onResize,tabIndex:p("rce-resize-handle"),onFocus:()=>{i("rce-resize-handle")}})))}const lt=Me["StyleSheet"].create({separator:{display:"inline-block","box-sizing":"border-box","border-right":"1px solid #ccc",width:"1px",height:"1.5rem",position:"relative",top:".5rem"}})
const dt="ViewChange"
const ut={position:"absolute",left:"-9999px"}
class xt extends c["Component"]{constructor(...e){super(...e)
this.state={visible:false}
this.handleFocus=()=>{this.setState({visible:true})}
this.handleBlur=()=>{this.setState({visible:false})}}focus(){this.btnRef.focus()
this.setState({visible:true})}renderButton(){return s.a.createElement(Ne["a"],{"data-testid":"ShowOnFocusButton__button",color:"primary","aria-haspopup":"dialog",margin:this.props.margin,ref:e=>{this.btnRef=e},onFocus:this.handleFocus,onBlur:this.handleBlur,onClick:this.props.onClick,screenReaderLabel:this.props.screenReaderLabel,withBackground:false,withBorder:false},this.props.children)}render(){return s.a.createElement("div",{"data-testid":"ShowOnFocusButton__wrapper",style:this.state.visible?null:ut},this.renderButton())}}xt.propTypes={children:Object(r["oneOfType"])([r["node"],r["func"]]).isRequired,onClick:r["func"],screenReaderLabel:r["string"].isRequired,margin:r["string"]}
var _t=n("o4+2")
var mt=n("6RTY")
var pt=n("vlle")
function ft({borders:e,colors:t,forms:n,shadows:o,spacing:i,typography:r}){const a={canvasBackgroundColor:t.white,canvasTextColor:t.textDarkest,canvasErrorColor:t.textDanger,canvasWarningColor:t.textWarning,canvasInfoColor:t.textInfo,canvasSuccessColor:t.textSuccess,canvasBorderColor:t.borderMedium,toolbarButtonHoverBackground:Object(_t["a"])(t.backgroundLightest,5),canvasBrandColor:t.brand,activeMenuItemBackground:t.backgroundBrand,activeMenuItemLabelColor:t.textLightest,tableSelectorHighlightColor:Object(mt["a"])(Object(pt["a"])(t.brand,10),50),canvasLinkColor:t.link,canvasLinkDecoration:"none",canvasButtonBackground:t.backgroundLightest,canvasButtonBorderColor:"transparent",canvasButtonColor:t.textDarkest,canvasButtonHoverBackground:t.backgroundLightest,canvasButtonHoverColor:t.brand,canvasButtonActiveBackground:t.backgroundLightest,canvasButtonFontWeight:r.fontWeightNormal,canvasButtonFontSize:r.fontSizeMedium,canvasButtonLineHeight:n.inputHeightMedium,canvasButtonPadding:"0 "+i.small,canvasPrimaryButtonBackground:t.backgroundBrand,canvasPrimaryButtonColor:t.textLightest,canvasPrimaryButtonBorderColor:"transparent",canvasPrimaryButtonHoverBackground:Object(_t["a"])(t.backgroundBrand,10),canvasPrimaryButtonHoverColor:t.textLightest,canvasSecondaryButtonBackground:t.backgroundLight,canvasSecondaryButtonColor:t.textDarkest,canvasSecondaryButtonBorderColor:Object(_t["a"])(t.backgroundLight,10),canvasSecondaryButtonHoverBackground:Object(_t["a"])(t.backgroundLight,10),canvasSecondaryButtonHoverColor:t.textDarkest,canvasFocusBorderColor:e.brand,canvasFocusBorderWidth:e.widthSmall,canvasFocusBoxShadow:"0 0 0 2px "+t.brand,canvasEnabledColor:e.brand,canvasEnabledBoxShadow:"inset 0 0 0.1875rem 0.0625rem "+Object(_t["a"])(t.borderLightest,25),canvasFontFamily:r.fontFamily,canvasFontSize:"1rem",canvasFontSizeSmall:r.fontSizeSmall,canvasModalShadow:o.depth3,canvasModalHeadingPadding:i.medium,canvasModalHeadingFontSize:r.fontSizeXLarge,canvasModalHeadingFontWeight:r.fontWeightNormal,canvasModalBodyPadding:i.medium,canvasModalFooterPadding:i.small,canvasModalFooterBackground:t.backgroundLight,canvasFormElementMargin:`0 0 ${i.medium} 0`,canvasFormElementLabelColor:t.textDarkest,canvasFormElementLabelMargin:`0 0 ${i.small} 0`,canvasFormElementLabelFontSize:r.fontSizeMedium,canvasFormElementLabelFontWeight:r.fontWeightBold,canvasBadgeBackgroundColor:t.textInfo}
a.tinySplitButtonChevronHoverBackground=Object(_t["a"])(a.toolbarButtonHoverBackground,10)
return a}ft.canvas=function(e){return{canvasLinkColor:e["ic-link-color"],canvasLinkDecoration:e["ic-link-decoration"],canvasTextColor:e["ic-brand-font-color-dark"],canvasBrandColor:e["ic-brand-primary"],canvasFocusBorderColor:e["ic-brand-primary"],canvasFocusBoxShadow:"0 0 0 2px "+e["ic-brand-primary"],canvasEnabledColor:e["ic-brand-primary"],canvasPrimaryButtonBackground:e["ic-brand-primary"],canvasPrimaryButtonColor:e["ic-brand-button--primary-text"],canvasPrimaryButtonHoverBackground:Object(_t["a"])(e["ic-brand-button--primary-bgd"],10),activeMenuItemBackground:e["ic-brand-button--primary-bgd"],activeMenuItemLabelColor:e["ic-brand-button--primary-text"],tableSelectorHighlightColor:Object(mt["a"])(Object(pt["a"])(e["ic-brand-primary"],10),50)}}
ft["canvas-a11y"]=ft["canvas-high-contrast"]=function({colors:e}){return{canvasButtonBackground:e.backgroundLight,canvasSecondaryButtonBorderColor:e.borderMedium,canvasLinkDecoration:"underline",canvasFocusBoxShadow:"0 0 0 2px "+e.brand,canvasBrandColor:e.brand}}
var ht=n("msMH")
var yt=n("lxh4")
var bt=n("Dibh")
var gt=n("Mmr1")
function vt(e){return s.a.createElement(bt["a"],{"data-testid":"RCE_KeyboardShortcutModal","data-mce-component":true,label:Object(V["a"])("Keyboard Shortcuts"),open:e.open,shouldCloseOnDocumentClick:true,shouldReturnFocus:true,size:"auto",onClose:e.onClose,onExited:e.onExited,onDismiss:e.onDismiss},s.a.createElement(bt["a"].Header,null,s.a.createElement(gt["a"],{placement:"end",offset:"medium",variant:"icon",onClick:e.onDismiss},Object(V["a"])("Close")),s.a.createElement(ht["a"],null,Object(V["a"])("Keyboard Shortcuts"))),s.a.createElement(bt["a"].Body,null,s.a.createElement(H["a"],{as:"div",margin:"small"},s.a.createElement(yt["a"],{variant:"unstyled"},s.a.createElement(yt["a"].Item,null,s.a.createElement(We["a"],{weight:"bold"},"ALT+F8/ALT+0")," ",Object(V["a"])("Open this keyboard shortcuts dialog")),s.a.createElement(yt["a"].Item,null,s.a.createElement(We["a"],{weight:"bold"},"CTRL+F9")," ",Object(V["a"])("Focus element options toolbar")),s.a.createElement(yt["a"].Item,null,s.a.createElement(We["a"],{weight:"bold"},"ALT+F9")," ",Object(V["a"])("Go to the editor's menubar")),s.a.createElement(yt["a"].Item,null,s.a.createElement(We["a"],{weight:"bold"},"ALT+F10")," ",Object(V["a"])("Go to the editor's toolbar")),s.a.createElement(yt["a"].Item,null,s.a.createElement(We["a"],{weight:"bold"},"ESC")," ",Object(V["a"])("Close a menu or dialog. Also returns you to the editor area")),s.a.createElement(yt["a"].Item,null,s.a.createElement(We["a"],{weight:"bold"},Object(V["a"])("TAB/Arrows"))," ",Object(V["a"])("Navigate through the menu or toolbar"))),s.a.createElement(H["a"],{as:"p"},Object(V["a"])("Other editor shortcuts may be found at")," ",s.a.createElement("a",{href:"https://www.tiny.cloud/docs/advanced/keyboard-shortcuts/",target:"rcekbshortcut"},"https://www.tiny.cloud/docs/advanced/keyboard-shortcuts/")))))}vt.propTypes={open:r["bool"].isRequired,onClose:r["func"],onDismiss:r["func"].isRequired,onExited:r["func"]}
function wt({messages:e,afterDismiss:t,liveRegion:n}){return s.a.createElement("div",null,e.map(e=>s.a.createElement(U["a"],{key:e.id,variant:e.variant||e.type||"info",timeout:1e4,liveRegion:n,onDismiss:()=>t(e.id)},e.text)))}wt.propTypes={messages:Object(r["arrayOf"])(Object(r["shape"])({id:r["number"],variant:r["string"],text:r["string"]})).isRequired,afterDismiss:r["func"],liveRegion:r["func"].isRequired}
var kt=n("eAGa")
var Ct=n("WRSb")
var Ot=n("G1G5")
const Et=["trayProps"]
var At,St,jt,It
const Tt=s.a.lazy(()=>n.e(4171).then(n.bind(null,"L5Z7")))
const Lt=s.a.lazy(()=>Promise.all([n.e(3697),n.e(4137)]).then(n.bind(null,"GuXJ")))
const Bt=250
const Dt="400px"
const Rt=a.a.arrayOf(a.a.shape({name:a.a.string.isRequired,items:a.a.arrayOf(a.a.string).isRequired}))
const Ft=a.a.objectOf(a.a.shape({title:a.a.string,items:a.a.string.isRequired}))
const Mt=a.a.arrayOf(a.a.shape({id:a.a.oneOfType([a.a.string,a.a.number]),favorite:a.a.bool}))
const zt=a.a.shape({height:a.a.oneOfType([a.a.number,a.a.string]),toolbar:Rt,menu:Ft,plugins:a.a.arrayOf(a.a.string),readonly:a.a.bool})
const Pt={componentId:"dyzZI",template:function(e){return`\n\n\n\n\n.canvas-rce__skins--root {\n  background-color: ${e.canvasBackgroundColor||"inherit"};\n}\n\n\n\n.rce-wrapper textarea {\n    width: 100%;\n    box-sizing: border-box;\n    min-height: auto;\n  }\n\n.tox,\n  .tox *:not(svg) {\n    color: inherit;\n    font-family: inherit;\n  }\n\n\n\n[dir='rtl'] .tox :not(svg) {\n    direction: rtl;\n  }\n\n.tox:not(.tox-tinymce-inline) .tox-editor-header {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n  }\n\n.tox.tox-tinymce .screenreader-only {\n    border: 0;\n    clip: rect(0 0 0 0);\n    height: 1px;\n    margin: -1px;\n    overflow: hidden;\n    padding: 0;\n    position: absolute;\n    width: 1px;\n    transform: translatez(0);\n  }\n\n.tox-tinymce-aux {\n    font-family: ${e.canvasFontFamily||"inherit"};\n  }\n\n\n\n.tox.tox-tinymce-aux {\n    z-index: 10000;\n  }\n\n.tox .tox-button {\n    background-color: ${e.canvasPrimaryButtonHoverBackground||"inherit"};\n    font-family: ${e.canvasFontFamily||"inherit"};\n    font-weight: ${e.canvasButtonFontWeight||"inherit"};\n    font-size: ${e.canvasButtonFontSize||"inherit"};\n    color: ${e.canvasPrimaryButtonColor||"inherit"};\n    border-color: ${e.canvasPrimaryButtonBorderColor||"inherit"};\n    line-height: calc(${e.canvasButtonLineHeight||"inherit"} - 2px);\n    padding: ${e.canvasButtonPadding||"inherit"};\n  }\n\n.tox .tox-button[disabled] {\n    opacity: 0.5;\n    border-color: inherit;\n    color: inherit;\n  }\n\n.tox .tox-button:focus:not(:disabled) {\n    background-color: ${e.canvasPrimaryButtonBackground||"inherit"};\n    color: ${e.canvasPrimaryButtonColor||"inherit"};\n    border-color: ${e.canvasBackgroundColor||"inherit"};\n    box-shadow: ${e.canvasFocusBoxShadow||"inherit"};\n  }\n\n.tox .tox-button:hover:not(:disabled) {\n    background-color: ${e.canvasPrimaryButtonHoverBackground||"inherit"};\n    color: ${e.canvasPrimaryButtonHoverColor||"inherit"};\n  }\n\n.tox .tox-button:active:not(:disabled) {\n    background-color: ${e.canvasPrimaryButtonBackground||"inherit"};\n    border-color: ${e.canvasPrimaryButtonBorderColor||"inherit"};\n    color: ${e.canvasPrimaryButtonColor||"inherit"};\n  }\n\n.tox .tox-button--secondary {\n    background-color: ${e.canvasSecondaryButtonBackground||"inherit"};\n    border-color: ${e.canvasSecondaryButtonBorderColor||"inherit"};\n    color: ${e.canvasSecondaryButtonColor||"inherit"};\n  }\n\n.tox .tox-button--secondary[disabled] {\n    background-color: inherit;\n    border-color: ${e.canvasSecondaryButtonBorderColor||"inherit"};\n    color: inherit;\n    opacity: 0.5;\n  }\n\n.tox .tox-button--secondary:focus:not(:disabled) {\n    background-color: inherit;\n    border-color: ${e.canvasFocusBorderColor||"inherit"};\n    color: inherit;\n  }\n\n.tox .tox-button--secondary:hover:not(:disabled) {\n    background-color: ${e.canvasSecondaryButtonHoverBackground||"inherit"};\n    border-color: ${e.canvasSecondaryButtonBorderColor||"inherit"};\n    color: ${e.canvasSecondaryButtonHoverColor||"inherit"};\n  }\n\n.tox .tox-button--secondary:active:not(:disabled) {\n    background-color: inherit;\n    border-color: ${e.canvasSecondaryButtonBorderColor||"inherit"};\n    color: inherit;\n  }\n\n.tox .tox-button-link {\n    font-family: ${e.canvasFontFamily||"inherit"};\n  }\n\n.tox .tox-button--naked {\n    background: ${e.canvasButtonBackground||"inherit"};\n    border-color: ${e.canvasButtonBorderColor||"inherit"};\n    color: ${e.canvasButtonColor||"inherit"};\n  }\n\n.tox .tox-button--naked:hover:not(:disabled) {\n    background-color: ${e.canvasButtonHoverBackground||"inherit"};\n    border-color: ${e.canvasButtonBorderColor||"inherit"};\n    color: ${e.canvasButtonHoverColor||"inherit"};\n  }\n\n.tox .tox-button--naked:focus:not(:disabled) {\n    background-color: ${e.canvasButtonBackground||"inherit"};\n    color: ${e.canvasButtonColor||"inherit"};\n    border-color: ${e.canvasBackgroundColor||"inherit"};\n    box-shadow: ${e.canvasFocusBoxShadow||"inherit"};\n  }\n\n.tox .tox-button--naked:active:not(:disabled) {\n    background-color: inherit;\n    color: inherit;\n  }\n\n.tox .tox-button--naked.tox-button--icon {\n    color: ${e.canvasButtonColor||"inherit"};\n  }\n\n.tox .tox-button--naked.tox-button--icon:hover:not(:disabled) {\n    background: ${e.canvasButtonHoverBackground||"inherit"};\n    color: ${e.canvasButtonHoverColor||"inherit"};\n  }\n\n.tox .tox-checkbox__icons .tox-checkbox-icon__unchecked svg {\n    fill: rgba(45, 59, 69, 0.3);\n  }\n\n.tox .tox-checkbox__icons .tox-checkbox-icon__indeterminate svg {\n    fill: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-checkbox__icons .tox-checkbox-icon__checked svg {\n    fill: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox input.tox-checkbox__input:focus + .tox-checkbox__icons {\n    box-shadow: ${e.canvasFocusBoxShadow||"inherit"};\n  }\n\n.tox .tox-collection--list .tox-collection__group {\n    border-color: ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox .tox-collection__group-heading {\n    background-color: #e3e6e8;\n    color: rgba(45, 59, 69, 0.6);\n  }\n\n.tox .tox-collection__item {\n    color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-collection__item--state-disabled {\n    background-color: unset;\n    opacity: 0.5;\n    cursor: default;\n  }\n\n.tox .tox-collection--list .tox-collection__item--enabled {\n    color: contrast(inherit, ${e.canvasTextColor||"inherit"}, #fff);\n  }\n\n.tox .tox-collection--list .tox-collection__item--active {\n    background-color: ${e.activeMenuItemBackground||"inherit"};\n    color: ${e.activeMenuItemLabelColor||"inherit"};\n  }\n\n.tox\n    .tox-collection--list\n    .tox-collection__item--active:not(.tox-collection__item--state-disabled) {\n    background-color: ${e.activeMenuItemBackground||"inherit"};\n    color: ${e.activeMenuItemLabelColor||"inherit"};\n  }\n\n.tox .tox-collection--toolbar .tox-collection__item--enabled {\n    background-color: #cbced1;\n    color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-collection--toolbar .tox-collection__item--active {\n    background-color: #e0e2e3;\n    color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-collection--grid .tox-collection__item--enabled {\n    background-color: #cbced1;\n    color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-collection--grid .tox-collection__item--active {\n    background-color: #e0e2e3;\n    color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-collection--list .tox-collection__item-icon:first-child {\n    margin-right: 8px;\n  }\n\n.tox .tox-collection__item-accessory {\n    color: rgba(45, 59, 69, 0.6);\n  }\n\n.tox .tox-sv-palette {\n    border: 1px solid black;\n    box-sizing: border-box;\n  }\n\n.tox .tox-hue-slider {\n    border: 1px solid black;\n  }\n\n.tox .tox-rgb-form input.tox-invalid {\n    \n    border-color: ${e.canvasErrorColor||"inherit"} !important;\n  }\n\n.tox .tox-rgb-form {\n    padding: 2px; \n  }\n\n.tox .tox-swatches__picker-btn:hover {\n    background: #e0e2e3;\n  }\n\n.tox .tox-comment-thread {\n    background: ${e.canvasBackgroundColor||"inherit"};\n  }\n\n.tox .tox-comment {\n    background: ${e.canvasBackgroundColor||"inherit"};\n    border-color: ${e.canvasBorderColor||"inherit"};\n    box-shadow: 0 4px 8px 0 rgba(45, 59, 69, 0.1);\n  }\n\n.tox .tox-comment__header {\n    color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-comment__date {\n    color: rgba(45, 59, 69, 0.6);\n  }\n\n.tox .tox-comment__body {\n    color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-comment__expander p {\n    color: rgba(45, 59, 69, 0.6);\n  }\n\n.tox .tox-comment-thread__overlay::after {\n    background: ${e.canvasBackgroundColor||"inherit"};\n  }\n\n.tox .tox-comment__overlay {\n    background: ${e.canvasBackgroundColor||"inherit"};\n  }\n\n.tox .tox-comment__loading-text {\n    color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-comment__overlaytext p {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n    color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-comment__busy-spinner {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n  }\n\n.tox .tox-user__avatar svg {\n    fill: rgba(45, 59, 69, 0.6);\n  }\n\n.tox .tox-user__name {\n    color: rgba(45, 59, 69, 0.6);\n  }\n\n.tox .tox-dialog-wrap__backdrop {\n    background-color: rgba(255, 255, 255, 0.75);\n  }\n\n.tox .tox-dialog {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n    border-color: ${e.canvasBorderColor||"inherit"};\n    box-shadow: ${e.canvasModalShadow||"inherit"};\n  }\n\n.tox .tox-dialog__header {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n    color: ${e.canvasTextColor||"inherit"};\n    border-bottom: 1px solid ${e.canvasBorderColor||"inherit"};\n    padding: ${e.canvasModalHeadingPadding||"inherit"};\n    margin: 0;\n  }\n\n.tox .tox-dialog__title {\n    font-family: ${e.canvasFontFamily||"inherit"};\n    font-size: ${e.canvasModalHeadingFontSize||"inherit"};\n    font-weight: ${e.canvasModalHeadingFontWeight||"inherit"};\n  }\n\n.tox .tox-dialog__body {\n    color: ${e.canvasTextColor||"inherit"};\n    padding: ${e.canvasModalBodyPadding||"inherit"};\n  }\n\n.tox .tox-dialog__body-nav-item {\n    color: rgba(45, 59, 69, 0.75);\n  }\n\n.tox .tox-dialog__body-nav-item:focus {\n      box-shadow: ${e.canvasFocusBoxShadow||"inherit"};\n    }\n\n.tox .tox-dialog__body-nav-item--active {\n    border-bottom-color: ${e.canvasBrandColor||"inherit"};\n    color: ${e.canvasBrandColor||"inherit"};\n  }\n\n.tox .tox-dialog__footer {\n    background-color: ${e.canvasModalFooterBackground||"inherit"};\n    border-top: 1px solid ${e.canvasBorderColor||"inherit"};\n    padding: ${e.canvasModalFooterPadding||"inherit"};\n    margin: 0;\n  }\n\n.tox .tox-dialog__table tbody tr {\n    border-bottom-color: ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox .tox-dropzone {\n    background: ${e.canvasBackgroundColor||"inherit"};\n    border: 2px dashed ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox .tox-dropzone p {\n    color: rgba(45, 59, 69, 0.6);\n  }\n\n.tox .tox-edit-area {\n    border: 1px solid ${e.canvasBorderColor||"inherit"};\n    border-radius: 3px;\n  }\n\n.tox .tox-edit-area__iframe {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n    border: ${e.canvasFocusBorderWidth||"inherit"} solid transparent;\n  }\n\n.tox.tox-inline-edit-area {\n    border-color: ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox .tox-form__group {\n    padding: 2px;\n  }\n\n.tox .tox-control-wrap .tox-textfield {\n    padding-right: 32px;\n  }\n\n.tox .tox-control-wrap__status-icon-invalid svg {\n    fill: ${e.canvasErrorColor||"inherit"};\n  }\n\n.tox .tox-control-wrap__status-icon-unknown svg {\n    fill: ${e.canvasWarningColor||"inherit"};\n  }\n\n.tox .tox-control-wrap__status-icon-valid svg {\n    fill: ${e.canvasSuccessColor||"inherit"};\n  }\n\n.tox .tox-color-input span {\n    border-color: rgba(45, 59, 69, 0.2);\n  }\n\n.tox .tox-color-input span:focus {\n    border-color: ${e.canvasBrandColor||"inherit"};\n  }\n\n.tox .tox-label,\n  .tox .tox-toolbar-label {\n    color: rgba(45, 59, 69, 0.6);\n  }\n\n.tox .tox-form__group {\n    margin: ${e.canvasFormElementMargin||"inherit"};\n  }\n\n.tox .tox-form__group:last-child {\n    margin: 0;\n  }\n\n.tox .tox-form__group .tox-label {\n    color: ${e.canvasFormElementLabelColor||"inherit"};\n    margin: ${e.canvasFormElementLabelMargin||"inherit"};\n    font-size: ${e.canvasFormElementLabelFontSize||"inherit"};\n    font-weight: ${e.canvasFormElementLabelFontWeight||"inherit"};\n  }\n\n.tox .tox-form__group--error {\n    color: ${e.canvasErrorColor||"inherit"};\n  }\n\n.tox .tox-textfield,\n  .tox .tox-selectfield select,\n  .tox .tox-textarea,\n  .tox .tox-toolbar-textfield {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n    border-color: ${e.canvasBorderColor||"inherit"};\n    color: ${e.canvasTextColor||"inherit"};\n    font-family: ${e.canvasFontFamily||"inherit"};\n  }\n\n.tox .tox-textfield:focus,\n  .tox .tox-selectfield select:focus,\n  .tox .tox-textarea:focus {\n    \n    border-color: ${e.canvasBorderColor||"inherit"};\n    box-shadow: ${e.canvasFocusBoxShadow||"inherit"};\n  }\n\n.tox .tox-naked-btn {\n    color: ${e.canvasButtonColor||"inherit"};\n  }\n\n.tox .tox-naked-btn svg {\n    fill: ${e.canvasButtonColor||"inherit"};\n  }\n\n.tox .tox-insert-table-picker > div {\n    border-color: #cccccc;\n  }\n\n.tox .tox-insert-table-picker .tox-insert-table-picker__selected {\n    background-color: ${e.tableSelectorHighlightColor||"inherit"};\n    border-color: ${e.tableSelectorHighlightColor||"inherit"};\n  }\n\n.tox-selected-menu .tox-insert-table-picker {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n  }\n\n.tox .tox-insert-table-picker__label {\n    color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-menu {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n    border-color: ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox .tox-menubar {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n  }\n\n.tox .tox-mbtn {\n    color: ${e.canvasButtonColor||"inherit"};\n  }\n\n.tox .tox-mbtn[disabled] {\n    opacity: 0.5;\n  }\n\n.tox .tox-mbtn:hover:not(:disabled) {\n    background: ${e.toolbarButtonHoverBackground||"inherit"};\n    color: ${e.canvasButtonColor||"inherit"};\n  }\n\n.tox .tox-mbtn:focus:not(:disabled) {\n    background-color: transparent;\n    color: ${e.canvasButtonColor||"inherit"};\n    border-color: ${e.canvasBackgroundColor||"inherit"};\n    box-shadow: ${e.canvasFocusBoxShadow||"inherit"};\n  }\n\n.tox .tox-mbtn--active {\n    background: ${e.toolbarButtonHoverBackground||"inherit"};\n    color: ${e.canvasButtonColor||"inherit"};\n  }\n\n.tox .tox-notification {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n    border-color: #c5c5c5;\n  }\n\n.tox .tox-notification--success {\n    background-color: #dff0d8;\n    border-color: ${e.canvasSuccessColor||"inherit"};\n  }\n\n.tox .tox-notification--error {\n    background-color: #f2dede;\n    border-color: ${e.canvasErrorColor||"inherit"};\n  }\n\n.tox .tox-notification--warn {\n    background-color: #fcf8e3;\n    border-color: ${e.canvasWarningColor||"inherit"};\n  }\n\n.tox .tox-notification--info {\n    background-color: #d9edf7;\n    border-color: ${e.canvasInfoColor||"inherit"};\n  }\n\n.tox .tox-notification__body {\n    color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-pop__dialog {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n    border-color: ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox .tox-pop.tox-pop--bottom::before {\n    border-color: ${e.canvasBorderColor||"inherit"} transparent transparent transparent;\n  }\n\n.tox .tox-pop.tox-pop--top::before {\n    border-color: transparent transparent ${e.canvasBorderColor||"inherit"} transparent;\n  }\n\n.tox .tox-pop.tox-pop--left::before {\n    border-color: transparent ${e.canvasBorderColor||"inherit"} transparent transparent;\n  }\n\n.tox .tox-pop.tox-pop--right::before {\n    border-color: transparent transparent transparent ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox .tox-slider {\n    width: 100%;\n  }\n\n.tox .tox-slider__rail {\n    border-color: ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox .tox-slider__handle {\n    background-color: ${e.canvasBrandColor||"inherit"};\n  }\n\n.tox .tox-spinner > div {\n    background-color: rgba(45, 59, 69, 0.6);\n  }\n\n\n\n.tox .tox-tbtn {\n    border-style: none;\n    color: ${e.canvasButtonColor||"inherit"};\n    position: relative;\n  }\n\n.tox .tox-tbtn svg {\n    fill: ${e.canvasButtonColor||"inherit"};\n  }\n\n.tox .tox-tbtn.tox-tbtn--enabled {\n    background: inherit;\n  }\n\n.tox .tox-tbtn:focus,\n  .tox .tox-split-button:focus {\n    background: ${e.canvasBackgroundColor||"inherit"};\n    color: ${e.canvasButtonColor||"inherit"};\n    box-shadow: ${e.canvasFocusBoxShadow||"inherit"};\n  }\n\n.tox .tox-tbtn:hover,\n  .tox .tox-split-button:hover,\n  .tox .tox-tbtn.tox-tbtn--enabled:hover,\n  .tox .tox-split-button .tox-tbtn.tox-split-button__chevron:hover {\n    background: ${e.toolbarButtonHoverBackground||"inherit"};\n    color: ${e.canvasButtonColor||"inherit"};\n  }\n\n.tox-tbtn.tox-split-button__chevron {\n    position: relative;\n  }\n\n\n\n.tox .tox-tbtn.tox-tbtn--enabled::after {\n    position: absolute;\n    top: -3px;\n    content: '\\25BC';\n    text-align: center;\n    height: 8px;\n    font-size: 8px;\n    width: 100%;\n    color: ${e.canvasEnabledColor||"inherit"};\n  }\n\n[dir="ltr"] .tox .tox-tbtn.tox-tbtn--enabled::after {\n    text-align: center;\n  }\n\n[dir="rtl"] .tox .tox-tbtn.tox-tbtn--enabled::after {\n    text-align: center;\n  }\n\n\n\n.tox-tbtn.tox-split-button__chevron.tox-tbtn--enabled::after {\n    display: none;\n  }\n\n.tox .tox-tbtn--disabled,\n  .tox .tox-tbtn--disabled:hover,\n  .tox .tox-tbtn:disabled,\n  .tox .tox-tbtn:disabled:hover {\n    opacity: 0.5;\n  }\n\n.tox .tox-tbtn--disabled svg,\n  .tox .tox-tbtn--disabled:hover svg,\n  .tox .tox-tbtn:disabled svg,\n  .tox .tox-tbtn:disabled:hover svg {\n    \n    opacity: 0.5;\n  }\n\n.tox .tox-tbtn__select-chevron svg {\n    fill: ${e.canvasButtonColor||"inherit"};\n    width: 10px;\n    height: 10px;\n  }\n\n.tox .tox-split-button__chevron svg {\n    fill: ${e.canvasButtonColor||"inherit"};\n    width: 10px;\n    height: 10px;\n  }\n\n.tox .tox-split-button.tox-tbtn--disabled:hover,\n  .tox .tox-split-button.tox-tbtn--disabled:focus,\n  .tox .tox-split-button.tox-tbtn--disabled .tox-tbtn:hover,\n  .tox .tox-split-button.tox-tbtn--disabled .tox-tbtn:focus {\n    opacity: 0.5;\n  }\n\n.tox .tox-toolbar {\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n    border-top: 1px solid ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox .tox-toolbar__group:not(:last-of-type) {\n    border-right: 1px solid ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox .tox-tooltip__body {\n    background-color: ${e.canvasTextColor||"inherit"};\n    box-shadow: 0 2px 4px rgba(45, 59, 69, 0.3);\n    color: rgba(255, 255, 255, 0.75);\n  }\n\n.tox .tox-tooltip--down .tox-tooltip__arrow {\n    border-top-color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-tooltip--up .tox-tooltip__arrow {\n    border-bottom-color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-tooltip--right .tox-tooltip__arrow {\n    border-left-color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-tooltip--left .tox-tooltip__arrow {\n    border-right-color: ${e.canvasTextColor||"inherit"};\n  }\n\n.tox .tox-well {\n    border-color: ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox .tox-custom-editor {\n    border-color: ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox a {\n    color: ${e.canvasLinkColor||"inherit"};\n  }\n\n.tox.tox-tinymce {\n    border-style: none;\n  }\n\n\n\n.tox-editor-container .tox-toolbar,\n  .tox-editor-container .tox-toolbar-overlord {\n    background-image: none;\n    margin-bottom: 5px;\n  }\n\n.tox-editor-container .tox-toolbar__primary {\n    background-image: none;\n  }\n\n\n\n.tox .tox-menubar + .tox-toolbar-overlord .tox-toolbar__primary {\n    border-style: none;\n  }\n\n.tox .tox-toolbar .tox-toolbar__group,\n  .tox .tox-toolbar-overlord .tox-toolbar__group,\n  .tox-toolbar__overflow .tox-toolbar__group,\n  .tox:not([dir='rtl']) .tox-toolbar__group:not(:last-of-type),\n  .tox[dir='rtl'] .tox-toolbar__group:not(:last-of-type) {\n    border-style: none;\n  }\n\n.tox-toolbar .tox-toolbar__group::after, \n  .tox-toolbar-overlord .tox-toolbar__group::after, \n  .tox-toolbar__overflow .tox-toolbar__group::after, \n  .tox-tinymce-aux .tox-toolbar .tox-toolbar__group::after {\n    \n    content: '';\n    display: inline-block;\n    box-sizing: border-box;\n    border-inline-end: 1px solid ${e.canvasBorderColor||"inherit"};\n    width: 8px;\n    height: 24px;\n  }\n\n[dir="ltr"] .tox-toolbar .tox-toolbar__group::after,\n[dir="ltr"] .tox-toolbar-overlord .tox-toolbar__group::after,\n[dir="ltr"] .tox-toolbar__overflow .tox-toolbar__group::after,\n[dir="ltr"] .tox-tinymce-aux .tox-toolbar .tox-toolbar__group::after {\n    border-right: 1px solid ${e.canvasBorderColor||"inherit"};\n  }\n\n[dir="rtl"] .tox-toolbar .tox-toolbar__group::after,\n[dir="rtl"] .tox-toolbar-overlord .tox-toolbar__group::after,\n[dir="rtl"] .tox-toolbar__overflow .tox-toolbar__group::after,\n[dir="rtl"] .tox-tinymce-aux .tox-toolbar .tox-toolbar__group::after {\n    border-left: 1px solid ${e.canvasBorderColor||"inherit"};\n  }\n\n.tox-toolbar .tox-toolbar__group:last-child::after,\n  .tox-toolbar-overlord .tox-toolbar__group:last-child::after,\n  .tox-toolbar__overflow .tox-toolbar__group:last-child::after,\n  .tox-tinymce-aux .tox-toolbar .tox-toolbar__group:last-child::after {\n    border-inline-end-width: 0;\n    padding-inline-start: 0;\n    width: 0;\n  }\n\n[dir="ltr"] .tox-toolbar .tox-toolbar__group:last-child::after,\n[dir="ltr"] .tox-toolbar-overlord .tox-toolbar__group:last-child::after,\n[dir="ltr"] .tox-toolbar__overflow .tox-toolbar__group:last-child::after,\n[dir="ltr"] .tox-tinymce-aux .tox-toolbar .tox-toolbar__group:last-child::after {\n    border-right-width: 0;\n    padding-left: 0;\n  }\n\n[dir="rtl"] .tox-toolbar .tox-toolbar__group:last-child::after,\n[dir="rtl"] .tox-toolbar-overlord .tox-toolbar__group:last-child::after,\n[dir="rtl"] .tox-toolbar__overflow .tox-toolbar__group:last-child::after,\n[dir="rtl"] .tox-tinymce-aux .tox-toolbar .tox-toolbar__group:last-child::after {\n    border-left-width: 0;\n    padding-right: 0;\n  }\n\n.tox .tox-tbtn--bespoke .tox-tbtn__select-label {\n    width: auto;\n    padding-inline-end: 0;\n  }\n\n[dir="ltr"] .tox .tox-tbtn--bespoke .tox-tbtn__select-label {\n    padding-right: 0;\n  }\n\n[dir="rtl"] .tox .tox-tbtn--bespoke .tox-tbtn__select-label {\n    padding-left: 0;\n  }\n\n.tox .tox-tbtn {\n    box-sizing: border-box;\n  }\n\n.tox .tox-tbtn,\n  .tox .tox-split-button,\n  .tox .tox-tbtn--select {\n    border-style: none;\n    margin: 2px 2px 3px;\n  }\n\n.tox .tox-split-button .tox-tbtn {\n    margin-inline-end: 0;\n  }\n\n[dir="ltr"] .tox .tox-split-button .tox-tbtn {\n    margin-right: 0;\n  }\n\n[dir="rtl"] .tox .tox-split-button .tox-tbtn {\n    margin-left: 0;\n  }\n\n.tox .tox-split-button .tox-tbtn.tox-split-button__chevron {\n    margin-inline-start: 0;\n  }\n\n[dir="ltr"] .tox .tox-split-button .tox-tbtn.tox-split-button__chevron {\n    margin-left: 0;\n  }\n\n[dir="rtl"] .tox .tox-split-button .tox-tbtn.tox-split-button__chevron {\n    margin-right: 0;\n  }\n\n.tox .tox-edit-area.active,\n  .tox .tox-edit-area.active iframe {\n    border-color: ${e.canvasFocusBorderColor||"inherit"};\n  }\n\n.tox .tox-split-button .tox-tbtn {\n    margin-inline-end: 0;\n  }\n\n[dir="ltr"] .tox .tox-split-button .tox-tbtn {\n    margin-right: 0;\n  }\n\n[dir="rtl"] .tox .tox-split-button .tox-tbtn {\n    margin-left: 0;\n  }\n\n.tox .tox-split-button .tox-tbtn.tox-split-button__chevron {\n    margin-inline-start: -6px;\n    background-color: ${e.canvasBackgroundColor||"inherit"};\n  }\n\n[dir="ltr"] .tox .tox-split-button .tox-tbtn.tox-split-button__chevron {\n    margin-left: -6px;\n  }\n\n[dir="rtl"] .tox .tox-split-button .tox-tbtn.tox-split-button__chevron {\n    margin-right: -6px;\n  }\n\n.tox .tox-split-button:hover .tox-split-button__chevron {\n    background: ${e.canvasBackgroundColor||"inherit"};\n    color: ${e.canvasButtonColor||"inherit"};\n    box-shadow: none;\n  }\n\n.tox .tox-tbtn:hover.tox-split-button__chevron,\n  .tox .tox-tbtn:focus.tox-split-button__chevron {\n    box-shadow: none;\n  }\n\n.tox .tox-toolbar__primary {\n    border-width: 0;\n  }\n\n.tox-tbtn.tox-tbtn--select .tox-icon.tox-tbtn__icon-wrap {\n    margin-inline-end: 4px;\n  }\n\n[dir="ltr"] .tox-tbtn.tox-tbtn--select .tox-icon.tox-tbtn__icon-wrap {\n    margin-right: 4px;\n  }\n\n[dir="rtl"] .tox-tbtn.tox-tbtn--select .tox-icon.tox-tbtn__icon-wrap {\n    margin-left: 4px;\n  }\n\n\n\n.tox .tox-icon svg:not([height]),\n  .tox .tox-collection__item-icon svg:not([height]) {\n    height: 16px;\n  }\n\n\n\n.tox .tox-collection--toolbar-lg .tox-collection__item-icon {\n    height: 30px;\n    width: 30px;\n  }\n\n\n\n.tox-selectfield__icon-js svg {\n    width: 10px;\n    height: 10px;\n  }\n\n\n\n[data-canvascontenttray-content]:focus {\n    outline-color: ${e.canvasFocusBorderColor||"inherit"};\n  }\n`},root:"canvas-rce__skins--root"}
const Nt={componentId:"djgIv",template:function(){return'\n\n\n.tinymce__oxide--tox{box-shadow:none;box-sizing:content-box;color:#222f3e;cursor:auto;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",sans-serif;font-size:16px;font-style:normal;font-weight:400;line-height:normal;-webkit-tap-highlight-color:transparent;text-decoration:none;text-shadow:none;text-transform:none;vertical-align:baseline;vertical-align:initial;white-space:normal}\n\n.tinymce__oxide--tox :not(svg):not(rect){box-sizing:inherit;color:inherit;cursor:inherit;direction:inherit;font-family:inherit;font-size:inherit;font-style:inherit;font-weight:inherit;line-height:inherit;-webkit-tap-highlight-color:inherit;text-align:inherit;text-decoration:inherit;text-shadow:inherit;text-transform:inherit;vertical-align:inherit;white-space:inherit}\n\n[dir="ltr"] .tinymce__oxide--tox :not(svg):not(rect){text-align:inherit}\n\n[dir="rtl"] .tinymce__oxide--tox :not(svg):not(rect){text-align:inherit}\n\n.tinymce__oxide--tox :not(svg):not(rect){background:0 0;border:0;box-shadow:none;float:none;height:auto;margin:0;max-width:none;outline:0;padding:0;position:static;width:auto}\n\n[dir="ltr"] .tinymce__oxide--tox :not(svg):not(rect){float:none}\n\n[dir="rtl"] .tinymce__oxide--tox :not(svg):not(rect){float:none}\n\n.tinymce__oxide--tox:not([dir=rtl]){direction:ltr;text-align:left}\n\n[dir="ltr"] .tinymce__oxide--tox:not([dir=rtl]){text-align:left}\n\n[dir="rtl"] .tinymce__oxide--tox:not([dir=rtl]){text-align:left}\n\n.tinymce__oxide--tox[dir=rtl]{direction:rtl;text-align:right}\n\n[dir="ltr"] .tinymce__oxide--tox[dir=rtl]{text-align:right}\n\n[dir="rtl"] .tinymce__oxide--tox[dir=rtl]{text-align:right}\n\n.tinymce__oxide--tox-tinymce{border:1px solid #ccc;border-radius:0;box-shadow:none;box-sizing:border-box;display:flex;flex-direction:column;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",sans-serif;overflow:hidden;position:relative;visibility:inherit!important}\n\n.tinymce__oxide--tox-tinymce-inline{border:none;box-shadow:none}\n\n.tinymce__oxide--tox-tinymce-inline .tinymce__oxide--tox-editor-header{background-color:transparent;border:1px solid #ccc;border-radius:0;box-shadow:none}\n\n.tinymce__oxide--tox-tinymce-aux{font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",sans-serif;z-index:1300}\n\n.tinymce__oxide--tox-tinymce :focus,.tinymce__oxide--tox-tinymce-aux :focus{outline:0}\n\nbutton::-moz-focus-inner{border:0}\n\n.tinymce__oxide--tox .tinymce__oxide--accessibility-issue__header{align-items:center;display:flex;margin-bottom:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--accessibility-issue__description{align-items:stretch;border:1px solid #ccc;border-radius:3px;display:flex;justify-content:space-between}\n\n.tinymce__oxide--tox .tinymce__oxide--accessibility-issue__description>div{padding-bottom:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--accessibility-issue__description>div>div{align-items:center;display:flex;margin-bottom:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--accessibility-issue__description>:last-child:not(:only-child){border-color:#ccc;border-style:solid}\n\n.tinymce__oxide--tox .tinymce__oxide--accessibility-issue__repair{margin-top:16px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--info .tinymce__oxide--accessibility-issue__description{background-color:rgba(32,122,183,.1);border-color:rgba(32,122,183,.4);color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--info .tinymce__oxide--accessibility-issue__description>:last-child{border-color:rgba(32,122,183,.4)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--info .tinymce__oxide--tox-form__group h2{color:#207ab7}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--info .tinymce__oxide--tox-icon svg{fill:#207ab7}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--info a .tinymce__oxide--tox-icon{color:#207ab7}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--warn .tinymce__oxide--accessibility-issue__description{background-color:rgba(255,165,0,.1);border-color:rgba(255,165,0,.5);color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--warn .tinymce__oxide--accessibility-issue__description>:last-child{border-color:rgba(255,165,0,.5)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--warn .tinymce__oxide--tox-form__group h2{color:#cc8500}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--warn .tinymce__oxide--tox-icon svg{fill:#cc8500}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--warn a .tinymce__oxide--tox-icon{color:#cc8500}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--error .tinymce__oxide--accessibility-issue__description{background-color:rgba(204,0,0,.1);border-color:rgba(204,0,0,.4);color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--error .tinymce__oxide--accessibility-issue__description>:last-child{border-color:rgba(204,0,0,.4)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--error .tinymce__oxide--tox-form__group h2{color:#c00}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--error .tinymce__oxide--tox-icon svg{fill:#c00}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--error a .tinymce__oxide--tox-icon{color:#c00}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--success .tinymce__oxide--accessibility-issue__description{background-color:rgba(120,171,70,.1);border-color:rgba(120,171,70,.4);color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--success .tinymce__oxide--accessibility-issue__description>:last-child{border-color:rgba(120,171,70,.4)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--success .tinymce__oxide--tox-form__group h2{color:#78ab46}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--success .tinymce__oxide--tox-icon svg{fill:#78ab46}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue--success a .tinymce__oxide--tox-icon{color:#78ab46}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue__header h1,.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group .tinymce__oxide--accessibility-issue__description h2{margin-top:0}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue__header .tinymce__oxide--tox-button{margin-left:4px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue__header>:nth-last-child(2){margin-left:auto}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue__description{padding:4px 4px 4px 8px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue__description>:last-child{border-left-width:1px;padding-left:4px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue__header .tinymce__oxide--tox-button{margin-right:4px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue__header>:nth-last-child(2){margin-right:auto}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue__description{padding:4px 8px 4px 4px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--accessibility-issue__description>:last-child{border-right-width:1px;padding-right:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-anchorbar{display:flex;flex:0 0 auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-bar{display:flex;flex:0 0 auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button{background-color:#207ab7;background-image:none;background-position:0 0;background-repeat:repeat;border-color:#207ab7;border-radius:3px;border-style:solid;border-width:1px;box-shadow:none;box-sizing:border-box;color:#fff;cursor:pointer;display:inline-block;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",sans-serif;font-size:14px;font-style:normal;font-weight:700;letter-spacing:normal;line-height:24px;margin:0;outline:0;padding:4px 16px;text-align:center;text-decoration:none;text-transform:none;white-space:nowrap}\n\n[dir="ltr"] .tinymce__oxide--tox .tinymce__oxide--tox-button{text-align:center}\n\n[dir="rtl"] .tinymce__oxide--tox .tinymce__oxide--tox-button{text-align:center}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button[disabled]{background-color:#207ab7;background-image:none;border-color:#207ab7;box-shadow:none;color:rgba(255,255,255,.5);cursor:not-allowed}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button:focus:not(:disabled){background-color:#1c6ca1;background-image:none;border-color:#1c6ca1;box-shadow:none;color:#fff}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button:hover:not(:disabled){background-color:#1c6ca1;background-image:none;border-color:#1c6ca1;box-shadow:none;color:#fff}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button:active:not(:disabled){background-color:#185d8c;background-image:none;border-color:#185d8c;box-shadow:none;color:#fff}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--secondary{background-color:#f0f0f0;background-image:none;background-position:0 0;background-repeat:repeat;border-color:#f0f0f0;border-radius:3px;border-style:solid;border-width:1px;box-shadow:none;color:#222f3e;font-size:14px;font-style:normal;font-weight:700;letter-spacing:normal;outline:0;padding:4px 16px;text-decoration:none;text-transform:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--secondary[disabled]{background-color:#f0f0f0;background-image:none;border-color:#f0f0f0;box-shadow:none;color:rgba(34,47,62,.5)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--secondary:focus:not(:disabled){background-color:#e3e3e3;background-image:none;border-color:#e3e3e3;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--secondary:hover:not(:disabled){background-color:#e3e3e3;background-image:none;border-color:#e3e3e3;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--secondary:active:not(:disabled){background-color:#d6d6d6;background-image:none;border-color:#d6d6d6;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--icon,.tinymce__oxide--tox .tinymce__oxide--tox-button.tinymce__oxide--tox-button--icon,.tinymce__oxide--tox .tinymce__oxide--tox-button.tinymce__oxide--tox-button--secondary.tinymce__oxide--tox-button--icon{padding:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--icon .tinymce__oxide--tox-icon svg,.tinymce__oxide--tox .tinymce__oxide--tox-button.tinymce__oxide--tox-button--icon .tinymce__oxide--tox-icon svg,.tinymce__oxide--tox .tinymce__oxide--tox-button.tinymce__oxide--tox-button--secondary.tinymce__oxide--tox-button--icon .tinymce__oxide--tox-icon svg{display:block;fill:currentColor}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button-link{background:0;border:none;box-sizing:border-box;cursor:pointer;display:inline-block;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",sans-serif;font-size:16px;font-weight:400;line-height:1.3;margin:0;padding:0;white-space:nowrap}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button-link--sm{font-size:14px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--naked{background-color:transparent;border-color:transparent;box-shadow:unset;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--naked[disabled]{background-color:#f0f0f0;border-color:#f0f0f0;box-shadow:none;color:rgba(34,47,62,.5)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--naked:hover:not(:disabled){background-color:#e3e3e3;border-color:#e3e3e3;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--naked:focus:not(:disabled){background-color:#e3e3e3;border-color:#e3e3e3;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--naked:active:not(:disabled){background-color:#d6d6d6;border-color:#d6d6d6;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--naked .tinymce__oxide--tox-icon svg{fill:currentColor}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-button--naked.tinymce__oxide--tox-button--icon:hover:not(:disabled){color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-checkbox{align-items:center;border-radius:3px;cursor:pointer;display:flex;height:36px;min-width:36px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-checkbox__input{height:1px;overflow:hidden;position:absolute;top:auto;width:1px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-checkbox__icons{align-items:center;border-radius:3px;box-shadow:0 0 0 2px transparent;box-sizing:content-box;display:flex;height:24px;justify-content:center;padding:calc(4px - 1px);width:24px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-checkbox__icons .tinymce__oxide--tox-checkbox-icon__unchecked svg{display:block;fill:rgba(34,47,62,.3)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-checkbox__icons .tinymce__oxide--tox-checkbox-icon__indeterminate svg{display:none;fill:#207ab7}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-checkbox__icons .tinymce__oxide--tox-checkbox-icon__checked svg{display:none;fill:#207ab7}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-checkbox--disabled{color:rgba(34,47,62,.5);cursor:not-allowed}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-checkbox--disabled .tinymce__oxide--tox-checkbox__icons .tinymce__oxide--tox-checkbox-icon__checked svg{fill:rgba(34,47,62,.5)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-checkbox--disabled .tinymce__oxide--tox-checkbox__icons .tinymce__oxide--tox-checkbox-icon__unchecked svg{fill:rgba(34,47,62,.5)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-checkbox--disabled .tinymce__oxide--tox-checkbox__icons .tinymce__oxide--tox-checkbox-icon__indeterminate svg{fill:rgba(34,47,62,.5)}\n\n.tinymce__oxide--tox input.tinymce__oxide--tox-checkbox__input:checked+.tinymce__oxide--tox-checkbox__icons .tinymce__oxide--tox-checkbox-icon__unchecked svg{display:none}\n\n.tinymce__oxide--tox input.tinymce__oxide--tox-checkbox__input:checked+.tinymce__oxide--tox-checkbox__icons .tinymce__oxide--tox-checkbox-icon__checked svg{display:block}\n\n.tinymce__oxide--tox input.tinymce__oxide--tox-checkbox__input:indeterminate+.tinymce__oxide--tox-checkbox__icons .tinymce__oxide--tox-checkbox-icon__unchecked svg{display:none}\n\n.tinymce__oxide--tox input.tinymce__oxide--tox-checkbox__input:indeterminate+.tinymce__oxide--tox-checkbox__icons .tinymce__oxide--tox-checkbox-icon__indeterminate svg{display:block}\n\n.tinymce__oxide--tox input.tinymce__oxide--tox-checkbox__input:focus+.tinymce__oxide--tox-checkbox__icons{border-radius:3px;box-shadow:inset 0 0 0 1px #207ab7;padding:calc(4px - 1px)}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-checkbox__label{margin-left:4px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-checkbox__input{left:-10000px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-bar .tinymce__oxide--tox-checkbox{margin-left:4px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-checkbox__label{margin-right:4px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-checkbox__input{right:-10000px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-bar .tinymce__oxide--tox-checkbox{margin-right:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--toolbar .tinymce__oxide--tox-collection__group{display:flex;padding:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--grid .tinymce__oxide--tox-collection__group{display:flex;flex-wrap:wrap;max-height:208px;overflow-x:hidden;overflow-y:auto;padding:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__group{border-bottom-width:0;border-color:#ccc;border-left-width:0;border-right-width:0;border-style:solid;border-top-width:1px;padding:4px 0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__group:first-child{border-top-width:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__group-heading{background-color:#e6e6e6;color:rgba(34,47,62,.7);cursor:default;font-size:12px;font-style:normal;font-weight:400;margin-bottom:4px;margin-top:-4px;padding:4px 8px;text-transform:none;-webkit-touch-callout:none;-webkit-user-select:none;user-select:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item{align-items:center;color:#222f3e;cursor:pointer;display:flex;-webkit-touch-callout:none;-webkit-user-select:none;user-select:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__item{padding:4px 8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--toolbar .tinymce__oxide--tox-collection__item{border-radius:3px;padding:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--grid .tinymce__oxide--tox-collection__item{border-radius:3px;padding:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__item--enabled{background-color:#fff;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__item--active{background-color:#dee0e2}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--toolbar .tinymce__oxide--tox-collection__item--enabled{background-color:#c8cbcf;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--toolbar .tinymce__oxide--tox-collection__item--active{background-color:#dee0e2}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--grid .tinymce__oxide--tox-collection__item--enabled{background-color:#c8cbcf;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--grid .tinymce__oxide--tox-collection__item--active:not(.tinymce__oxide--tox-collection__item--state-disabled){background-color:#dee0e2;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__item--active:not(.tinymce__oxide--tox-collection__item--state-disabled){color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--toolbar .tinymce__oxide--tox-collection__item--active:not(.tinymce__oxide--tox-collection__item--state-disabled){color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item--state-disabled{background-color:transparent;color:rgba(34,47,62,.5);cursor:not-allowed}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-checkmark,.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-icon{align-items:center;display:flex;height:24px;justify-content:center;width:24px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-checkmark svg,.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-icon svg{fill:currentColor}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--toolbar-lg .tinymce__oxide--tox-collection__item-icon{height:48px;width:48px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-label{color:currentColor;display:inline-block;flex:1;-ms-flex-preferred-size:auto;font-size:14px;font-style:normal;font-weight:400;line-height:24px;text-transform:none;word-break:break-all}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-accessory{color:rgba(34,47,62,.7);display:inline-block;font-size:14px;height:24px;line-height:24px;text-transform:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-caret{align-items:center;display:flex;min-height:24px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-caret::after{content:\'\';font-size:0;min-height:inherit}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-caret svg{fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__item:not(.tinymce__oxide--tox-collection__item--enabled) .tinymce__oxide--tox-collection__item-checkmark svg{display:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__item:not(.tinymce__oxide--tox-collection__item--enabled) .tinymce__oxide--tox-collection__item-accessory+.tinymce__oxide--tox-collection__item-checkmark{display:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--horizontal{background-color:#fff;border:1px solid #ccc;border-radius:3px;box-shadow:0 1px 3px rgba(0,0,0,.15);display:flex;flex:0 0 auto;flex-shrink:0;flex-wrap:nowrap;margin-bottom:0;overflow-x:auto;padding:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--horizontal .tinymce__oxide--tox-collection__group{align-items:center;display:flex;flex-wrap:nowrap;margin:0;padding:0 4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--horizontal .tinymce__oxide--tox-collection__item{height:34px;margin:2px 0 3px 0;padding:0 4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--horizontal .tinymce__oxide--tox-collection__item-label{white-space:nowrap}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--horizontal .tinymce__oxide--tox-collection__item-caret{margin-left:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container{display:flex}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--row{align-items:center;flex:1 1 auto;flex-direction:row}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--row.tinymce__oxide--tox-collection__item-container--align-left{margin-right:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--row.tinymce__oxide--tox-collection__item-container--align-right{justify-content:flex-end;margin-left:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--row.tinymce__oxide--tox-collection__item-container--valign-top{align-items:flex-start;margin-bottom:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--row.tinymce__oxide--tox-collection__item-container--valign-middle{align-items:center}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--row.tinymce__oxide--tox-collection__item-container--valign-bottom{align-items:flex-end;margin-top:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--column{align-self:center;flex:1 1 auto;flex-direction:column}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--column.tinymce__oxide--tox-collection__item-container--align-left{align-items:flex-start}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--column.tinymce__oxide--tox-collection__item-container--align-right{align-items:flex-end}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--column.tinymce__oxide--tox-collection__item-container--valign-top{align-self:flex-start}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--column.tinymce__oxide--tox-collection__item-container--valign-middle{align-self:center}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection__item-container--column.tinymce__oxide--tox-collection__item-container--valign-bottom{align-self:flex-end}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-collection--horizontal .tinymce__oxide--tox-collection__group:not(:last-of-type){border-right:1px solid #ccc}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__item>:not(:first-child){margin-left:8px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__item>.tinymce__oxide--tox-collection__item-label:first-child{margin-left:4px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-collection__item-accessory{margin-left:16px;text-align:right}\n\n[dir="ltr"] .tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-collection__item-accessory{text-align:right}\n\n[dir="rtl"] .tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-collection__item-accessory{text-align:right}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-collection .tinymce__oxide--tox-collection__item-caret{margin-left:16px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-collection--horizontal .tinymce__oxide--tox-collection__group:not(:last-of-type){border-left:1px solid #ccc}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__item>:not(:first-child){margin-right:8px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__item>.tinymce__oxide--tox-collection__item-label:first-child{margin-right:4px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-collection__item-icon-rtl .tinymce__oxide--tox-collection__item-icon svg{transform:rotateY(180deg)}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-collection__item-accessory{margin-right:16px;text-align:left}\n\n[dir="ltr"] .tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-collection__item-accessory{text-align:left}\n\n[dir="rtl"] .tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-collection__item-accessory{text-align:left}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-collection .tinymce__oxide--tox-collection__item-caret{margin-right:16px;transform:rotateY(180deg)}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-collection--horizontal .tinymce__oxide--tox-collection__item-caret{margin-right:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-color-picker-container{display:flex;flex-direction:row;height:225px;margin:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sv-palette{box-sizing:border-box;display:flex;height:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sv-palette-spectrum{height:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sv-palette,.tinymce__oxide--tox .tinymce__oxide--tox-sv-palette-spectrum{width:225px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sv-palette-thumb{background:0 0;border:1px solid #000;border-radius:50%;box-sizing:content-box;height:12px;position:absolute;width:12px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sv-palette-inner-thumb{border:1px solid #fff;border-radius:50%;height:10px;position:absolute;width:10px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-hue-slider{box-sizing:border-box;height:100%;width:25px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-hue-slider-spectrum{background:linear-gradient(to bottom,red,#ff0080,#f0f,#8000ff,#00f,#0080ff,#0ff,#00ff80,#0f0,#80ff00,#ff0,#ff8000,red);height:100%;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-hue-slider,.tinymce__oxide--tox .tinymce__oxide--tox-hue-slider-spectrum{width:20px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-hue-slider-thumb{background:#fff;border:1px solid #000;box-sizing:content-box;height:4px;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-rgb-form{display:flex;flex-direction:column;justify-content:space-between}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-rgb-form div{align-items:center;display:flex;justify-content:space-between;margin-bottom:5px;width:inherit}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-rgb-form input{width:6em}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-rgb-form input.tinymce__oxide--tox-invalid{border:1px solid red!important}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-rgb-form .tinymce__oxide--tox-rgba-preview{border:1px solid #000;flex-grow:2;margin-bottom:0}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-sv-palette{margin-right:15px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-hue-slider{margin-right:15px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-hue-slider-thumb{margin-left:-1px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-rgb-form label{margin-right:.5em}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-sv-palette{margin-left:15px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-hue-slider{margin-left:15px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-hue-slider-thumb{margin-right:-1px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-rgb-form label{margin-left:.5em}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar .tinymce__oxide--tox-swatches,.tinymce__oxide--tox .tinymce__oxide--tox-toolbar__overflow .tinymce__oxide--tox-swatches,.tinymce__oxide--tox .tinymce__oxide--tox-toolbar__primary .tinymce__oxide--tox-swatches{margin:2px 0 3px 4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__group .tinymce__oxide--tox-swatches-menu{border:0;margin:-4px 0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-swatches__row{display:flex}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-swatch{height:30px;transition:transform .15s,box-shadow .15s;width:30px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-swatch:focus,.tinymce__oxide--tox .tinymce__oxide--tox-swatch:hover{box-shadow:0 0 0 1px rgba(127,127,127,.3) inset;transform:scale(.8)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-swatch--remove{align-items:center;display:flex;justify-content:center}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-swatch--remove svg path{stroke:#e74c3c}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-swatches__picker-btn{align-items:center;background-color:transparent;border:0;cursor:pointer;display:flex;height:30px;justify-content:center;outline:0;padding:0;width:30px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-swatches__picker-btn svg{height:24px;width:24px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-swatches__picker-btn:hover{background:#dee0e2}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-swatches__picker-btn{margin-left:auto}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-swatches__picker-btn{margin-right:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment-thread{background:#fff;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment-thread>:not(:first-child){margin-top:8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment{background:#fff;border:1px solid #ccc;border-radius:3px;box-shadow:0 4px 8px 0 rgba(34,47,62,.1);padding:8px 8px 16px 8px;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__header{align-items:center;color:#222f3e;display:flex;justify-content:space-between}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__date{color:rgba(34,47,62,.7);font-size:12px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__body{color:#222f3e;font-size:14px;font-style:normal;font-weight:400;line-height:1.3;margin-top:8px;position:relative;text-transform:none;text-transform:initial}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__body textarea{resize:none;white-space:normal;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__expander{padding-top:8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__expander p{color:rgba(34,47,62,.7);font-size:14px;font-style:normal}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__body p{margin:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__buttonspacing{padding-top:16px;text-align:center}\n\n[dir="ltr"] .tinymce__oxide--tox .tinymce__oxide--tox-comment__buttonspacing{text-align:center}\n\n[dir="rtl"] .tinymce__oxide--tox .tinymce__oxide--tox-comment__buttonspacing{text-align:center}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment-thread__overlay::after{background:#fff;bottom:0;content:"";display:flex;left:0;opacity:.9;position:absolute;right:0;top:0;z-index:5}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__reply{display:flex;flex-shrink:0;flex-wrap:wrap;justify-content:flex-end;margin-top:8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__reply>:first-child{margin-bottom:8px;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__edit{display:flex;flex-wrap:wrap;justify-content:flex-end;margin-top:16px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__gradient::after{background:linear-gradient(rgba(255,255,255,0),#fff);bottom:0;content:"";display:block;height:5em;margin-top:-40px;position:absolute;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__overlay{background:#fff;bottom:0;display:flex;flex-direction:column;flex-grow:1;left:0;opacity:.9;position:absolute;right:0;text-align:center;top:0;z-index:5}\n\n[dir="ltr"] .tinymce__oxide--tox .tinymce__oxide--tox-comment__overlay{text-align:center}\n\n[dir="rtl"] .tinymce__oxide--tox .tinymce__oxide--tox-comment__overlay{text-align:center}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__loading-text{align-items:center;color:#222f3e;display:flex;flex-direction:column;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__loading-text>div{padding-bottom:16px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__overlaytext{bottom:0;flex-direction:column;font-size:14px;left:0;padding:1em;position:absolute;right:0;top:0;z-index:10}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__overlaytext p{background-color:#fff;box-shadow:0 0 8px 8px #fff;color:#222f3e;text-align:center}\n\n[dir="ltr"] .tinymce__oxide--tox .tinymce__oxide--tox-comment__overlaytext p{text-align:center}\n\n[dir="rtl"] .tinymce__oxide--tox .tinymce__oxide--tox-comment__overlaytext p{text-align:center}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__overlaytext div:nth-of-type(2){font-size:.8em}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__busy-spinner{align-items:center;background-color:#fff;bottom:0;display:flex;justify-content:center;left:0;position:absolute;right:0;top:0;z-index:20}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-comment__scroll{display:flex;flex-direction:column;flex-shrink:1;overflow:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-conversations{margin:8px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-comment__edit{margin-left:8px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-comment__buttonspacing>:last-child,.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-comment__edit>:last-child,.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-comment__reply>:last-child{margin-left:8px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-comment__edit{margin-right:8px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-comment__buttonspacing>:last-child,.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-comment__edit>:last-child,.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-comment__reply>:last-child{margin-right:8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-user{align-items:center;display:flex}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-user__avatar svg{fill:rgba(34,47,62,.7)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-user__name{color:rgba(34,47,62,.7);font-size:12px;font-style:normal;font-weight:700;text-transform:uppercase}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-user__avatar svg{margin-right:8px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-user__avatar+.tinymce__oxide--tox-user__name{margin-left:8px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-user__avatar svg{margin-left:8px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-user__avatar+.tinymce__oxide--tox-user__name{margin-right:8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog-wrap{align-items:center;bottom:0;display:flex;justify-content:center;left:0;position:fixed;right:0;top:0;z-index:1100}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog-wrap__backdrop{background-color:rgba(255,255,255,.75);bottom:0;left:0;position:absolute;right:0;top:0;z-index:1}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog-wrap__backdrop--opaque{background-color:#fff}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog{background-color:#fff;border-color:#ccc;border-radius:3px;border-style:solid;border-width:1px;box-shadow:0 16px 16px -10px rgba(34,47,62,.15),0 0 40px 1px rgba(34,47,62,.15);display:flex;flex-direction:column;max-height:100%;max-width:480px;overflow:hidden;position:relative;width:95vw;z-index:2}\n\n@media only screen and (max-width:767px){body:not(.tinymce__oxide--tox-force-desktop) .tinymce__oxide--tox .tinymce__oxide--tox-dialog{align-self:flex-start;margin:8px auto;width:calc(100vw - 16px)}}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog-inline{z-index:1100}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__header{align-items:center;background-color:#fff;border-bottom:none;color:#222f3e;display:flex;font-size:16px;justify-content:space-between;padding:8px 16px 0 16px;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__header .tinymce__oxide--tox-button{z-index:1}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__draghandle{cursor:grab;height:100%;left:0;position:absolute;top:0;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__draghandle:active{cursor:grabbing}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__dismiss{margin-left:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__title{font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",sans-serif;font-size:20px;font-style:normal;font-weight:400;line-height:1.3;margin:0;text-transform:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body{color:#222f3e;display:flex;flex:1;-ms-flex-preferred-size:auto;font-size:16px;font-style:normal;font-weight:400;line-height:1.3;min-width:0;text-align:left;text-transform:none}\n\n[dir="ltr"] .tinymce__oxide--tox .tinymce__oxide--tox-dialog__body{text-align:left}\n\n[dir="rtl"] .tinymce__oxide--tox .tinymce__oxide--tox-dialog__body{text-align:left}\n\n@media only screen and (max-width:767px){body:not(.tinymce__oxide--tox-force-desktop) .tinymce__oxide--tox .tinymce__oxide--tox-dialog__body{flex-direction:column}}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-nav{align-items:flex-start;display:flex;flex-direction:column;padding:16px 16px}\n\n@media only screen and (max-width:767px){body:not(.tinymce__oxide--tox-force-desktop) .tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-nav{flex-direction:row;-webkit-overflow-scrolling:touch;overflow-x:auto;padding-bottom:0}}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-nav-item{border-bottom:2px solid transparent;color:rgba(34,47,62,.7);display:inline-block;font-size:14px;line-height:1.3;margin-bottom:8px;text-decoration:none;white-space:nowrap}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-nav-item:focus{background-color:rgba(32,122,183,.1)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-nav-item--active{border-bottom:2px solid #207ab7;color:#207ab7}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content{box-sizing:border-box;display:flex;flex:1;flex-direction:column;-ms-flex-preferred-size:auto;max-height:650px;overflow:auto;-webkit-overflow-scrolling:touch;padding:16px 16px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content>*{margin-bottom:0;margin-top:16px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content>:first-child{margin-top:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content>:last-child{margin-bottom:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content>:only-child{margin-bottom:0;margin-top:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content a{color:#207ab7;cursor:pointer;text-decoration:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content a:focus,.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content a:hover{color:#185d8c;text-decoration:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content a:active{color:#185d8c;text-decoration:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content svg{fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content ul{display:block;list-style-type:disc;margin-bottom:16px;margin-inline-end:0;margin-inline-start:0;padding-inline-start:2.5rem}\n\n[dir="ltr"] .tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content ul{margin-right:0;margin-left:0;padding-left:2.5rem}\n\n[dir="rtl"] .tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content ul{margin-left:0;margin-right:0;padding-right:2.5rem}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group h1{color:#222f3e;font-size:20px;font-style:normal;font-weight:700;letter-spacing:normal;margin-bottom:16px;margin-top:2rem;text-transform:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group h2{color:#222f3e;font-size:16px;font-style:normal;font-weight:700;letter-spacing:normal;margin-bottom:16px;margin-top:2rem;text-transform:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group p{margin-bottom:16px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group h1:first-child,.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group h2:first-child,.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group p:first-child{margin-top:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group h1:last-child,.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group h2:last-child,.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group p:last-child{margin-bottom:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group h1:only-child,.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group h2:only-child,.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-form__group p:only-child{margin-bottom:0;margin-top:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog--width-lg{height:650px;max-width:1200px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog--width-md{max-width:800px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog--width-md .tinymce__oxide--tox-dialog__body-content{overflow:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content--centered{text-align:center}\n\n[dir="ltr"] .tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content--centered{text-align:center}\n\n[dir="rtl"] .tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content--centered{text-align:center}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__footer{align-items:center;background-color:#fff;border-top:1px solid #ccc;display:flex;justify-content:space-between;padding:8px 16px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__footer-end,.tinymce__oxide--tox .tinymce__oxide--tox-dialog__footer-start{display:flex}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__busy-spinner{align-items:center;background-color:rgba(255,255,255,.75);bottom:0;display:flex;justify-content:center;left:0;position:absolute;right:0;top:0;z-index:3}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__table{border-collapse:collapse;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__table thead th{font-weight:700;padding-bottom:8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__table tbody tr{border-bottom:1px solid #ccc}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__table tbody tr:last-child{border-bottom:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__table td{padding-bottom:8px;padding-top:8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__popups{position:absolute;width:100%;z-index:1100}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-iframe{display:flex;flex:1;flex-direction:column;-ms-flex-preferred-size:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-iframe .tinymce__oxide--tox-navobj{display:flex;flex:1;-ms-flex-preferred-size:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-iframe .tinymce__oxide--tox-navobj :nth-child(2){flex:1;-ms-flex-preferred-size:auto;height:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog-dock-fadeout{opacity:0;visibility:hidden}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog-dock-fadein{opacity:1;visibility:visible}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog-dock-transition{transition:visibility 0s linear .3s,opacity .3s ease}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog-dock-transition.tinymce__oxide--tox-dialog-dock-fadein{transition-delay:0s}\n\n.tinymce__oxide--tox.tinymce__oxide--tox-platform-ie .tinymce__oxide--tox-dialog-wrap{position:-ms-device-fixed}\n\n@media only screen and (max-width:767px){body:not(.tinymce__oxide--tox-force-desktop) .tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-dialog__body-nav{margin-right:0}}\n\n@media only screen and (max-width:767px){body:not(.tinymce__oxide--tox-force-desktop) .tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-dialog__body-nav-item:not(:first-child){margin-left:8px}}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-dialog__footer .tinymce__oxide--tox-dialog__footer-end>*,.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-dialog__footer .tinymce__oxide--tox-dialog__footer-start>*{margin-left:8px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-dialog__body{text-align:right}\n\n[dir="ltr"] .tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-dialog__body{text-align:right}\n\n[dir="rtl"] .tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-dialog__body{text-align:right}\n\n@media only screen and (max-width:767px){body:not(.tinymce__oxide--tox-force-desktop) .tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-dialog__body-nav{margin-left:0}}\n\n@media only screen and (max-width:767px){body:not(.tinymce__oxide--tox-force-desktop) .tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-dialog__body-nav-item:not(:first-child){margin-right:8px}}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-dialog__footer .tinymce__oxide--tox-dialog__footer-end>*,.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-dialog__footer .tinymce__oxide--tox-dialog__footer-start>*{margin-right:8px}\n\nbody.tinymce__oxide--tox-dialog__disable-scroll{overflow:hidden}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dropzone-container{display:flex;flex:1;-ms-flex-preferred-size:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dropzone{align-items:center;background:#fff;border:2px dashed #ccc;box-sizing:border-box;display:flex;flex-direction:column;flex-grow:1;justify-content:center;min-height:100px;padding:10px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dropzone p{color:rgba(34,47,62,.7);margin:0 0 16px 0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-edit-area{display:flex;flex:1;-ms-flex-preferred-size:auto;overflow:hidden;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-edit-area__iframe{background-color:#fff;border:0;box-sizing:border-box;flex:1;-ms-flex-preferred-size:auto;height:100%;position:absolute;width:100%}\n\n.tinymce__oxide--tox.tinymce__oxide--tox-inline-edit-area{border:1px dotted #ccc}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-editor-container{display:flex;flex:1 1 auto;flex-direction:column;overflow:hidden}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-editor-header{z-index:1}\n\n.tinymce__oxide--tox:not(.tinymce__oxide--tox-tinymce-inline) .tinymce__oxide--tox-editor-header{box-shadow:none;transition:box-shadow .5s}\n\n.tinymce__oxide--tox.tinymce__oxide--tox-tinymce--toolbar-bottom .tinymce__oxide--tox-editor-header,.tinymce__oxide--tox.tinymce__oxide--tox-tinymce-inline .tinymce__oxide--tox-editor-header{margin-bottom:-1px}\n\n.tinymce__oxide--tox.tinymce__oxide--tox-tinymce--toolbar-sticky-on .tinymce__oxide--tox-editor-header{background-color:transparent;box-shadow:0 4px 4px -3px rgba(0,0,0,.25)}\n\n.tinymce__oxide--tox-editor-dock-fadeout{opacity:0;visibility:hidden}\n\n.tinymce__oxide--tox-editor-dock-fadein{opacity:1;visibility:visible}\n\n.tinymce__oxide--tox-editor-dock-transition{transition:visibility 0s linear .25s,opacity .25s ease}\n\n.tinymce__oxide--tox-editor-dock-transition.tinymce__oxide--tox-editor-dock-fadein{transition-delay:0s}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-control-wrap{flex:1;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-control-wrap:not(.tinymce__oxide--tox-control-wrap--status-invalid) .tinymce__oxide--tox-control-wrap__status-icon-invalid,.tinymce__oxide--tox .tinymce__oxide--tox-control-wrap:not(.tinymce__oxide--tox-control-wrap--status-unknown) .tinymce__oxide--tox-control-wrap__status-icon-unknown,.tinymce__oxide--tox .tinymce__oxide--tox-control-wrap:not(.tinymce__oxide--tox-control-wrap--status-valid) .tinymce__oxide--tox-control-wrap__status-icon-valid{display:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-control-wrap svg{display:block}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-control-wrap__status-icon-wrap{position:absolute;top:50%;transform:translateY(-50%)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-control-wrap__status-icon-invalid svg{fill:#c00}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-control-wrap__status-icon-unknown svg{fill:orange}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-control-wrap__status-icon-valid svg{fill:green}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-control-wrap--status-invalid .tinymce__oxide--tox-textfield,.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-control-wrap--status-unknown .tinymce__oxide--tox-textfield,.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-control-wrap--status-valid .tinymce__oxide--tox-textfield{padding-right:32px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-control-wrap__status-icon-wrap{right:4px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-control-wrap--status-invalid .tinymce__oxide--tox-textfield,.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-control-wrap--status-unknown .tinymce__oxide--tox-textfield,.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-control-wrap--status-valid .tinymce__oxide--tox-textfield{padding-left:32px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-control-wrap__status-icon-wrap{left:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-autocompleter{max-width:25em}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-autocompleter .tinymce__oxide--tox-menu{max-width:25em}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-autocompleter .tinymce__oxide--tox-autocompleter-highlight{font-weight:700}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-color-input{display:flex;position:relative;z-index:1}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-color-input .tinymce__oxide--tox-textfield{z-index:-1}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-color-input span{border-color:rgba(34,47,62,.2);border-radius:3px;border-style:solid;border-width:1px;box-shadow:none;box-sizing:border-box;height:24px;position:absolute;top:6px;width:24px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-color-input span:focus:not([aria-disabled=true]),.tinymce__oxide--tox .tinymce__oxide--tox-color-input span:hover:not([aria-disabled=true]){border-color:#207ab7;cursor:pointer}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-color-input span::before{background-image:linear-gradient(45deg,rgba(0,0,0,.25) 25%,transparent 25%),linear-gradient(-45deg,rgba(0,0,0,.25) 25%,transparent 25%),linear-gradient(45deg,transparent 75%,rgba(0,0,0,.25) 75%),linear-gradient(-45deg,transparent 75%,rgba(0,0,0,.25) 75%);background-position:0 0,0 6px,6px -6px,-6px 0;background-size:12px 12px;border:1px solid #fff;border-radius:3px;box-sizing:border-box;content:\'\';height:24px;left:-1px;position:absolute;top:-1px;width:24px;z-index:-1}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-color-input span[aria-disabled=true]{cursor:not-allowed}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-color-input .tinymce__oxide--tox-textfield{padding-left:36px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-color-input span{left:6px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-color-input .tinymce__oxide--tox-textfield{padding-right:36px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-color-input span{right:6px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-label,.tinymce__oxide--tox .tinymce__oxide--tox-toolbar-label{color:rgba(34,47,62,.7);display:block;font-size:14px;font-style:normal;font-weight:400;line-height:1.3;padding:0 8px 0 0;text-transform:none;white-space:nowrap}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar-label{padding:0 8px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-label{padding:0 0 0 8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form{display:flex;flex:1;flex-direction:column;-ms-flex-preferred-size:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__group{box-sizing:border-box;margin-bottom:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form-group--maximize{flex:1}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__group--error{color:#c00}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__group--collection{display:flex}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__grid{display:flex;flex-direction:row;flex-wrap:wrap;justify-content:space-between}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__grid--2col>.tinymce__oxide--tox-form__group{width:calc(50% - (8px / 2))}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__grid--3col>.tinymce__oxide--tox-form__group{width:calc(100% / 3 - (8px / 2))}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__grid--4col>.tinymce__oxide--tox-form__group{width:calc(25% - (8px / 2))}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__controls-h-stack{align-items:center;display:flex}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__group--inline{align-items:center;display:flex}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__group--stretched{display:flex;flex:1;flex-direction:column;-ms-flex-preferred-size:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__group--stretched .tinymce__oxide--tox-textarea{flex:1;-ms-flex-preferred-size:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__group--stretched .tinymce__oxide--tox-navobj{display:flex;flex:1;-ms-flex-preferred-size:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-form__group--stretched .tinymce__oxide--tox-navobj :nth-child(2){flex:1;-ms-flex-preferred-size:auto;height:100%}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-form__controls-h-stack>:not(:first-child){margin-left:4px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-form__controls-h-stack>:not(:first-child){margin-right:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-lock.tinymce__oxide--tox-locked .tinymce__oxide--tox-lock-icon__unlock,.tinymce__oxide--tox .tinymce__oxide--tox-lock:not(.tinymce__oxide--tox-locked) .tinymce__oxide--tox-lock-icon__lock{display:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-listboxfield .tinymce__oxide--tox-listbox--select,.tinymce__oxide--tox .tinymce__oxide--tox-textarea,.tinymce__oxide--tox .tinymce__oxide--tox-textfield,.tinymce__oxide--tox .tinymce__oxide--tox-toolbar-textfield{-webkit-appearance:none;appearance:none;background-color:#fff;border-color:#ccc;border-radius:3px;border-style:solid;border-width:1px;box-shadow:none;box-sizing:border-box;color:#222f3e;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",sans-serif;font-size:16px;line-height:24px;margin:0;min-height:34px;outline:0;padding:5px 4.75px;resize:none;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-textarea[disabled],.tinymce__oxide--tox .tinymce__oxide--tox-textfield[disabled]{background-color:#f2f2f2;color:rgba(34,47,62,.85);cursor:not-allowed}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-listboxfield .tinymce__oxide--tox-listbox--select:focus,.tinymce__oxide--tox .tinymce__oxide--tox-textarea:focus,.tinymce__oxide--tox .tinymce__oxide--tox-textfield:focus{background-color:#fff;border-color:#207ab7;box-shadow:none;outline:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar-textfield{border-width:0;margin-bottom:3px;margin-top:2px;max-width:250px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-naked-btn{background-color:transparent;border:0;border-color:transparent;box-shadow:unset;color:#207ab7;cursor:pointer;display:block;margin:0;padding:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-naked-btn svg{display:block;fill:#222f3e}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-toolbar-textfield+*{margin-left:4px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-toolbar-textfield+*{margin-right:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-listboxfield{cursor:pointer;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-listboxfield .tinymce__oxide--tox-listbox--select[disabled]{background-color:#f2f2f2;color:rgba(34,47,62,.85);cursor:not-allowed}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-listbox__select-label{cursor:default;flex:1;margin:0 4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-listbox__select-chevron{align-items:center;display:flex;justify-content:center;width:16px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-listbox__select-chevron svg{fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-listboxfield .tinymce__oxide--tox-listbox--select{align-items:center;display:flex}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-listboxfield svg{right:8px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-listboxfield svg{left:8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-selectfield{cursor:pointer;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-selectfield select{-webkit-appearance:none;appearance:none;background-color:#fff;border-color:#ccc;border-radius:3px;border-style:solid;border-width:1px;box-shadow:none;box-sizing:border-box;color:#222f3e;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",sans-serif;font-size:16px;line-height:24px;margin:0;min-height:34px;outline:0;padding:5px 4.75px;resize:none;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-selectfield select[disabled]{background-color:#f2f2f2;color:rgba(34,47,62,.85);cursor:not-allowed}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-selectfield select::-ms-expand{display:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-selectfield select:focus{background-color:#fff;border-color:#207ab7;box-shadow:none;outline:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-selectfield svg{pointer-events:none;position:absolute;top:50%;transform:translateY(-50%)}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-selectfield select[size="0"],.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-selectfield select[size="1"]{padding-right:24px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-selectfield svg{right:8px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-selectfield select[size="0"],.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-selectfield select[size="1"]{padding-left:24px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-selectfield svg{left:8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-textarea{-webkit-appearance:textarea;appearance:textarea;white-space:pre-wrap}\n\n.tinymce__oxide--tox-fullscreen{border:0;height:100%;left:0;margin:0;overflow:hidden;overscroll-behavior:none;padding:0;position:fixed;top:0;touch-action:pinch-zoom;width:100%}\n\n.tinymce__oxide--tox.tinymce__oxide--tox-tinymce.tinymce__oxide--tox-fullscreen .tinymce__oxide--tox-statusbar__resize-handle{display:none}\n\n.tinymce__oxide--tox.tinymce__oxide--tox-tinymce.tinymce__oxide--tox-fullscreen{background-color:transparent;z-index:1200}\n\n.tinymce__oxide--tox-shadowhost.tinymce__oxide--tox-fullscreen{z-index:1200}\n\n.tinymce__oxide--tox-fullscreen .tinymce__oxide--tox.tinymce__oxide--tox-tinymce-aux,.tinymce__oxide--tox-fullscreen~.tinymce__oxide--tox.tinymce__oxide--tox-tinymce-aux{z-index:1201}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-help__more-link{list-style:none;margin-top:1em}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-image-tools{width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-image-tools__toolbar{align-items:center;display:flex;justify-content:center}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-image-tools__image{background-color:#666;height:380px;overflow:auto;position:relative;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-image-tools__image,.tinymce__oxide--tox .tinymce__oxide--tox-image-tools__image+.tinymce__oxide--tox-image-tools__toolbar{margin-top:8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-image-tools__image-bg{background:url(data:image/gif;base64,R0lGODdhDAAMAIABAMzMzP///ywAAAAADAAMAAACFoQfqYeabNyDMkBQb81Uat85nxguUAEAOw==)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-image-tools__toolbar>.tinymce__oxide--tox-spacer{flex:1;-ms-flex-preferred-size:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-croprect-block{background:#000;opacity:.5;position:absolute;zoom:1}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-croprect-handle{border:2px solid #fff;height:20px;left:0;position:absolute;top:0;width:20px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-croprect-handle-move{border:0;cursor:move;position:absolute}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-croprect-handle-nw{border-width:2px 0 0 2px;cursor:nw-resize;left:100px;margin:-2px 0 0 -2px;top:100px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-croprect-handle-ne{border-width:2px 2px 0 0;cursor:ne-resize;left:200px;margin:-2px 0 0 -20px;top:100px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-croprect-handle-sw{border-width:0 0 2px 2px;cursor:sw-resize;left:100px;margin:-20px 2px 0 -2px;top:200px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-croprect-handle-se{border-width:0 2px 2px 0;cursor:se-resize;left:200px;margin:-20px 0 0 -20px;top:200px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-image-tools__toolbar>.tinymce__oxide--tox-slider:not(:first-of-type){margin-left:8px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-image-tools__toolbar>.tinymce__oxide--tox-button+.tinymce__oxide--tox-slider{margin-left:32px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-image-tools__toolbar>.tinymce__oxide--tox-slider+.tinymce__oxide--tox-button{margin-left:32px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-image-tools__toolbar>.tinymce__oxide--tox-slider:not(:first-of-type){margin-right:8px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-image-tools__toolbar>.tinymce__oxide--tox-button+.tinymce__oxide--tox-slider{margin-right:32px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-image-tools__toolbar>.tinymce__oxide--tox-slider+.tinymce__oxide--tox-button{margin-right:32px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-insert-table-picker{display:flex;flex-wrap:wrap;width:170px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-insert-table-picker>div{border-color:#ccc;border-style:solid;border-width:0 1px 1px 0;box-sizing:border-box;height:17px;width:17px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-collection--list .tinymce__oxide--tox-collection__group .tinymce__oxide--tox-insert-table-picker{margin:-4px 0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-insert-table-picker .tinymce__oxide--tox-insert-table-picker__selected{background-color:rgba(32,122,183,.5);border-color:rgba(32,122,183,.5)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-insert-table-picker__label{color:rgba(34,47,62,.7);display:block;font-size:14px;padding:4px;text-align:center;width:100%}\n\n[dir="ltr"] .tinymce__oxide--tox .tinymce__oxide--tox-insert-table-picker__label{text-align:center}\n\n[dir="rtl"] .tinymce__oxide--tox .tinymce__oxide--tox-insert-table-picker__label{text-align:center}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-insert-table-picker>div:nth-child(10n){border-right:0}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-insert-table-picker>div:nth-child(10n+1){border-right:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-menu{background-color:#fff;border:1px solid #ccc;border-radius:3px;box-shadow:0 4px 8px 0 rgba(34,47,62,.1);display:inline-block;overflow:hidden;vertical-align:top;z-index:1150}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-menu.tinymce__oxide--tox-collection.tinymce__oxide--tox-collection--list{padding:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-menu.tinymce__oxide--tox-collection.tinymce__oxide--tox-collection--toolbar{padding:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-menu.tinymce__oxide--tox-collection.tinymce__oxide--tox-collection--grid{padding:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-menu__label blockquote,.tinymce__oxide--tox .tinymce__oxide--tox-menu__label code,.tinymce__oxide--tox .tinymce__oxide--tox-menu__label h1,.tinymce__oxide--tox .tinymce__oxide--tox-menu__label h2,.tinymce__oxide--tox .tinymce__oxide--tox-menu__label h3,.tinymce__oxide--tox .tinymce__oxide--tox-menu__label h4,.tinymce__oxide--tox .tinymce__oxide--tox-menu__label h5,.tinymce__oxide--tox .tinymce__oxide--tox-menu__label h6,.tinymce__oxide--tox .tinymce__oxide--tox-menu__label p{margin:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-menubar{background:url("data:image/svg+xml;charset=utf8,%3Csvg height=\'39px\' viewBox=\'0 0 40 39px\' width=\'40\' xmlns=\'http://www.w3.org/2000/svg\'%3E%3Crect x=\'0\' y=\'38px\' width=\'100\' height=\'1\' fill=\'%23cccccc\'/%3E%3C/svg%3E") left 0 top 0 #fff;background-color:#fff;display:flex;flex:0 0 auto;flex-shrink:0;flex-wrap:wrap;padding:0 4px 0 4px}\n\n.tinymce__oxide--tox.tinymce__oxide--tox-tinymce:not(.tinymce__oxide--tox-tinymce-inline) .tinymce__oxide--tox-editor-header:not(:first-child) .tinymce__oxide--tox-menubar{border-top:1px solid #ccc}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-mbtn{align-items:center;background:0 0;border:0;border-radius:3px;box-shadow:none;color:#222f3e;display:flex;flex:0 0 auto;font-size:14px;font-style:normal;font-weight:400;height:34px;justify-content:center;margin:2px 0 3px 0;outline:0;overflow:hidden;padding:0 4px;text-transform:none;width:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-mbtn[disabled]{background-color:transparent;border:0;box-shadow:none;color:rgba(34,47,62,.5);cursor:not-allowed}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-mbtn:focus:not(:disabled){background:#dee0e2;border:0;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-mbtn--active{background:#c8cbcf;border:0;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-mbtn:hover:not(:disabled):not(.tinymce__oxide--tox-mbtn--active){background:#dee0e2;border:0;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-mbtn__select-label{cursor:default;font-weight:400;margin:0 4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-mbtn[disabled] .tinymce__oxide--tox-mbtn__select-label{cursor:not-allowed}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-mbtn__select-chevron{align-items:center;display:flex;justify-content:center;width:16px;display:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification{border-radius:3px;border-style:solid;border-width:1px;box-shadow:none;box-sizing:border-box;display:grid;font-size:14px;font-weight:400;grid-template-columns:minmax(40px,1fr) auto minmax(40px,1fr);margin-top:4px;opacity:0;padding:4px;transition:transform .1s ease-in,opacity 150ms ease-in}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification p{font-size:14px;font-weight:400}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification a{text-decoration:underline}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--in{opacity:1}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--success{background-color:#e4eeda;border-color:#d7e6c8;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--success p{color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--success a{color:#547831}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--success svg{fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--error{background-color:#f8dede;border-color:#f2bfbf;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--error p{color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--error a{color:#c00}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--error svg{fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--warn,.tinymce__oxide--tox .tinymce__oxide--tox-notification--warning{background-color:#fffaea;border-color:#ffe89d;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--warn p,.tinymce__oxide--tox .tinymce__oxide--tox-notification--warning p{color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--warn a,.tinymce__oxide--tox .tinymce__oxide--tox-notification--warning a{color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--warn svg,.tinymce__oxide--tox .tinymce__oxide--tox-notification--warning svg{fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--info{background-color:#d9edf7;border-color:#779ecb;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--info p{color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--info a{color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification--info svg{fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification__body{align-self:center;color:#222f3e;font-size:14px;-ms-grid-column-span:1;grid-column-end:3;grid-column-start:2;-ms-grid-row-span:1;grid-row-end:2;grid-row-start:1;text-align:center;white-space:normal;word-break:break-all;word-break:break-word}\n\n[dir="ltr"] .tinymce__oxide--tox .tinymce__oxide--tox-notification__body{text-align:center}\n\n[dir="rtl"] .tinymce__oxide--tox .tinymce__oxide--tox-notification__body{text-align:center}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification__body>*{margin:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification__body>*+*{margin-top:1rem}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification__icon{align-self:center;-ms-grid-column-span:1;grid-column-end:2;grid-column-start:1;-ms-grid-row-span:1;grid-row-end:2;grid-row-start:1;justify-self:end}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification__icon svg{display:block}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification__dismiss{align-self:start;-ms-grid-column-span:1;grid-column-end:4;grid-column-start:3;-ms-grid-row-span:1;grid-row-end:2;grid-row-start:1;justify-self:end}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-notification .tinymce__oxide--tox-progress-bar{-ms-grid-column-span:3;grid-column-end:4;grid-column-start:1;-ms-grid-row-span:1;grid-row-end:3;grid-row-start:2;justify-self:center}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop{display:inline-block;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop--resizing{transition:width .1s ease}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop--resizing .tinymce__oxide--tox-toolbar{flex-wrap:nowrap}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop__dialog{background-color:#fff;border:1px solid #ccc;border-radius:3px;box-shadow:0 1px 3px rgba(0,0,0,.15);min-width:0;overflow:hidden}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop__dialog>:not(.tinymce__oxide--tox-toolbar){margin:4px 4px 4px 8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop__dialog .tinymce__oxide--tox-toolbar{background-color:transparent;margin-bottom:-1px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop::after,.tinymce__oxide--tox .tinymce__oxide--tox-pop::before{border-style:solid;content:\'\';display:block;height:0;position:absolute;width:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--bottom::after,.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--bottom::before{left:50%;top:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--bottom::after{border-color:#fff transparent transparent transparent;border-width:8px;margin-left:-8px;margin-top:-1px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--bottom::before{border-color:#ccc transparent transparent transparent;border-width:9px;margin-left:-9px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--top::after,.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--top::before{left:50%;top:0;transform:translateY(-100%)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--top::after{border-color:transparent transparent #fff transparent;border-width:8px;margin-left:-8px;margin-top:1px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--top::before{border-color:transparent transparent #ccc transparent;border-width:9px;margin-left:-9px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--left::after,.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--left::before{left:0;top:calc(50% - 1px);transform:translateY(-50%)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--left::after{border-color:transparent #fff transparent transparent;border-width:8px;margin-left:-15px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--left::before{border-color:transparent #ccc transparent transparent;border-width:10px;margin-left:-19px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--right::after,.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--right::before{left:100%;top:calc(50% + 1px);transform:translateY(-50%)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--right::after{border-color:transparent transparent transparent #fff;border-width:8px;margin-left:-1px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--right::before{border-color:transparent transparent transparent #ccc;border-width:10px;margin-left:-1px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--align-left::after,.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--align-left::before{left:20px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--align-right::after,.tinymce__oxide--tox .tinymce__oxide--tox-pop.tinymce__oxide--tox-pop--align-right::before{left:calc(100% - 20px)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sidebar-wrap{display:flex;flex-direction:row;flex-grow:1;-ms-flex-preferred-size:0;min-height:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sidebar{background-color:#fff;display:flex;flex-direction:row;justify-content:flex-end}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sidebar__slider{display:flex;overflow:hidden}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sidebar__pane-container{display:flex}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sidebar__pane{display:flex}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sidebar--sliding-closed{opacity:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sidebar--sliding-open{opacity:1}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-sidebar--sliding-growing,.tinymce__oxide--tox .tinymce__oxide--tox-sidebar--sliding-shrinking{transition:width .5s ease,opacity .5s ease}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-selector{background-color:#4099ff;border-color:#4099ff;border-style:solid;border-width:1px;box-sizing:border-box;display:inline-block;height:10px;position:absolute;width:10px}\n\n.tinymce__oxide--tox.tinymce__oxide--tox-platform-touch .tinymce__oxide--tox-selector{height:12px;width:12px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-slider{align-items:center;display:flex;flex:1;-ms-flex-preferred-size:auto;height:24px;justify-content:center;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-slider__rail{background-color:transparent;border:1px solid #ccc;border-radius:3px;height:10px;min-width:120px;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-slider__handle{background-color:#207ab7;border:2px solid #185d8c;border-radius:3px;box-shadow:none;height:24px;left:50%;position:absolute;top:50%;transform:translateX(-50%) translateY(-50%);width:14px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-source-code{overflow:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-spinner{display:flex}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-spinner>div{animation:tinymce__oxide--tam-bouncing-dots 1.5s ease-in-out 0s infinite both;background-color:rgba(34,47,62,.7);border-radius:100%;height:8px;width:8px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-spinner>div:nth-child(1){animation-delay:-.32s}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-spinner>div:nth-child(2){animation-delay:-.16s}\n\n@keyframes tinymce__oxide--tam-bouncing-dots{0%,100%,80%{transform:scale(0)}40%{transform:scale(1)}}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-spinner>div:not(:first-child){margin-left:4px}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-spinner>div:not(:first-child){margin-right:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-statusbar{align-items:center;background-color:#fff;border-top:1px solid #ccc;color:rgba(34,47,62,.7);display:flex;flex:0 0 auto;font-size:12px;font-weight:400;height:18px;overflow:hidden;padding:0 8px;position:relative;text-transform:uppercase}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__text-container{display:flex;flex:1 1 auto;justify-content:flex-end;overflow:hidden}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__path{display:flex;flex:1 1 auto;margin-right:auto;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__path>*{display:inline;white-space:nowrap}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__wordcount{flex:0 0 auto;margin-left:1ch}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-statusbar a,.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__path-item,.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__wordcount{color:rgba(34,47,62,.7);text-decoration:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-statusbar a:focus:not(:disabled):not([aria-disabled=true]),.tinymce__oxide--tox .tinymce__oxide--tox-statusbar a:hover:not(:disabled):not([aria-disabled=true]),.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__path-item:focus:not(:disabled):not([aria-disabled=true]),.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__path-item:hover:not(:disabled):not([aria-disabled=true]),.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__wordcount:focus:not(:disabled):not([aria-disabled=true]),.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__wordcount:hover:not(:disabled):not([aria-disabled=true]){cursor:pointer;text-decoration:underline}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__resize-handle{align-items:flex-end;align-self:stretch;cursor:nwse-resize;display:flex;flex:0 0 auto;justify-content:flex-end;margin-left:auto;margin-right:-8px;padding-left:1ch}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__resize-handle svg{display:block;fill:rgba(34,47,62,.7)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-statusbar__resize-handle:focus svg{background-color:#dee0e2;border-radius:1px;box-shadow:0 0 0 2px #dee0e2}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-statusbar__path>*{margin-right:4px}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-statusbar__branding{margin-left:1ch}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-statusbar{flex-direction:row-reverse}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-statusbar__path>*{margin-left:4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-throbber{z-index:1299}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-throbber__busy-spinner{align-items:center;background-color:rgba(255,255,255,.6);bottom:0;display:flex;justify-content:center;left:0;position:absolute;right:0;top:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn{align-items:center;background:0 0;border:0;border-radius:3px;box-shadow:none;color:#222f3e;display:flex;flex:0 0 auto;font-size:14px;font-style:normal;font-weight:400;height:34px;justify-content:center;margin:2px 0 3px 0;outline:0;overflow:hidden;padding:0;text-transform:none;width:34px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn svg{display:block;fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn.tinymce__oxide--tox-tbtn-more{padding-left:5px;padding-right:5px;width:inherit}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:focus{background:#dee0e2;border:0;box-shadow:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:hover{background:#dee0e2;border:0;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:hover svg{fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:active{background:#c8cbcf;border:0;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:active svg{fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--disabled,.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--disabled:hover,.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:disabled,.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:disabled:hover{background:0 0;border:0;box-shadow:none;color:rgba(34,47,62,.5);cursor:not-allowed}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--disabled svg,.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--disabled:hover svg,.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:disabled svg,.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:disabled:hover svg{fill:rgba(34,47,62,.5)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--enabled,.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--enabled:hover{background:#c8cbcf;border:0;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--enabled:hover>*,.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--enabled>*{transform:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--enabled svg,.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--enabled:hover svg{fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:focus:not(.tinymce__oxide--tox-tbtn--disabled){color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:focus:not(.tinymce__oxide--tox-tbtn--disabled) svg{fill:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn:active>*{transform:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--md{height:51px;width:51px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--lg{flex-direction:column;height:68px;width:68px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--return{align-self:stretch;height:unset;width:16px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--labeled{padding:0 4px;width:unset}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn__vlabel{display:block;font-size:10px;font-weight:400;letter-spacing:-.025em;margin-bottom:4px;white-space:nowrap}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--select{margin:2px 0 3px 0;padding:0 4px;width:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn__select-label{cursor:default;font-weight:400;margin:0 4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn__select-chevron{align-items:center;display:flex;justify-content:center;width:16px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn__select-chevron svg{fill:rgba(34,47,62,.5)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tbtn--bespoke .tinymce__oxide--tox-tbtn__select-label{overflow:hidden;text-overflow:ellipsis;white-space:nowrap;width:7em}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-split-button{border:0;border-radius:3px;box-sizing:border-box;display:flex;margin:2px 0 3px 0;overflow:hidden}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-split-button:hover{box-shadow:0 0 0 1px #dee0e2 inset}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-split-button:focus{background:#dee0e2;box-shadow:none;color:#222f3e}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-split-button>*{border-radius:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-split-button__chevron{width:16px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-split-button__chevron svg{fill:rgba(34,47,62,.5)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-split-button .tinymce__oxide--tox-tbtn{margin:0}\n\n.tinymce__oxide--tox.tinymce__oxide--tox-platform-touch .tinymce__oxide--tox-split-button .tinymce__oxide--tox-tbtn:first-child{width:30px}\n\n.tinymce__oxide--tox.tinymce__oxide--tox-platform-touch .tinymce__oxide--tox-split-button__chevron{width:20px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-split-button.tinymce__oxide--tox-tbtn--disabled .tinymce__oxide--tox-tbtn:focus,.tinymce__oxide--tox .tinymce__oxide--tox-split-button.tinymce__oxide--tox-tbtn--disabled .tinymce__oxide--tox-tbtn:hover,.tinymce__oxide--tox .tinymce__oxide--tox-split-button.tinymce__oxide--tox-tbtn--disabled:focus,.tinymce__oxide--tox .tinymce__oxide--tox-split-button.tinymce__oxide--tox-tbtn--disabled:hover{background:0 0;box-shadow:none;color:rgba(34,47,62,.5)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar-overlord{background-color:#fff}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar,.tinymce__oxide--tox .tinymce__oxide--tox-toolbar__overflow,.tinymce__oxide--tox .tinymce__oxide--tox-toolbar__primary{background:url("data:image/svg+xml;charset=utf8,%3Csvg height=\'39px\' viewBox=\'0 0 40 39px\' width=\'40\' xmlns=\'http://www.w3.org/2000/svg\'%3E%3Crect x=\'0\' y=\'38px\' width=\'100\' height=\'1\' fill=\'%23cccccc\'/%3E%3C/svg%3E") left 0 top 0 #fff;background-color:#fff;display:flex;flex:0 0 auto;flex-shrink:0;flex-wrap:wrap;padding:0 0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar__overflow.tinymce__oxide--tox-toolbar__overflow--closed{height:0;opacity:0;padding-bottom:0;padding-top:0;visibility:hidden}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar__overflow--growing{transition:height .3s ease,opacity .2s linear .1s}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar__overflow--shrinking{transition:opacity .3s ease,height .2s linear .1s,visibility 0s linear .3s}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-menubar+.tinymce__oxide--tox-toolbar,.tinymce__oxide--tox .tinymce__oxide--tox-menubar+.tinymce__oxide--tox-toolbar-overlord .tinymce__oxide--tox-toolbar__primary{border-top:1px solid #ccc;margin-top:-1px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar--scrolling{flex-wrap:nowrap;overflow-x:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-pop .tinymce__oxide--tox-toolbar{border-width:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar--no-divider{background-image:none}\n\n.tinymce__oxide--tox-tinymce:not(.tinymce__oxide--tox-tinymce-inline) .tinymce__oxide--tox-editor-header:not(:first-child) .tinymce__oxide--tox-toolbar-overlord:first-child .tinymce__oxide--tox-toolbar__primary,.tinymce__oxide--tox-tinymce:not(.tinymce__oxide--tox-tinymce-inline) .tinymce__oxide--tox-editor-header:not(:first-child) .tinymce__oxide--tox-toolbar:first-child{border-top:1px solid #ccc}\n\n.tinymce__oxide--tox.tinymce__oxide--tox-tinymce-aux .tinymce__oxide--tox-toolbar__overflow{background-color:#fff;border:1px solid #ccc;border-radius:3px;box-shadow:0 1px 3px rgba(0,0,0,.15)}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-tbtn__icon-rtl svg{transform:rotateY(180deg)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar__group{align-items:center;display:flex;flex-wrap:wrap;margin:0 0;padding:0 4px 0 4px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar__group--pull-right{margin-left:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-toolbar--scrolling .tinymce__oxide--tox-toolbar__group{flex-shrink:0;flex-wrap:nowrap}\n\n.tinymce__oxide--tox:not([dir=rtl]) .tinymce__oxide--tox-toolbar__group:not(:last-of-type){border-right:1px solid #ccc}\n\n.tinymce__oxide--tox[dir=rtl] .tinymce__oxide--tox-toolbar__group:not(:last-of-type){border-left:1px solid #ccc}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tooltip{display:inline-block;padding:8px;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tooltip__body{background-color:#222f3e;border-radius:3px;box-shadow:0 2px 4px rgba(34,47,62,.3);color:rgba(255,255,255,.75);font-size:14px;font-style:normal;font-weight:400;padding:4px 8px;text-transform:none}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tooltip__arrow{position:absolute}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tooltip--down .tinymce__oxide--tox-tooltip__arrow{border-left:8px solid transparent;border-right:8px solid transparent;border-top:8px solid #222f3e;bottom:0;left:50%;position:absolute;transform:translateX(-50%)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tooltip--up .tinymce__oxide--tox-tooltip__arrow{border-bottom:8px solid #222f3e;border-left:8px solid transparent;border-right:8px solid transparent;left:50%;position:absolute;top:0;transform:translateX(-50%)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tooltip--right .tinymce__oxide--tox-tooltip__arrow{border-bottom:8px solid transparent;border-left:8px solid #222f3e;border-top:8px solid transparent;position:absolute;right:0;top:50%;transform:translateY(-50%)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tooltip--left .tinymce__oxide--tox-tooltip__arrow{border-bottom:8px solid transparent;border-right:8px solid #222f3e;border-top:8px solid transparent;left:0;position:absolute;top:50%;transform:translateY(-50%)}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-well{border:1px solid #ccc;border-radius:3px;padding:8px;width:100%}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-well>:first-child{margin-top:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-well>:last-child{margin-bottom:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-well>:only-child{margin:0}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-custom-editor{border:1px solid #ccc;border-radius:3px;display:flex;flex:1;position:relative}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog-loading::before{background-color:rgba(0,0,0,.5);content:"";height:100%;position:absolute;width:100%;z-index:1000}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-tab{cursor:pointer}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__content-js{display:flex;flex:1;-ms-flex-preferred-size:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-dialog__body-content .tinymce__oxide--tox-collection{display:flex;flex:1;-ms-flex-preferred-size:auto}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-image-tools-edit-panel{height:60px}\n\n.tinymce__oxide--tox .tinymce__oxide--tox-image-tools__sidebar{height:60px}\n'},tox:"tinymce__oxide--tox","tox-tinymce":"tinymce__oxide--tox-tinymce","tox-tinymce-inline":"tinymce__oxide--tox-tinymce-inline","tox-editor-header":"tinymce__oxide--tox-editor-header","tox-tinymce-aux":"tinymce__oxide--tox-tinymce-aux","accessibility-issue__header":"tinymce__oxide--accessibility-issue__header","accessibility-issue__description":"tinymce__oxide--accessibility-issue__description","accessibility-issue__repair":"tinymce__oxide--accessibility-issue__repair","tox-dialog__body-content":"tinymce__oxide--tox-dialog__body-content","accessibility-issue--info":"tinymce__oxide--accessibility-issue--info","tox-form__group":"tinymce__oxide--tox-form__group","tox-icon":"tinymce__oxide--tox-icon","accessibility-issue--warn":"tinymce__oxide--accessibility-issue--warn","accessibility-issue--error":"tinymce__oxide--accessibility-issue--error","accessibility-issue--success":"tinymce__oxide--accessibility-issue--success","tox-button":"tinymce__oxide--tox-button","tox-anchorbar":"tinymce__oxide--tox-anchorbar","tox-bar":"tinymce__oxide--tox-bar","tox-button--secondary":"tinymce__oxide--tox-button--secondary","tox-button--icon":"tinymce__oxide--tox-button--icon","tox-button-link":"tinymce__oxide--tox-button-link","tox-button-link--sm":"tinymce__oxide--tox-button-link--sm","tox-button--naked":"tinymce__oxide--tox-button--naked","tox-checkbox":"tinymce__oxide--tox-checkbox","tox-checkbox__input":"tinymce__oxide--tox-checkbox__input","tox-checkbox__icons":"tinymce__oxide--tox-checkbox__icons","tox-checkbox-icon__unchecked":"tinymce__oxide--tox-checkbox-icon__unchecked","tox-checkbox-icon__indeterminate":"tinymce__oxide--tox-checkbox-icon__indeterminate","tox-checkbox-icon__checked":"tinymce__oxide--tox-checkbox-icon__checked","tox-checkbox--disabled":"tinymce__oxide--tox-checkbox--disabled","tox-checkbox__label":"tinymce__oxide--tox-checkbox__label","tox-collection--toolbar":"tinymce__oxide--tox-collection--toolbar","tox-collection__group":"tinymce__oxide--tox-collection__group","tox-collection--grid":"tinymce__oxide--tox-collection--grid","tox-collection--list":"tinymce__oxide--tox-collection--list","tox-collection__group-heading":"tinymce__oxide--tox-collection__group-heading","tox-collection__item":"tinymce__oxide--tox-collection__item","tox-collection__item--enabled":"tinymce__oxide--tox-collection__item--enabled","tox-collection__item--active":"tinymce__oxide--tox-collection__item--active","tox-collection__item--state-disabled":"tinymce__oxide--tox-collection__item--state-disabled","tox-collection__item-checkmark":"tinymce__oxide--tox-collection__item-checkmark","tox-collection__item-icon":"tinymce__oxide--tox-collection__item-icon","tox-collection--toolbar-lg":"tinymce__oxide--tox-collection--toolbar-lg","tox-collection__item-label":"tinymce__oxide--tox-collection__item-label","tox-collection__item-accessory":"tinymce__oxide--tox-collection__item-accessory","tox-collection__item-caret":"tinymce__oxide--tox-collection__item-caret","tox-collection--horizontal":"tinymce__oxide--tox-collection--horizontal","tox-collection__item-container":"tinymce__oxide--tox-collection__item-container","tox-collection__item-container--row":"tinymce__oxide--tox-collection__item-container--row","tox-collection__item-container--align-left":"tinymce__oxide--tox-collection__item-container--align-left","tox-collection__item-container--align-right":"tinymce__oxide--tox-collection__item-container--align-right","tox-collection__item-container--valign-top":"tinymce__oxide--tox-collection__item-container--valign-top","tox-collection__item-container--valign-middle":"tinymce__oxide--tox-collection__item-container--valign-middle","tox-collection__item-container--valign-bottom":"tinymce__oxide--tox-collection__item-container--valign-bottom","tox-collection__item-container--column":"tinymce__oxide--tox-collection__item-container--column","tox-collection":"tinymce__oxide--tox-collection","tox-collection__item-icon-rtl":"tinymce__oxide--tox-collection__item-icon-rtl","tox-color-picker-container":"tinymce__oxide--tox-color-picker-container","tox-sv-palette":"tinymce__oxide--tox-sv-palette","tox-sv-palette-spectrum":"tinymce__oxide--tox-sv-palette-spectrum","tox-sv-palette-thumb":"tinymce__oxide--tox-sv-palette-thumb","tox-sv-palette-inner-thumb":"tinymce__oxide--tox-sv-palette-inner-thumb","tox-hue-slider":"tinymce__oxide--tox-hue-slider","tox-hue-slider-spectrum":"tinymce__oxide--tox-hue-slider-spectrum","tox-hue-slider-thumb":"tinymce__oxide--tox-hue-slider-thumb","tox-rgb-form":"tinymce__oxide--tox-rgb-form","tox-invalid":"tinymce__oxide--tox-invalid","tox-rgba-preview":"tinymce__oxide--tox-rgba-preview","tox-toolbar":"tinymce__oxide--tox-toolbar","tox-swatches":"tinymce__oxide--tox-swatches","tox-toolbar__overflow":"tinymce__oxide--tox-toolbar__overflow","tox-toolbar__primary":"tinymce__oxide--tox-toolbar__primary","tox-swatches-menu":"tinymce__oxide--tox-swatches-menu","tox-swatches__row":"tinymce__oxide--tox-swatches__row","tox-swatch":"tinymce__oxide--tox-swatch","tox-swatch--remove":"tinymce__oxide--tox-swatch--remove","tox-swatches__picker-btn":"tinymce__oxide--tox-swatches__picker-btn","tox-comment-thread":"tinymce__oxide--tox-comment-thread","tox-comment":"tinymce__oxide--tox-comment","tox-comment__header":"tinymce__oxide--tox-comment__header","tox-comment__date":"tinymce__oxide--tox-comment__date","tox-comment__body":"tinymce__oxide--tox-comment__body","tox-comment__expander":"tinymce__oxide--tox-comment__expander","tox-comment__buttonspacing":"tinymce__oxide--tox-comment__buttonspacing","tox-comment-thread__overlay":"tinymce__oxide--tox-comment-thread__overlay","tox-comment__reply":"tinymce__oxide--tox-comment__reply","tox-comment__edit":"tinymce__oxide--tox-comment__edit","tox-comment__gradient":"tinymce__oxide--tox-comment__gradient","tox-comment__overlay":"tinymce__oxide--tox-comment__overlay","tox-comment__loading-text":"tinymce__oxide--tox-comment__loading-text","tox-comment__overlaytext":"tinymce__oxide--tox-comment__overlaytext","tox-comment__busy-spinner":"tinymce__oxide--tox-comment__busy-spinner","tox-comment__scroll":"tinymce__oxide--tox-comment__scroll","tox-conversations":"tinymce__oxide--tox-conversations","tox-user":"tinymce__oxide--tox-user","tox-user__avatar":"tinymce__oxide--tox-user__avatar","tox-user__name":"tinymce__oxide--tox-user__name","tox-dialog-wrap":"tinymce__oxide--tox-dialog-wrap","tox-dialog-wrap__backdrop":"tinymce__oxide--tox-dialog-wrap__backdrop","tox-dialog-wrap__backdrop--opaque":"tinymce__oxide--tox-dialog-wrap__backdrop--opaque","tox-dialog":"tinymce__oxide--tox-dialog","tox-force-desktop":"tinymce__oxide--tox-force-desktop","tox-dialog-inline":"tinymce__oxide--tox-dialog-inline","tox-dialog__header":"tinymce__oxide--tox-dialog__header","tox-dialog__draghandle":"tinymce__oxide--tox-dialog__draghandle","tox-dialog__dismiss":"tinymce__oxide--tox-dialog__dismiss","tox-dialog__title":"tinymce__oxide--tox-dialog__title","tox-dialog__body":"tinymce__oxide--tox-dialog__body","tox-dialog__body-nav":"tinymce__oxide--tox-dialog__body-nav","tox-dialog__body-nav-item":"tinymce__oxide--tox-dialog__body-nav-item","tox-dialog__body-nav-item--active":"tinymce__oxide--tox-dialog__body-nav-item--active","tox-dialog--width-lg":"tinymce__oxide--tox-dialog--width-lg","tox-dialog--width-md":"tinymce__oxide--tox-dialog--width-md","tox-dialog__body-content--centered":"tinymce__oxide--tox-dialog__body-content--centered","tox-dialog__footer":"tinymce__oxide--tox-dialog__footer","tox-dialog__footer-end":"tinymce__oxide--tox-dialog__footer-end","tox-dialog__footer-start":"tinymce__oxide--tox-dialog__footer-start","tox-dialog__busy-spinner":"tinymce__oxide--tox-dialog__busy-spinner","tox-dialog__table":"tinymce__oxide--tox-dialog__table","tox-dialog__popups":"tinymce__oxide--tox-dialog__popups","tox-dialog__body-iframe":"tinymce__oxide--tox-dialog__body-iframe","tox-navobj":"tinymce__oxide--tox-navobj","tox-dialog-dock-fadeout":"tinymce__oxide--tox-dialog-dock-fadeout","tox-dialog-dock-fadein":"tinymce__oxide--tox-dialog-dock-fadein","tox-dialog-dock-transition":"tinymce__oxide--tox-dialog-dock-transition","tox-platform-ie":"tinymce__oxide--tox-platform-ie","tox-dialog__disable-scroll":"tinymce__oxide--tox-dialog__disable-scroll","tox-dropzone-container":"tinymce__oxide--tox-dropzone-container","tox-dropzone":"tinymce__oxide--tox-dropzone","tox-edit-area":"tinymce__oxide--tox-edit-area","tox-edit-area__iframe":"tinymce__oxide--tox-edit-area__iframe","tox-inline-edit-area":"tinymce__oxide--tox-inline-edit-area","tox-editor-container":"tinymce__oxide--tox-editor-container","tox-tinymce--toolbar-bottom":"tinymce__oxide--tox-tinymce--toolbar-bottom","tox-tinymce--toolbar-sticky-on":"tinymce__oxide--tox-tinymce--toolbar-sticky-on","tox-editor-dock-fadeout":"tinymce__oxide--tox-editor-dock-fadeout","tox-editor-dock-fadein":"tinymce__oxide--tox-editor-dock-fadein","tox-editor-dock-transition":"tinymce__oxide--tox-editor-dock-transition","tox-control-wrap":"tinymce__oxide--tox-control-wrap","tox-control-wrap--status-invalid":"tinymce__oxide--tox-control-wrap--status-invalid","tox-control-wrap__status-icon-invalid":"tinymce__oxide--tox-control-wrap__status-icon-invalid","tox-control-wrap--status-unknown":"tinymce__oxide--tox-control-wrap--status-unknown","tox-control-wrap__status-icon-unknown":"tinymce__oxide--tox-control-wrap__status-icon-unknown","tox-control-wrap--status-valid":"tinymce__oxide--tox-control-wrap--status-valid","tox-control-wrap__status-icon-valid":"tinymce__oxide--tox-control-wrap__status-icon-valid","tox-control-wrap__status-icon-wrap":"tinymce__oxide--tox-control-wrap__status-icon-wrap","tox-textfield":"tinymce__oxide--tox-textfield","tox-autocompleter":"tinymce__oxide--tox-autocompleter","tox-menu":"tinymce__oxide--tox-menu","tox-autocompleter-highlight":"tinymce__oxide--tox-autocompleter-highlight","tox-color-input":"tinymce__oxide--tox-color-input","tox-label":"tinymce__oxide--tox-label","tox-toolbar-label":"tinymce__oxide--tox-toolbar-label","tox-form":"tinymce__oxide--tox-form","tox-form-group--maximize":"tinymce__oxide--tox-form-group--maximize","tox-form__group--error":"tinymce__oxide--tox-form__group--error","tox-form__group--collection":"tinymce__oxide--tox-form__group--collection","tox-form__grid":"tinymce__oxide--tox-form__grid","tox-form__grid--2col":"tinymce__oxide--tox-form__grid--2col","tox-form__grid--3col":"tinymce__oxide--tox-form__grid--3col","tox-form__grid--4col":"tinymce__oxide--tox-form__grid--4col","tox-form__controls-h-stack":"tinymce__oxide--tox-form__controls-h-stack","tox-form__group--inline":"tinymce__oxide--tox-form__group--inline","tox-form__group--stretched":"tinymce__oxide--tox-form__group--stretched","tox-textarea":"tinymce__oxide--tox-textarea","tox-lock":"tinymce__oxide--tox-lock","tox-locked":"tinymce__oxide--tox-locked","tox-lock-icon__unlock":"tinymce__oxide--tox-lock-icon__unlock","tox-lock-icon__lock":"tinymce__oxide--tox-lock-icon__lock","tox-listboxfield":"tinymce__oxide--tox-listboxfield","tox-listbox--select":"tinymce__oxide--tox-listbox--select","tox-toolbar-textfield":"tinymce__oxide--tox-toolbar-textfield","tox-naked-btn":"tinymce__oxide--tox-naked-btn","tox-listbox__select-label":"tinymce__oxide--tox-listbox__select-label","tox-listbox__select-chevron":"tinymce__oxide--tox-listbox__select-chevron","tox-selectfield":"tinymce__oxide--tox-selectfield","tox-fullscreen":"tinymce__oxide--tox-fullscreen","tox-statusbar__resize-handle":"tinymce__oxide--tox-statusbar__resize-handle","tox-shadowhost":"tinymce__oxide--tox-shadowhost","tox-help__more-link":"tinymce__oxide--tox-help__more-link","tox-image-tools":"tinymce__oxide--tox-image-tools","tox-image-tools__toolbar":"tinymce__oxide--tox-image-tools__toolbar","tox-image-tools__image":"tinymce__oxide--tox-image-tools__image","tox-image-tools__image-bg":"tinymce__oxide--tox-image-tools__image-bg","tox-spacer":"tinymce__oxide--tox-spacer","tox-croprect-block":"tinymce__oxide--tox-croprect-block","tox-croprect-handle":"tinymce__oxide--tox-croprect-handle","tox-croprect-handle-move":"tinymce__oxide--tox-croprect-handle-move","tox-croprect-handle-nw":"tinymce__oxide--tox-croprect-handle-nw","tox-croprect-handle-ne":"tinymce__oxide--tox-croprect-handle-ne","tox-croprect-handle-sw":"tinymce__oxide--tox-croprect-handle-sw","tox-croprect-handle-se":"tinymce__oxide--tox-croprect-handle-se","tox-slider":"tinymce__oxide--tox-slider","tox-insert-table-picker":"tinymce__oxide--tox-insert-table-picker","tox-insert-table-picker__selected":"tinymce__oxide--tox-insert-table-picker__selected","tox-insert-table-picker__label":"tinymce__oxide--tox-insert-table-picker__label","tox-menu__label":"tinymce__oxide--tox-menu__label","tox-menubar":"tinymce__oxide--tox-menubar","tox-mbtn":"tinymce__oxide--tox-mbtn","tox-mbtn--active":"tinymce__oxide--tox-mbtn--active","tox-mbtn__select-label":"tinymce__oxide--tox-mbtn__select-label","tox-mbtn__select-chevron":"tinymce__oxide--tox-mbtn__select-chevron","tox-notification":"tinymce__oxide--tox-notification","tox-notification--in":"tinymce__oxide--tox-notification--in","tox-notification--success":"tinymce__oxide--tox-notification--success","tox-notification--error":"tinymce__oxide--tox-notification--error","tox-notification--warn":"tinymce__oxide--tox-notification--warn","tox-notification--warning":"tinymce__oxide--tox-notification--warning","tox-notification--info":"tinymce__oxide--tox-notification--info","tox-notification__body":"tinymce__oxide--tox-notification__body","tox-notification__icon":"tinymce__oxide--tox-notification__icon","tox-notification__dismiss":"tinymce__oxide--tox-notification__dismiss","tox-progress-bar":"tinymce__oxide--tox-progress-bar","tox-pop":"tinymce__oxide--tox-pop","tox-pop--resizing":"tinymce__oxide--tox-pop--resizing","tox-pop__dialog":"tinymce__oxide--tox-pop__dialog","tox-pop--bottom":"tinymce__oxide--tox-pop--bottom","tox-pop--top":"tinymce__oxide--tox-pop--top","tox-pop--left":"tinymce__oxide--tox-pop--left","tox-pop--right":"tinymce__oxide--tox-pop--right","tox-pop--align-left":"tinymce__oxide--tox-pop--align-left","tox-pop--align-right":"tinymce__oxide--tox-pop--align-right","tox-sidebar-wrap":"tinymce__oxide--tox-sidebar-wrap","tox-sidebar":"tinymce__oxide--tox-sidebar","tox-sidebar__slider":"tinymce__oxide--tox-sidebar__slider","tox-sidebar__pane-container":"tinymce__oxide--tox-sidebar__pane-container","tox-sidebar__pane":"tinymce__oxide--tox-sidebar__pane","tox-sidebar--sliding-closed":"tinymce__oxide--tox-sidebar--sliding-closed","tox-sidebar--sliding-open":"tinymce__oxide--tox-sidebar--sliding-open","tox-sidebar--sliding-growing":"tinymce__oxide--tox-sidebar--sliding-growing","tox-sidebar--sliding-shrinking":"tinymce__oxide--tox-sidebar--sliding-shrinking","tox-selector":"tinymce__oxide--tox-selector","tox-platform-touch":"tinymce__oxide--tox-platform-touch","tox-slider__rail":"tinymce__oxide--tox-slider__rail","tox-slider__handle":"tinymce__oxide--tox-slider__handle","tox-source-code":"tinymce__oxide--tox-source-code","tox-spinner":"tinymce__oxide--tox-spinner","tam-bouncing-dots":"tinymce__oxide--tam-bouncing-dots","tox-statusbar":"tinymce__oxide--tox-statusbar","tox-statusbar__text-container":"tinymce__oxide--tox-statusbar__text-container","tox-statusbar__path":"tinymce__oxide--tox-statusbar__path","tox-statusbar__wordcount":"tinymce__oxide--tox-statusbar__wordcount","tox-statusbar__path-item":"tinymce__oxide--tox-statusbar__path-item","tox-statusbar__branding":"tinymce__oxide--tox-statusbar__branding","tox-throbber":"tinymce__oxide--tox-throbber","tox-throbber__busy-spinner":"tinymce__oxide--tox-throbber__busy-spinner","tox-tbtn":"tinymce__oxide--tox-tbtn","tox-tbtn-more":"tinymce__oxide--tox-tbtn-more","tox-tbtn--disabled":"tinymce__oxide--tox-tbtn--disabled","tox-tbtn--enabled":"tinymce__oxide--tox-tbtn--enabled","tox-tbtn--md":"tinymce__oxide--tox-tbtn--md","tox-tbtn--lg":"tinymce__oxide--tox-tbtn--lg","tox-tbtn--return":"tinymce__oxide--tox-tbtn--return","tox-tbtn--labeled":"tinymce__oxide--tox-tbtn--labeled","tox-tbtn__vlabel":"tinymce__oxide--tox-tbtn__vlabel","tox-tbtn--select":"tinymce__oxide--tox-tbtn--select","tox-tbtn__select-label":"tinymce__oxide--tox-tbtn__select-label","tox-tbtn__select-chevron":"tinymce__oxide--tox-tbtn__select-chevron","tox-tbtn--bespoke":"tinymce__oxide--tox-tbtn--bespoke","tox-split-button":"tinymce__oxide--tox-split-button","tox-split-button__chevron":"tinymce__oxide--tox-split-button__chevron","tox-toolbar-overlord":"tinymce__oxide--tox-toolbar-overlord","tox-toolbar__overflow--closed":"tinymce__oxide--tox-toolbar__overflow--closed","tox-toolbar__overflow--growing":"tinymce__oxide--tox-toolbar__overflow--growing","tox-toolbar__overflow--shrinking":"tinymce__oxide--tox-toolbar__overflow--shrinking","tox-toolbar--scrolling":"tinymce__oxide--tox-toolbar--scrolling","tox-toolbar--no-divider":"tinymce__oxide--tox-toolbar--no-divider","tox-tbtn__icon-rtl":"tinymce__oxide--tox-tbtn__icon-rtl","tox-toolbar__group":"tinymce__oxide--tox-toolbar__group","tox-toolbar__group--pull-right":"tinymce__oxide--tox-toolbar__group--pull-right","tox-tooltip":"tinymce__oxide--tox-tooltip","tox-tooltip__body":"tinymce__oxide--tox-tooltip__body","tox-tooltip__arrow":"tinymce__oxide--tox-tooltip__arrow","tox-tooltip--down":"tinymce__oxide--tox-tooltip--down","tox-tooltip--up":"tinymce__oxide--tox-tooltip--up","tox-tooltip--right":"tinymce__oxide--tox-tooltip--right","tox-tooltip--left":"tinymce__oxide--tox-tooltip--left","tox-well":"tinymce__oxide--tox-well","tox-custom-editor":"tinymce__oxide--tox-custom-editor","tox-dialog-loading":"tinymce__oxide--tox-dialog-loading","tox-tab":"tinymce__oxide--tox-tab","tox-dialog__content-js":"tinymce__oxide--tox-dialog__content-js","tox-image-tools-edit-panel":"tinymce__oxide--tox-image-tools-edit-panel","tox-image-tools__sidebar":"tinymce__oxide--tox-image-tools__sidebar"}.template().replace(/tinymce__oxide--/g,"")
const Ut={componentId:"bKkob",template:function(){return'\n\n\n.tinymce__oxide--mce-content-body .tinymce__oxide--mce-item-anchor {\n  background: transparent url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D\'8\'%20height%3D\'12\'%20xmlns%3D\'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg\'%3E%3Cpath%20d%3D\'M0%200L8%200%208%2012%204.09117821%209%200%2012z\'%2F%3E%3C%2Fsvg%3E%0A") no-repeat center;\n  cursor: default;\n  display: inline-block;\n  height: 12px !important;\n  padding: 0 2px;\n  -webkit-user-modify: read-only;\n  -moz-user-modify: read-only;\n  -webkit-user-select: all;\n      user-select: all;\n  width: 8px !important;\n}\n.tinymce__oxide--mce-content-body .tinymce__oxide--mce-item-anchor[data-mce-selected] {\n  outline-offset: 1px;\n}\n.tinymce__oxide--tox-comments-visible .tinymce__oxide--tox-comment {\n  background-color: #fff0b7;\n}\n.tinymce__oxide--tox-comments-visible .tinymce__oxide--tox-comment--active {\n  background-color: #ffe168;\n}\n.tinymce__oxide--tox-checklist > li:not(.tinymce__oxide--tox-checklist--hidden) {\n  list-style: none;\n  margin: 0.25em 0;\n}\n.tinymce__oxide--tox-checklist > li:not(.tinymce__oxide--tox-checklist--hidden)::before {\n  content: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%3E%3Cg%20id%3D%22checklist-unchecked%22%20fill%3D%22none%22%20fill-rule%3D%22evenodd%22%3E%3Crect%20id%3D%22Rectangle%22%20width%3D%2215%22%20height%3D%2215%22%20x%3D%22.5%22%20y%3D%22.5%22%20fill-rule%3D%22nonzero%22%20stroke%3D%22%234C4C4C%22%20rx%3D%222%22%2F%3E%3C%2Fg%3E%3C%2Fsvg%3E%0A");\n  cursor: pointer;\n  height: 1em;\n  margin-left: -1.5em;\n  margin-top: 0.125em;\n  position: absolute;\n  width: 1em;\n}\n.tinymce__oxide--tox-checklist li:not(.tinymce__oxide--tox-checklist--hidden).tinymce__oxide--tox-checklist--checked::before {\n  content: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%3E%3Cg%20id%3D%22checklist-checked%22%20fill%3D%22none%22%20fill-rule%3D%22evenodd%22%3E%3Crect%20id%3D%22Rectangle%22%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%234099FF%22%20fill-rule%3D%22nonzero%22%20rx%3D%222%22%2F%3E%3Cpath%20id%3D%22Path%22%20fill%3D%22%23FFF%22%20fill-rule%3D%22nonzero%22%20d%3D%22M11.5703186%2C3.14417309%20C11.8516238%2C2.73724603%2012.4164781%2C2.62829933%2012.83558%2C2.89774797%20C13.260121%2C3.17069355%2013.3759736%2C3.72932262%2013.0909105%2C4.14168582%20L7.7580587%2C11.8560195%20C7.43776896%2C12.3193404%206.76483983%2C12.3852142%206.35607322%2C11.9948725%20L3.02491697%2C8.8138662%20C2.66090143%2C8.46625845%202.65798871%2C7.89594698%203.01850234%2C7.54483354%20C3.373942%2C7.19866177%203.94940006%2C7.19592841%204.30829608%2C7.5386474%20L6.85276923%2C9.9684299%20L11.5703186%2C3.14417309%20Z%22%2F%3E%3C%2Fg%3E%3C%2Fsvg%3E%0A");\n}\n[dir=rtl] .tinymce__oxide--tox-checklist > li:not(.tinymce__oxide--tox-checklist--hidden)::before {\n  margin-left: 0;\n  margin-right: -1.5em;\n}\n\n\n\ncode[class*="language-"],\npre[class*="language-"] {\n  color: black;\n  background: none;\n  text-shadow: 0 1px white;\n  font-family: Consolas, Monaco, \'Andale Mono\', \'Ubuntu Mono\', monospace;\n  font-size: 1em;\n  text-align: left;\n  white-space: pre;\n  word-spacing: normal;\n  word-break: normal;\n  word-wrap: normal;\n  line-height: 1.5;\n  tab-size: 4;\n  -webkit-hyphens: none;\n  hyphens: none;\n}\n[dir="ltr"] code[class*="language-"],\n[dir="ltr"] pre[class*="language-"] {\n  text-align: left;\n}\n[dir="rtl"] code[class*="language-"],\n[dir="rtl"] pre[class*="language-"] {\n  text-align: left;\n}\npre[class*="language-"]::selection,\npre[class*="language-"] ::selection,\ncode[class*="language-"]::selection,\ncode[class*="language-"] ::selection {\n  text-shadow: none;\n  background: #b3d4fc;\n}\n@media print {\n  code[class*="language-"],\n  pre[class*="language-"] {\n    text-shadow: none;\n  }\n}\n\npre[class*="language-"] {\n  padding: 1em;\n  margin: 0.5em 0;\n  overflow: auto;\n}\n:not(pre) > code[class*="language-"],\npre[class*="language-"] {\n  background: #f5f2f0;\n}\n\n:not(pre) > code[class*="language-"] {\n  padding: 0.1em;\n  border-radius: 0.3em;\n  white-space: normal;\n}\n.tinymce__oxide--token.tinymce__oxide--comment,\n.tinymce__oxide--token.tinymce__oxide--prolog,\n.tinymce__oxide--token.tinymce__oxide--doctype,\n.tinymce__oxide--token.tinymce__oxide--cdata {\n  color: slategray;\n}\n.tinymce__oxide--token.tinymce__oxide--punctuation {\n  color: #999;\n}\n.tinymce__oxide--namespace {\n  opacity: 0.7;\n}\n.tinymce__oxide--token.tinymce__oxide--property,\n.tinymce__oxide--token.tinymce__oxide--tag,\n.tinymce__oxide--token.tinymce__oxide--boolean,\n.tinymce__oxide--token.tinymce__oxide--number,\n.tinymce__oxide--token.tinymce__oxide--constant,\n.tinymce__oxide--token.tinymce__oxide--symbol,\n.tinymce__oxide--token.tinymce__oxide--deleted {\n  color: #905;\n}\n.tinymce__oxide--token.tinymce__oxide--selector,\n.tinymce__oxide--token.tinymce__oxide--attr-name,\n.tinymce__oxide--token.tinymce__oxide--string,\n.tinymce__oxide--token.tinymce__oxide--char,\n.tinymce__oxide--token.tinymce__oxide--builtin,\n.tinymce__oxide--token.tinymce__oxide--inserted {\n  color: #690;\n}\n.tinymce__oxide--token.tinymce__oxide--operator,\n.tinymce__oxide--token.tinymce__oxide--entity,\n.tinymce__oxide--token.tinymce__oxide--url,\n.tinymce__oxide--language-css .tinymce__oxide--token.tinymce__oxide--string,\n.tinymce__oxide--style .tinymce__oxide--token.tinymce__oxide--string {\n  color: #9a6e3a;\n  background: hsla(0, 0%, 100%, 0.5);\n}\n.tinymce__oxide--token.tinymce__oxide--atrule,\n.tinymce__oxide--token.tinymce__oxide--attr-value,\n.tinymce__oxide--token.tinymce__oxide--keyword {\n  color: #07a;\n}\n.tinymce__oxide--token.tinymce__oxide--function,\n.tinymce__oxide--token.tinymce__oxide--class-name {\n  color: #DD4A68;\n}\n.tinymce__oxide--token.tinymce__oxide--regex,\n.tinymce__oxide--token.tinymce__oxide--important,\n.tinymce__oxide--token.tinymce__oxide--variable {\n  color: #e90;\n}\n.tinymce__oxide--token.tinymce__oxide--important,\n.tinymce__oxide--token.tinymce__oxide--bold {\n  font-weight: bold;\n}\n.tinymce__oxide--token.tinymce__oxide--italic {\n  font-style: italic;\n}\n.tinymce__oxide--token.tinymce__oxide--entity {\n  cursor: help;\n}\n\n.tinymce__oxide--mce-content-body {\n  overflow-wrap: break-word;\n  word-wrap: break-word;\n}\n.tinymce__oxide--mce-content-body .tinymce__oxide--mce-visual-caret {\n  background-color: black;\n  background-color: currentColor;\n  position: absolute;\n}\n.tinymce__oxide--mce-content-body .tinymce__oxide--mce-visual-caret-hidden {\n  display: none;\n}\n.tinymce__oxide--mce-content-body *[data-mce-caret] {\n  left: -1000px;\n  margin: 0;\n  padding: 0;\n  position: absolute;\n  right: auto;\n  top: 0;\n}\n.tinymce__oxide--mce-content-body .tinymce__oxide--mce-offscreen-selection {\n  left: -2000000px;\n  max-width: 1000000px;\n  position: absolute;\n}\n.tinymce__oxide--mce-content-body *[contentEditable=false] {\n  cursor: default;\n}\n.tinymce__oxide--mce-content-body *[contentEditable=true] {\n  cursor: text;\n}\n.tinymce__oxide--tox-cursor-format-painter {\n  cursor: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2224%22%20height%3D%2224%22%20viewBox%3D%220%200%2024%2024%22%3E%0A%20%20%3Cg%20fill%3D%22none%22%20fill-rule%3D%22evenodd%22%3E%0A%20%20%20%20%3Cpath%20fill%3D%22%23000%22%20fill-rule%3D%22nonzero%22%20d%3D%22M15%2C6%20C15%2C5.45%2014.55%2C5%2014%2C5%20L6%2C5%20C5.45%2C5%205%2C5.45%205%2C6%20L5%2C10%20C5%2C10.55%205.45%2C11%206%2C11%20L14%2C11%20C14.55%2C11%2015%2C10.55%2015%2C10%20L15%2C9%20L16%2C9%20L16%2C12%20L9%2C12%20L9%2C19%20C9%2C19.55%209.45%2C20%2010%2C20%20L11%2C20%20C11.55%2C20%2012%2C19.55%2012%2C19%20L12%2C14%20L18%2C14%20L18%2C7%20L15%2C7%20L15%2C6%20Z%22%2F%3E%0A%20%20%20%20%3Cpath%20fill%3D%22%23000%22%20fill-rule%3D%22nonzero%22%20d%3D%22M1%2C1%20L8.25%2C1%20C8.66421356%2C1%209%2C1.33578644%209%2C1.75%20L9%2C1.75%20C9%2C2.16421356%208.66421356%2C2.5%208.25%2C2.5%20L2.5%2C2.5%20L2.5%2C8.25%20C2.5%2C8.66421356%202.16421356%2C9%201.75%2C9%20L1.75%2C9%20C1.33578644%2C9%201%2C8.66421356%201%2C8.25%20L1%2C1%20Z%22%2F%3E%0A%20%20%3C%2Fg%3E%0A%3C%2Fsvg%3E%0A"), default;\n}\n.tinymce__oxide--mce-content-body figure.tinymce__oxide--align-left {\n  float: left;\n}\n[dir="ltr"] .tinymce__oxide--mce-content-body figure.tinymce__oxide--align-left {\n  float: left;\n}\n[dir="rtl"] .tinymce__oxide--mce-content-body figure.tinymce__oxide--align-left {\n  float: left;\n}\n.tinymce__oxide--mce-content-body figure.tinymce__oxide--align-right {\n  float: right;\n}\n[dir="ltr"] .tinymce__oxide--mce-content-body figure.tinymce__oxide--align-right {\n  float: right;\n}\n[dir="rtl"] .tinymce__oxide--mce-content-body figure.tinymce__oxide--align-right {\n  float: right;\n}\n.tinymce__oxide--mce-content-body figure.tinymce__oxide--image.tinymce__oxide--align-center {\n  display: table;\n  margin-left: auto;\n  margin-right: auto;\n}\n.tinymce__oxide--mce-preview-object {\n  border: 1px solid gray;\n  display: inline-block;\n  line-height: 0;\n  margin: 0 2px 0 2px;\n  position: relative;\n}\n.tinymce__oxide--mce-preview-object .tinymce__oxide--mce-shim {\n  background: url(data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7);\n  height: 100%;\n  left: 0;\n  position: absolute;\n  top: 0;\n  width: 100%;\n}\n.tinymce__oxide--mce-preview-object[data-mce-selected="2"] .tinymce__oxide--mce-shim {\n  display: none;\n}\n.tinymce__oxide--mce-object {\n  background: transparent url("data:image/svg+xml;charset=UTF-8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2224%22%20height%3D%2224%22%3E%3Cpath%20d%3D%22M4%203h16a1%201%200%200%201%201%201v16a1%201%200%200%201-1%201H4a1%201%200%200%201-1-1V4a1%201%200%200%201%201-1zm1%202v14h14V5H5zm4.79%202.565l5.64%204.028a.5.5%200%200%201%200%20.814l-5.64%204.028a.5.5%200%200%201-.79-.407V7.972a.5.5%200%200%201%20.79-.407z%22%2F%3E%3C%2Fsvg%3E%0A") no-repeat center;\n  border: 1px dashed #aaa;\n}\n.tinymce__oxide--mce-pagebreak {\n  border: 1px dashed #aaa;\n  cursor: default;\n  display: block;\n  height: 5px;\n  margin-top: 15px;\n  page-break-before: always;\n  width: 100%;\n}\n@media print {\n  .tinymce__oxide--mce-pagebreak {\n    border: 0;\n  }\n}\n.tinymce__oxide--tiny-pageembed .tinymce__oxide--mce-shim {\n  background: url(data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7);\n  height: 100%;\n  left: 0;\n  position: absolute;\n  top: 0;\n  width: 100%;\n}\n.tinymce__oxide--tiny-pageembed[data-mce-selected="2"] .tinymce__oxide--mce-shim {\n  display: none;\n}\n.tinymce__oxide--tiny-pageembed {\n  display: inline-block;\n  position: relative;\n}\n.tinymce__oxide--tiny-pageembed--21by9,\n.tinymce__oxide--tiny-pageembed--16by9,\n.tinymce__oxide--tiny-pageembed--4by3,\n.tinymce__oxide--tiny-pageembed--1by1 {\n  display: block;\n  overflow: hidden;\n  padding: 0;\n  position: relative;\n  width: 100%;\n}\n.tinymce__oxide--tiny-pageembed--21by9 {\n  padding-top: 42.857143%;\n}\n.tinymce__oxide--tiny-pageembed--16by9 {\n  padding-top: 56.25%;\n}\n.tinymce__oxide--tiny-pageembed--4by3 {\n  padding-top: 75%;\n}\n.tinymce__oxide--tiny-pageembed--1by1 {\n  padding-top: 100%;\n}\n.tinymce__oxide--tiny-pageembed--21by9 iframe,\n.tinymce__oxide--tiny-pageembed--16by9 iframe,\n.tinymce__oxide--tiny-pageembed--4by3 iframe,\n.tinymce__oxide--tiny-pageembed--1by1 iframe {\n  border: 0;\n  height: 100%;\n  left: 0;\n  position: absolute;\n  top: 0;\n  width: 100%;\n}\n.tinymce__oxide--mce-content-body[data-mce-placeholder] {\n  position: relative;\n}\n.tinymce__oxide--mce-content-body[data-mce-placeholder]:not(.tinymce__oxide--mce-visualblocks)::before {\n  color: rgba(34, 47, 62, 0.7);\n  content: attr(data-mce-placeholder);\n  position: absolute;\n}\n.tinymce__oxide--mce-content-body:not([dir=rtl])[data-mce-placeholder]:not(.tinymce__oxide--mce-visualblocks)::before {\n  left: 1px;\n}\n.tinymce__oxide--mce-content-body[dir=rtl][data-mce-placeholder]:not(.tinymce__oxide--mce-visualblocks)::before {\n  right: 1px;\n}\n.tinymce__oxide--mce-content-body div.tinymce__oxide--mce-resizehandle {\n  background-color: #4099ff;\n  border-color: #4099ff;\n  border-style: solid;\n  border-width: 1px;\n  box-sizing: border-box;\n  height: 10px;\n  position: absolute;\n  width: 10px;\n  z-index: 10000;\n}\n.tinymce__oxide--mce-content-body div.tinymce__oxide--mce-resizehandle:hover {\n  background-color: #4099ff;\n}\n.tinymce__oxide--mce-content-body div.tinymce__oxide--mce-resizehandle:nth-of-type(1) {\n  cursor: nwse-resize;\n}\n.tinymce__oxide--mce-content-body div.tinymce__oxide--mce-resizehandle:nth-of-type(2) {\n  cursor: nesw-resize;\n}\n.tinymce__oxide--mce-content-body div.tinymce__oxide--mce-resizehandle:nth-of-type(3) {\n  cursor: nwse-resize;\n}\n.tinymce__oxide--mce-content-body div.tinymce__oxide--mce-resizehandle:nth-of-type(4) {\n  cursor: nesw-resize;\n}\n.tinymce__oxide--mce-content-body .tinymce__oxide--mce-resize-backdrop {\n  z-index: 10000;\n}\n.tinymce__oxide--mce-content-body .tinymce__oxide--mce-clonedresizable {\n  cursor: default;\n  opacity: 0.5;\n  outline: 1px dashed black;\n  position: absolute;\n  z-index: 10001;\n}\n.tinymce__oxide--mce-content-body .tinymce__oxide--mce-clonedresizable.tinymce__oxide--mce-resizetable-columns th,\n.tinymce__oxide--mce-content-body .tinymce__oxide--mce-clonedresizable.tinymce__oxide--mce-resizetable-columns td {\n  border: 0;\n}\n.tinymce__oxide--mce-content-body .tinymce__oxide--mce-resize-helper {\n  background: #555;\n  background: rgba(0, 0, 0, 0.75);\n  border: 1px;\n  border-radius: 3px;\n  color: white;\n  display: none;\n  font-family: sans-serif;\n  font-size: 12px;\n  line-height: 14px;\n  margin: 5px 10px;\n  padding: 5px;\n  position: absolute;\n  white-space: nowrap;\n  z-index: 10002;\n}\n.tinymce__oxide--tox-rtc-user-selection {\n  position: relative;\n}\n.tinymce__oxide--tox-rtc-user-cursor {\n  bottom: 0;\n  cursor: default;\n  position: absolute;\n  top: 0;\n  width: 2px;\n}\n.tinymce__oxide--tox-rtc-user-cursor::before {\n  background-color: inherit;\n  border-radius: 50%;\n  content: \'\';\n  display: block;\n  height: 8px;\n  position: absolute;\n  right: -3px;\n  top: -3px;\n  width: 8px;\n}\n.tinymce__oxide--tox-rtc-user-cursor:hover::after {\n  background-color: inherit;\n  border-radius: 100px;\n  box-sizing: border-box;\n  color: #fff;\n  content: attr(data-user);\n  display: block;\n  font-size: 12px;\n  font-weight: bold;\n  left: -5px;\n  min-height: 8px;\n  min-width: 8px;\n  padding: 0 12px;\n  position: absolute;\n  top: -11px;\n  white-space: nowrap;\n  z-index: 1000;\n}\n.tinymce__oxide--tox-rtc-user-selection--1 .tinymce__oxide--tox-rtc-user-cursor {\n  background-color: #2dc26b;\n}\n.tinymce__oxide--tox-rtc-user-selection--2 .tinymce__oxide--tox-rtc-user-cursor {\n  background-color: #e03e2d;\n}\n.tinymce__oxide--tox-rtc-user-selection--3 .tinymce__oxide--tox-rtc-user-cursor {\n  background-color: #f1c40f;\n}\n.tinymce__oxide--tox-rtc-user-selection--4 .tinymce__oxide--tox-rtc-user-cursor {\n  background-color: #3598db;\n}\n.tinymce__oxide--tox-rtc-user-selection--5 .tinymce__oxide--tox-rtc-user-cursor {\n  background-color: #b96ad9;\n}\n.tinymce__oxide--tox-rtc-user-selection--6 .tinymce__oxide--tox-rtc-user-cursor {\n  background-color: #e67e23;\n}\n.tinymce__oxide--tox-rtc-user-selection--7 .tinymce__oxide--tox-rtc-user-cursor {\n  background-color: #aaa69d;\n}\n.tinymce__oxide--tox-rtc-user-selection--8 .tinymce__oxide--tox-rtc-user-cursor {\n  background-color: #f368e0;\n}\n.tinymce__oxide--tox-rtc-remote-image {\n  background: #eaeaea url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2236%22%20height%3D%2212%22%20viewBox%3D%220%200%2036%2012%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%20%20%3Ccircle%20cx%3D%226%22%20cy%3D%226%22%20r%3D%223%22%20fill%3D%22rgba(0%2C%200%2C%200%2C%20.2)%22%3E%0A%20%20%20%20%3Canimate%20attributeName%3D%22r%22%20values%3D%223%3B5%3B3%22%20calcMode%3D%22linear%22%20dur%3D%221s%22%20repeatCount%3D%22indefinite%22%20%2F%3E%0A%20%20%3C%2Fcircle%3E%0A%20%20%3Ccircle%20cx%3D%2218%22%20cy%3D%226%22%20r%3D%223%22%20fill%3D%22rgba(0%2C%200%2C%200%2C%20.2)%22%3E%0A%20%20%20%20%3Canimate%20attributeName%3D%22r%22%20values%3D%223%3B5%3B3%22%20calcMode%3D%22linear%22%20begin%3D%22.33s%22%20dur%3D%221s%22%20repeatCount%3D%22indefinite%22%20%2F%3E%0A%20%20%3C%2Fcircle%3E%0A%20%20%3Ccircle%20cx%3D%2230%22%20cy%3D%226%22%20r%3D%223%22%20fill%3D%22rgba(0%2C%200%2C%200%2C%20.2)%22%3E%0A%20%20%20%20%3Canimate%20attributeName%3D%22r%22%20values%3D%223%3B5%3B3%22%20calcMode%3D%22linear%22%20begin%3D%22.66s%22%20dur%3D%221s%22%20repeatCount%3D%22indefinite%22%20%2F%3E%0A%20%20%3C%2Fcircle%3E%0A%3C%2Fsvg%3E%0A") no-repeat center center;\n  border: 1px solid #ccc;\n  min-height: 240px;\n  min-width: 320px;\n}\n.tinymce__oxide--mce-match-marker {\n  background: #aaa;\n  color: #fff;\n}\n.tinymce__oxide--mce-match-marker-selected {\n  background: #39f;\n  color: #fff;\n}\n.tinymce__oxide--mce-match-marker-selected::selection {\n  background: #39f;\n  color: #fff;\n}\n.tinymce__oxide--mce-content-body img[data-mce-selected],\n.tinymce__oxide--mce-content-body video[data-mce-selected],\n.tinymce__oxide--mce-content-body audio[data-mce-selected],\n.tinymce__oxide--mce-content-body object[data-mce-selected],\n.tinymce__oxide--mce-content-body embed[data-mce-selected],\n.tinymce__oxide--mce-content-body table[data-mce-selected] {\n  outline: 3px solid #b4d7ff;\n}\n.tinymce__oxide--mce-content-body hr[data-mce-selected] {\n  outline: 3px solid #b4d7ff;\n  outline-offset: 1px;\n}\n.tinymce__oxide--mce-content-body *[contentEditable=false] *[contentEditable=true]:focus {\n  outline: 3px solid #b4d7ff;\n}\n.tinymce__oxide--mce-content-body *[contentEditable=false] *[contentEditable=true]:hover {\n  outline: 3px solid #b4d7ff;\n}\n.tinymce__oxide--mce-content-body *[contentEditable=false][data-mce-selected] {\n  cursor: not-allowed;\n  outline: 3px solid #b4d7ff;\n}\n.tinymce__oxide--mce-content-body.tinymce__oxide--mce-content-readonly *[contentEditable=true]:focus,\n.tinymce__oxide--mce-content-body.tinymce__oxide--mce-content-readonly *[contentEditable=true]:hover {\n  outline: none;\n}\n.tinymce__oxide--mce-content-body *[data-mce-selected="inline-boundary"] {\n  background-color: #b4d7ff;\n}\n.tinymce__oxide--mce-content-body .tinymce__oxide--mce-edit-focus {\n  outline: 3px solid #b4d7ff;\n}\n.tinymce__oxide--mce-content-body td[data-mce-selected],\n.tinymce__oxide--mce-content-body th[data-mce-selected] {\n  position: relative;\n}\n.tinymce__oxide--mce-content-body td[data-mce-selected]::selection,\n.tinymce__oxide--mce-content-body th[data-mce-selected]::selection {\n  background: none;\n}\n.tinymce__oxide--mce-content-body td[data-mce-selected] *,\n.tinymce__oxide--mce-content-body th[data-mce-selected] * {\n  outline: none;\n  -webkit-touch-callout: none;\n  -webkit-user-select: none;\n          user-select: none;\n}\n.tinymce__oxide--mce-content-body td[data-mce-selected]::after,\n.tinymce__oxide--mce-content-body th[data-mce-selected]::after {\n  background-color: rgba(180, 215, 255, 0.7);\n  border: 1px solid rgba(180, 215, 255, 0.7);\n  bottom: -1px;\n  content: \'\';\n  left: -1px;\n  mix-blend-mode: multiply;\n  position: absolute;\n  right: -1px;\n  top: -1px;\n}\n@media screen and (-ms-high-contrast: active), (-ms-high-contrast: none) {\n  .tinymce__oxide--mce-content-body td[data-mce-selected]::after,\n  .tinymce__oxide--mce-content-body th[data-mce-selected]::after {\n    border-color: rgba(0, 84, 180, 0.7);\n  }\n}\n.tinymce__oxide--mce-content-body img::selection {\n  background: none;\n}\n.tinymce__oxide--ephox-snooker-resizer-bar {\n  background-color: #b4d7ff;\n  opacity: 0;\n  -webkit-user-select: none;\n  user-select: none;\n}\n.tinymce__oxide--ephox-snooker-resizer-cols {\n  cursor: col-resize;\n}\n.tinymce__oxide--ephox-snooker-resizer-rows {\n  cursor: row-resize;\n}\n.tinymce__oxide--ephox-snooker-resizer-bar.tinymce__oxide--ephox-snooker-resizer-bar-dragging {\n  opacity: 1;\n}\n.tinymce__oxide--mce-spellchecker-word {\n  background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D\'4\'%20height%3D\'4\'%20xmlns%3D\'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg\'%3E%3Cpath%20stroke%3D\'%23ff0000\'%20fill%3D\'none\'%20stroke-linecap%3D\'round\'%20stroke-opacity%3D\'.75\'%20d%3D\'M0%203L2%201%204%203\'%2F%3E%3C%2Fsvg%3E%0A");\n  background-position: 0 calc(100% + 1px);\n  background-repeat: repeat-x;\n  background-size: auto 6px;\n  cursor: default;\n  height: 2rem;\n}\n.tinymce__oxide--mce-spellchecker-grammar {\n  background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D\'4\'%20height%3D\'4\'%20xmlns%3D\'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg\'%3E%3Cpath%20stroke%3D\'%2300A835\'%20fill%3D\'none\'%20stroke-linecap%3D\'round\'%20d%3D\'M0%203L2%201%204%203\'%2F%3E%3C%2Fsvg%3E%0A");\n  background-position: 0 calc(100% + 1px);\n  background-repeat: repeat-x;\n  background-size: auto 6px;\n  cursor: default;\n}\n.tinymce__oxide--mce-toc {\n  border: 1px solid gray;\n}\n.tinymce__oxide--mce-toc h2 {\n  margin: 4px;\n}\n.tinymce__oxide--mce-toc li {\n  list-style-type: none;\n}\ntable[style*="border-width: 0px"],\n.tinymce__oxide--mce-item-table:not([border]),\n.tinymce__oxide--mce-item-table[border="0"],\ntable[style*="border-width: 0px"] td,\n.tinymce__oxide--mce-item-table:not([border]) td,\n.tinymce__oxide--mce-item-table[border="0"] td,\ntable[style*="border-width: 0px"] th,\n.tinymce__oxide--mce-item-table:not([border]) th,\n.tinymce__oxide--mce-item-table[border="0"] th,\ntable[style*="border-width: 0px"] caption,\n.tinymce__oxide--mce-item-table:not([border]) caption,\n.tinymce__oxide--mce-item-table[border="0"] caption {\n  border: 1px dashed #bbb;\n}\n.tinymce__oxide--mce-visualblocks p,\n.tinymce__oxide--mce-visualblocks h1,\n.tinymce__oxide--mce-visualblocks h2,\n.tinymce__oxide--mce-visualblocks h3,\n.tinymce__oxide--mce-visualblocks h4,\n.tinymce__oxide--mce-visualblocks h5,\n.tinymce__oxide--mce-visualblocks h6,\n.tinymce__oxide--mce-visualblocks div:not([data-mce-bogus]),\n.tinymce__oxide--mce-visualblocks section,\n.tinymce__oxide--mce-visualblocks article,\n.tinymce__oxide--mce-visualblocks blockquote,\n.tinymce__oxide--mce-visualblocks address,\n.tinymce__oxide--mce-visualblocks pre,\n.tinymce__oxide--mce-visualblocks figure,\n.tinymce__oxide--mce-visualblocks figcaption,\n.tinymce__oxide--mce-visualblocks hgroup,\n.tinymce__oxide--mce-visualblocks aside,\n.tinymce__oxide--mce-visualblocks ul,\n.tinymce__oxide--mce-visualblocks ol,\n.tinymce__oxide--mce-visualblocks dl {\n  background-repeat: no-repeat;\n  border: 1px dashed #bbb;\n  margin-left: 3px;\n  padding-top: 10px;\n}\n.tinymce__oxide--mce-visualblocks p {\n  background-image: url(data:image/gif;base64,R0lGODlhCQAJAJEAAAAAAP///7u7u////yH5BAEAAAMALAAAAAAJAAkAAAIQnG+CqCN/mlyvsRUpThG6AgA7);\n}\n.tinymce__oxide--mce-visualblocks h1 {\n  background-image: url(data:image/gif;base64,R0lGODlhDQAKAIABALu7u////yH5BAEAAAEALAAAAAANAAoAAAIXjI8GybGu1JuxHoAfRNRW3TWXyF2YiRUAOw==);\n}\n.tinymce__oxide--mce-visualblocks h2 {\n  background-image: url(data:image/gif;base64,R0lGODlhDgAKAIABALu7u////yH5BAEAAAEALAAAAAAOAAoAAAIajI8Hybbx4oOuqgTynJd6bGlWg3DkJzoaUAAAOw==);\n}\n.tinymce__oxide--mce-visualblocks h3 {\n  background-image: url(data:image/gif;base64,R0lGODlhDgAKAIABALu7u////yH5BAEAAAEALAAAAAAOAAoAAAIZjI8Hybbx4oOuqgTynJf2Ln2NOHpQpmhAAQA7);\n}\n.tinymce__oxide--mce-visualblocks h4 {\n  background-image: url(data:image/gif;base64,R0lGODlhDgAKAIABALu7u////yH5BAEAAAEALAAAAAAOAAoAAAIajI8HybbxInR0zqeAdhtJlXwV1oCll2HaWgAAOw==);\n}\n.tinymce__oxide--mce-visualblocks h5 {\n  background-image: url(data:image/gif;base64,R0lGODlhDgAKAIABALu7u////yH5BAEAAAEALAAAAAAOAAoAAAIajI8HybbxIoiuwjane4iq5GlW05GgIkIZUAAAOw==);\n}\n.tinymce__oxide--mce-visualblocks h6 {\n  background-image: url(data:image/gif;base64,R0lGODlhDgAKAIABALu7u////yH5BAEAAAEALAAAAAAOAAoAAAIajI8HybbxIoiuwjan04jep1iZ1XRlAo5bVgAAOw==);\n}\n.tinymce__oxide--mce-visualblocks div:not([data-mce-bogus]) {\n  background-image: url(data:image/gif;base64,R0lGODlhEgAKAIABALu7u////yH5BAEAAAEALAAAAAASAAoAAAIfjI9poI0cgDywrhuxfbrzDEbQM2Ei5aRjmoySW4pAAQA7);\n}\n.tinymce__oxide--mce-visualblocks section {\n  background-image: url(data:image/gif;base64,R0lGODlhKAAKAIABALu7u////yH5BAEAAAEALAAAAAAoAAoAAAI5jI+pywcNY3sBWHdNrplytD2ellDeSVbp+GmWqaDqDMepc8t17Y4vBsK5hDyJMcI6KkuYU+jpjLoKADs=);\n}\n.tinymce__oxide--mce-visualblocks article {\n  background-image: url(data:image/gif;base64,R0lGODlhKgAKAIABALu7u////yH5BAEAAAEALAAAAAAqAAoAAAI6jI+pywkNY3wG0GBvrsd2tXGYSGnfiF7ikpXemTpOiJScasYoDJJrjsG9gkCJ0ag6KhmaIe3pjDYBBQA7);\n}\n.tinymce__oxide--mce-visualblocks blockquote {\n  background-image: url(data:image/gif;base64,R0lGODlhPgAKAIABALu7u////yH5BAEAAAEALAAAAAA+AAoAAAJPjI+py+0Knpz0xQDyuUhvfoGgIX5iSKZYgq5uNL5q69asZ8s5rrf0yZmpNkJZzFesBTu8TOlDVAabUyatguVhWduud3EyiUk45xhTTgMBBQA7);\n}\n.tinymce__oxide--mce-visualblocks address {\n  background-image: url(data:image/gif;base64,R0lGODlhLQAKAIABALu7u////yH5BAEAAAEALAAAAAAtAAoAAAI/jI+pywwNozSP1gDyyZcjb3UaRpXkWaXmZW4OqKLhBmLs+K263DkJK7OJeifh7FicKD9A1/IpGdKkyFpNmCkAADs=);\n}\n.tinymce__oxide--mce-visualblocks pre {\n  background-image: url(data:image/gif;base64,R0lGODlhFQAKAIABALu7uwAAACH5BAEAAAEALAAAAAAVAAoAAAIjjI+ZoN0cgDwSmnpz1NCueYERhnibZVKLNnbOq8IvKpJtVQAAOw==);\n}\n.tinymce__oxide--mce-visualblocks figure {\n  background-image: url(data:image/gif;base64,R0lGODlhJAAKAIAAALu7u////yH5BAEAAAEALAAAAAAkAAoAAAI0jI+py+2fwAHUSFvD3RlvG4HIp4nX5JFSpnZUJ6LlrM52OE7uSWosBHScgkSZj7dDKnWAAgA7);\n}\n.tinymce__oxide--mce-visualblocks figcaption {\n  border: 1px dashed #bbb;\n}\n.tinymce__oxide--mce-visualblocks hgroup {\n  background-image: url(data:image/gif;base64,R0lGODlhJwAKAIABALu7uwAAACH5BAEAAAEALAAAAAAnAAoAAAI3jI+pywYNI3uB0gpsRtt5fFnfNZaVSYJil4Wo03Hv6Z62uOCgiXH1kZIIJ8NiIxRrAZNMZAtQAAA7);\n}\n.tinymce__oxide--mce-visualblocks aside {\n  background-image: url(data:image/gif;base64,R0lGODlhHgAKAIABAKqqqv///yH5BAEAAAEALAAAAAAeAAoAAAItjI+pG8APjZOTzgtqy7I3f1yehmQcFY4WKZbqByutmW4aHUd6vfcVbgudgpYCADs=);\n}\n.tinymce__oxide--mce-visualblocks ul {\n  background-image: url(data:image/gif;base64,R0lGODlhDQAKAIAAALu7u////yH5BAEAAAEALAAAAAANAAoAAAIXjI8GybGuYnqUVSjvw26DzzXiqIDlVwAAOw==);\n}\n.tinymce__oxide--mce-visualblocks ol {\n  background-image: url(data:image/gif;base64,R0lGODlhDQAKAIABALu7u////yH5BAEAAAEALAAAAAANAAoAAAIXjI8GybH6HHt0qourxC6CvzXieHyeWQAAOw==);\n}\n.tinymce__oxide--mce-visualblocks dl {\n  background-image: url(data:image/gif;base64,R0lGODlhDQAKAIABALu7u////yH5BAEAAAEALAAAAAANAAoAAAIXjI8GybEOnmOvUoWznTqeuEjNSCqeGRUAOw==);\n}\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) p,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) h1,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) h2,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) h3,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) h4,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) h5,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) h6,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) div:not([data-mce-bogus]),\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) section,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) article,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) blockquote,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) address,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) pre,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) figure,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) figcaption,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) hgroup,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) aside,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) ul,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) ol,\n.tinymce__oxide--mce-visualblocks:not([dir=rtl]) dl {\n  margin-left: 3px;\n}\n.tinymce__oxide--mce-visualblocks[dir=rtl] p,\n.tinymce__oxide--mce-visualblocks[dir=rtl] h1,\n.tinymce__oxide--mce-visualblocks[dir=rtl] h2,\n.tinymce__oxide--mce-visualblocks[dir=rtl] h3,\n.tinymce__oxide--mce-visualblocks[dir=rtl] h4,\n.tinymce__oxide--mce-visualblocks[dir=rtl] h5,\n.tinymce__oxide--mce-visualblocks[dir=rtl] h6,\n.tinymce__oxide--mce-visualblocks[dir=rtl] div:not([data-mce-bogus]),\n.tinymce__oxide--mce-visualblocks[dir=rtl] section,\n.tinymce__oxide--mce-visualblocks[dir=rtl] article,\n.tinymce__oxide--mce-visualblocks[dir=rtl] blockquote,\n.tinymce__oxide--mce-visualblocks[dir=rtl] address,\n.tinymce__oxide--mce-visualblocks[dir=rtl] pre,\n.tinymce__oxide--mce-visualblocks[dir=rtl] figure,\n.tinymce__oxide--mce-visualblocks[dir=rtl] figcaption,\n.tinymce__oxide--mce-visualblocks[dir=rtl] hgroup,\n.tinymce__oxide--mce-visualblocks[dir=rtl] aside,\n.tinymce__oxide--mce-visualblocks[dir=rtl] ul,\n.tinymce__oxide--mce-visualblocks[dir=rtl] ol,\n.tinymce__oxide--mce-visualblocks[dir=rtl] dl {\n  background-position-x: right;\n  margin-right: 3px;\n}\n.tinymce__oxide--mce-nbsp,\n.tinymce__oxide--mce-shy {\n  background: #aaa;\n}\n.tinymce__oxide--mce-shy::after {\n  content: \'-\';\n}\nbody {\n  font-family: sans-serif;\n}\ntable {\n  border-collapse: collapse;\n}\n'},"mce-content-body":"tinymce__oxide--mce-content-body","mce-item-anchor":"tinymce__oxide--mce-item-anchor","tox-comments-visible":"tinymce__oxide--tox-comments-visible","tox-comment":"tinymce__oxide--tox-comment","tox-comment--active":"tinymce__oxide--tox-comment--active","tox-checklist":"tinymce__oxide--tox-checklist","tox-checklist--hidden":"tinymce__oxide--tox-checklist--hidden","tox-checklist--checked":"tinymce__oxide--tox-checklist--checked",token:"tinymce__oxide--token",comment:"tinymce__oxide--comment",prolog:"tinymce__oxide--prolog",doctype:"tinymce__oxide--doctype",cdata:"tinymce__oxide--cdata",punctuation:"tinymce__oxide--punctuation",namespace:"tinymce__oxide--namespace",property:"tinymce__oxide--property",tag:"tinymce__oxide--tag",boolean:"tinymce__oxide--boolean",number:"tinymce__oxide--number",constant:"tinymce__oxide--constant",symbol:"tinymce__oxide--symbol",deleted:"tinymce__oxide--deleted",selector:"tinymce__oxide--selector","attr-name":"tinymce__oxide--attr-name",string:"tinymce__oxide--string",char:"tinymce__oxide--char",builtin:"tinymce__oxide--builtin",inserted:"tinymce__oxide--inserted",operator:"tinymce__oxide--operator",entity:"tinymce__oxide--entity",url:"tinymce__oxide--url","language-css":"tinymce__oxide--language-css",style:"tinymce__oxide--style",atrule:"tinymce__oxide--atrule","attr-value":"tinymce__oxide--attr-value",keyword:"tinymce__oxide--keyword",function:"tinymce__oxide--function","class-name":"tinymce__oxide--class-name",regex:"tinymce__oxide--regex",important:"tinymce__oxide--important",variable:"tinymce__oxide--variable",bold:"tinymce__oxide--bold",italic:"tinymce__oxide--italic","mce-visual-caret":"tinymce__oxide--mce-visual-caret","mce-visual-caret-hidden":"tinymce__oxide--mce-visual-caret-hidden","mce-offscreen-selection":"tinymce__oxide--mce-offscreen-selection","tox-cursor-format-painter":"tinymce__oxide--tox-cursor-format-painter","align-left":"tinymce__oxide--align-left","align-right":"tinymce__oxide--align-right",image:"tinymce__oxide--image","align-center":"tinymce__oxide--align-center","mce-preview-object":"tinymce__oxide--mce-preview-object","mce-shim":"tinymce__oxide--mce-shim","mce-object":"tinymce__oxide--mce-object","mce-pagebreak":"tinymce__oxide--mce-pagebreak","tiny-pageembed":"tinymce__oxide--tiny-pageembed","tiny-pageembed--21by9":"tinymce__oxide--tiny-pageembed--21by9","tiny-pageembed--16by9":"tinymce__oxide--tiny-pageembed--16by9","tiny-pageembed--4by3":"tinymce__oxide--tiny-pageembed--4by3","tiny-pageembed--1by1":"tinymce__oxide--tiny-pageembed--1by1","mce-visualblocks":"tinymce__oxide--mce-visualblocks","mce-resizehandle":"tinymce__oxide--mce-resizehandle","mce-resize-backdrop":"tinymce__oxide--mce-resize-backdrop","mce-clonedresizable":"tinymce__oxide--mce-clonedresizable","mce-resizetable-columns":"tinymce__oxide--mce-resizetable-columns","mce-resize-helper":"tinymce__oxide--mce-resize-helper","tox-rtc-user-selection":"tinymce__oxide--tox-rtc-user-selection","tox-rtc-user-cursor":"tinymce__oxide--tox-rtc-user-cursor","tox-rtc-user-selection--1":"tinymce__oxide--tox-rtc-user-selection--1","tox-rtc-user-selection--2":"tinymce__oxide--tox-rtc-user-selection--2","tox-rtc-user-selection--3":"tinymce__oxide--tox-rtc-user-selection--3","tox-rtc-user-selection--4":"tinymce__oxide--tox-rtc-user-selection--4","tox-rtc-user-selection--5":"tinymce__oxide--tox-rtc-user-selection--5","tox-rtc-user-selection--6":"tinymce__oxide--tox-rtc-user-selection--6","tox-rtc-user-selection--7":"tinymce__oxide--tox-rtc-user-selection--7","tox-rtc-user-selection--8":"tinymce__oxide--tox-rtc-user-selection--8","tox-rtc-remote-image":"tinymce__oxide--tox-rtc-remote-image","mce-match-marker":"tinymce__oxide--mce-match-marker","mce-match-marker-selected":"tinymce__oxide--mce-match-marker-selected","mce-content-readonly":"tinymce__oxide--mce-content-readonly","mce-edit-focus":"tinymce__oxide--mce-edit-focus","ephox-snooker-resizer-bar":"tinymce__oxide--ephox-snooker-resizer-bar","ephox-snooker-resizer-cols":"tinymce__oxide--ephox-snooker-resizer-cols","ephox-snooker-resizer-rows":"tinymce__oxide--ephox-snooker-resizer-rows","ephox-snooker-resizer-bar-dragging":"tinymce__oxide--ephox-snooker-resizer-bar-dragging","mce-spellchecker-word":"tinymce__oxide--mce-spellchecker-word","mce-spellchecker-grammar":"tinymce__oxide--mce-spellchecker-grammar","mce-toc":"tinymce__oxide--mce-toc","mce-item-table":"tinymce__oxide--mce-item-table","mce-nbsp":"tinymce__oxide--mce-nbsp","mce-shy":"tinymce__oxide--mce-shy"}.template().replace(/tinymce__oxide--/g,"")
function $t(e){e.ui.registry.addIcon("more-drawer",'\n    <svg viewBox="0 0 1920 1920">\n      <path d="M1129.412 1637.647c0 93.448-75.964 169.412-169.412 169.412-93.448 0-169.412-75.964-169.412-169.412 0-93.447 75.964-169.412 169.412-169.412 93.448 0 169.412 75.965 169.412 169.412zm0-677.647c0 93.448-75.964 169.412-169.412 169.412-93.448 0-169.412-75.964-169.412-169.412 0-93.448 75.964-169.412 169.412-169.412 93.448 0 169.412 75.964 169.412 169.412zm0-677.647c0 93.447-75.964 169.412-169.412 169.412-93.448 0-169.412-75.965-169.412-169.412 0-93.448 75.964-169.412 169.412-169.412 93.448 0 169.412 75.964 169.412 169.412z" stroke="none" stroke-width="1" fill-rule="evenodd"/>\n    </svg>\n  ')}let Ht=false
function Wt(){if(Ht)return
Ht=true
const e=document.createElement("style")
e.setAttribute("data-skin","tiny oxide skin")
e.appendChild(document.createTextNode(Nt))
const t=document.head.querySelector("style[data-glamor]")||document.head.querySelector("style")||document.head.firstElementChild
document.head.insertBefore(e,t)}const qt=new WeakMap
function Vt(e){const t=e.querySelector(".tox-tbtn")
t&&t.focus()}function Gt(e){const t=e.querySelector(".tox-mbtn")
t&&t.focus()}function Kt(e){let t=e
while(t){if("TABLE"===t.tagName||"TD"===t.tagName||"TH"===t.tagName)return true
t=t.parentElement}return false}function Zt(){let e
try{e=window.localStorage
e.setItem("__storage_test__","__storage_test__")
e.removeItem("__storage_test__")
return true}catch(t){return t instanceof DOMException&&(22===t.code||1014===t.code||"QuotaExceededError"===t.name||"NS_ERROR_DOM_QUOTA_REACHED"===t.name)&&e&&0!==e.length}}function Yt(){const e=q("rce.htmleditor")
return e===it||e===ot?e:ot}function Jt(){return Object(V["a"])("Loading")}const Xt=void 0===document.fullscreenElement?"webkitFullscreenElement":"fullscreenElement"
const Qt=document.body.requestFullscreen?"requestFullscreen":"webkitRequestFullscreen"
const en=document.exitFullscreen?"exitFullscreen":"webkitExitFullscreen"
let tn=0
let nn=(At=Object(B["e"])(ft,Pt),At(St=(It=jt=class e extends s.a.Component{static getByEditor(e){return qt.get(e)}constructor(t){var o
super(t)
this.onRemove=()=>{Le["a"].detachEditor(this)
this.props.onRemove&&this.props.onRemove(this)}
this.toggleView=e=>{const t=this._isFullscreen()
t&&this._exitFullscreen()
let n
switch(this.state.editorView){case nt:n={editorView:e||ot}
break
case ot:n={editorView:e||nt}
break
case it:n={editorView:e||nt}}this.setState(n,()=>{t&&window.setTimeout(()=>{this._enterFullscreen()},200)})
this.checkAccessibility()
e!==ot&&e!==it||(document.cookie=`rce.htmleditor=${e};path=/;max-age=31536000`)
this.mceInstance().fire(dt,{target:this.editor,newView:n.editorView})}
this.contentTrayClosing=false
this.blurTimer=0
this.handleFocusRCE=e=>{this.handleFocus(e)}
this.handleBlurRCE=e=>{var t
null===e.relatedTarget&&this.handleBlur(e)
null!==(t=this._elementRef.current)&&void 0!==t&&t.contains(e.relatedTarget)||this.handleBlur(e)}
this.handleFocusEditor=e=>{const t=this.iframe
t&&t.parentElement.classList.add("active")
this._forceCloseFloatingToolbar()
this.handleFocus(e)}
this.handleFocusHtmlEditor=e=>{this.handleFocus(e)}
this.handleBlurEditor=e=>{const t=this.iframe
t&&t.parentElement.classList.remove("active")
this.handleBlur(e)}
this.handleKey=e=>{if("F9"===e.code&&e.altKey){e.preventDefault()
e.stopPropagation()
Gt(this._elementRef.current)}else if("F10"===e.code&&e.altKey){e.preventDefault()
e.stopPropagation()
Vt(this._elementRef.current)}else if("F8"!==e.code&&"Digit0"!==e.code||!e.altKey)if("Escape"===e.code){this._forceCloseFloatingToolbar()
this.state.fullscreenState.isTinyFullscreen?this.mceInstance().execCommand("mceFullScreen"):Le["a"].hideTrays()}else-1!==["n","N","d","D"].indexOf(e.key)&&e.stopPropagation()
else{e.preventDefault()
e.stopPropagation()
this.openKBShortcutModal()}}
this.handleClickFullscreen=()=>{this._isFullscreen()?this._exitFullscreen():this._enterFullscreen()}
this.handleExternalClick=()=>{this._forceCloseFloatingToolbar()
Object(W["a"])(this.checkAccessibility,1e3)()}
this.handleInputChange=()=>{this.checkAccessibility()}
this.onInit=(e,t)=>{var n,o
t.rceWrapper=this
this.editor=t
const i=this.editor.getElement()
i.dataset.rich_text=true
i.value=this.getCode()
i.style.height=this.state.height
document.addEventListener("click",this.handleExternalClick)
document.body.classList.contains("Underline-All-Links__enabled")&&this.iframe.contentDocument.body.classList.add("Underline-All-Links__enabled")
t.on("wordCountUpdate",this.onWordCountUpdate)
const r=document.querySelector('.tox-tinymce[role="application"]')
if(r){r.setAttribute("aria-label",Object(V["a"])("Rich Content Editor"))
r.setAttribute("role","document")
r.setAttribute("tabIndex","-1")}i.style.resize="none"
t.on("ExecCommand",this._forceCloseFloatingToolbar)
t.on("keydown",this.handleKey)
t.on("FullscreenStateChanged",this._toggleFullscreen)
t.on("click",()=>window.top.document.body.click(),true)
this.props.use_rce_a11y_checker_notifications&&t.on("Cut Paste Change input Undo Redo",Object(W["a"])(this.handleInputChange,1e3))
this.announceContextToolbars(t)
this.isAutoSaving&&this.initAutoSave(t)
this.setEditorView(this.state.editorView)
t.mode.set(this.props.readOnly?"readonly":"design")
null===(n=(o=this.props).onInitted)||void 0===n||n.call(o,t)}
this._toggleFullscreen=e=>{const t=document.getElementById("header")
if(t)if(e.state){this.setState({fullscreenState:{headerDisp:t.style.display,isTinyFullscreen:true}})
t.style.display="none"}else{t.style.display=this.state.fullscreenState.headerDisp
this.setState({fullscreenState:{isTinyFullscreen:false}})}if(!document[Xt]&&this.state.fullscreenElem){this.state.fullscreenElem.removeEventListener("fullscreenchange",this._toggleFullscreen)
this.state.fullscreenElem.removeEventListener("webkitfullscreenchange",this._toggleFullscreen)
this.setState({fullscreenState:{fullscreenElem:null}})}window.setTimeout(()=>{document[Xt]?this.setState(e=>({fullscreenState:Object(i["a"])(Object(i["a"])({},e.fullscreenState),{},{fullscreenElem:document[Xt]})})):this.forceUpdate()
this.focusCurrentView()},0)}
this._forceCloseFloatingToolbar=()=>{if(this._elementRef.current){const e=this._elementRef.current.querySelector(".tox-toolbar-overlord .tox-toolbar__group:last-child button:last-child")
if(null!==e&&void 0!==e&&e.getAttribute("aria-owns")){e.click()
const t=this.mceInstance()
null===t||void 0===t||t.focus()}}}
this.announcing=0
this.initAutoSave=e=>{this.storage=window.localStorage
if(this.storage){e.on("change Undo Redo",this.doAutoSave)
e.on("blur",this.doAutoSave)
this.cleanupAutoSave()
try{const t=this.getAutoSaved(this.autoSaveKey)
if(t&&t.content){const n=this.patchAutosavedContent(e.getContent({no_events:true}),true)
const o=this.patchAutosavedContent(t.content,true)
o!==n?this.setState({confirmAutoSave:true,autoSavedContent:this.patchAutosavedContent(t.content)}):this.storage.removeItem(this.autoSaveKey)}}catch(e){console.error("Failed initializing rce autosave",e)}}}
this.cleanupAutoSave=(e=false)=>{if(this.storage){const t=e?Date.now():Date.now()-this.props.autosave.maxAge
let n=0
let o
while(o=this.storage.key(n++))if(/^rceautosave:/.test(o)){const e=this.getAutoSaved(o)
e&&e.autosaveTimestamp<t&&this.storage.removeItem(o)}}}
this.restoreAutoSave=e=>{this.setState({confirmAutoSave:false},()=>{const t=this.mceInstance()
e&&t.setContent(this.state.autoSavedContent,{})
this.storage.removeItem(this.autoSaveKey)})
this.checkAccessibility()}
this.doAutoSave=(e,t=false)=>{if(this.storage){const n=this.mceInstance()
if(n.dom.isEmpty(n.getBody()))return
const o=n.getContent({no_events:true})
try{this.storage.setItem(this.autoSaveKey,JSON.stringify({autosaveTimestamp:Date.now(),content:o}))}catch(n){if(t)console.error("Autosave failed:",n)
else{this.cleanupAutoSave(true)
this.doAutoSave(e,true)}}}}
this.onWordCountUpdate=e=>{this.setState(t=>e.wordCount.words!==t.wordCount?{wordCount:e.wordCount.words}:null)}
this.onNodeChange=e=>{const t=e.parents.filter(e=>"BR"!==e.nodeName&&!e.getAttribute("data-mce-bogus")&&"bookmark"!==e.getAttribute("data-mce-type")).map(e=>e.nodeName.toLowerCase()).reverse()
this.setState({path:t})}
this.onEditorChange=e=>{var t,n
null===(t=(n=this.props).onContentChange)||void 0===t||t.call(n,e)}
this.onResize=(e,t)=>{const n=this.mceInstance()
if(n){const e=n.getContainer()
if(!e)return
const o=Number.parseInt(e.style.height,10)
if(isNaN(o))return
const i=o+t.deltaY
const r=i+"px"
e.style.height=r
this.getTextarea().style.height=r
this.setState({height:r})
n.fire("ResizeEditor")}}
this.onA11yChecker=()=>{this.a11yCheckerReady.then(()=>{this.onTinyMCEInstance("openAccessibilityChecker",{skip_focus:true})})}
this.checkAccessibility=()=>{if(!this.props.use_rce_a11y_checker_notifications)return
const e=this.mceInstance()
e.execCommand("checkAccessibility",false,{done:e=>{this.setState({a11yErrorsCount:e.length})}},{skip_focus:true})}
this.openKBShortcutModal=()=>{this.setState({KBShortcutModalOpen:true,KBShortcutFocusReturn:document.activeElement})}
this.closeKBShortcutModal=()=>{this.setState({KBShortcutModalOpen:false})}
this.KBShortcutModalExited=()=>{if(this.state.KBShortcutFocusReturn===this.iframe)this.editor.focus(false)
else if(this._showOnFocusButton&&document.activeElement===document.body)this._showOnFocusButton.focus()
else{var e
null===(e=this._showOnFocusButton)||void 0===e||e.focus()}}
this.handleTextareaChange=()=>{if(this.isHidden()){this.setCode(this.textareaValue())
this.doAutoSave()}}
this.addAlert=e=>{e.id=tn++
this.setState(t=>{let n=t.messages.concat(e)
n=L.a.uniqBy(n,"text")
return{messages:n}})}
this.removeAlert=e=>{this.setState(t=>{const n=t.messages.filter(t=>t.id!==e)
return{messages:n}})}
this.resetAlertId=()=>{if(this.state.messages.length>0)throw new Error("There are messages currently, you cannot reset when they are non-zero")
tn=0}
this.editor=null
this.language=Object(Ae["a"])(this.props.language)
this.get_code=this.getCode
this.set_code=this.setCode
this.insert_code=this.insertCode
this.indicator=false
this._elementRef=s.a.createRef()
this._editorPlaceholderRef=s.a.createRef()
this._prettyHtmlEditorRef=s.a.createRef()
this._showOnFocusButton=null
Wt()
let r=(null===(o=t.editorOptions)||void 0===o?void 0:o.height)||Dt
Number.isNaN(r)||(r+="px")
const a=document.querySelectorAll(".rce-wrapper").length
const c=Number.isNaN(t.maxInitRenderedRCEs)?e.defaultProps.maxInitRenderedRCEs:t.maxInitRenderedRCEs
this.state={path:[],wordCount:0,editorView:t.editorView||nt,shouldShowOnFocusButton:void 0===t.renderKBShortcutModal||t.renderKBShortcutModal,KBShortcutModalOpen:false,messages:[],announcement:null,confirmAutoSave:false,autoSavedContent:"",id:this.props.id||this.props.textareaId||""+Date.now(),height:r,fullscreenState:{headerDisp:"static",isTinyFullscreen:false},a11yErrorsCount:0,shouldShowEditor:"undefined"===typeof IntersectionObserver||c<=0||a<c}
this.pendingEventHandlers=[]
this.ltiToolFavorites=this.props.ltiTools.filter(e=>e.favorite).map(e=>"instructure_external_button_"+e.id).slice(0,2)||[]
this.tinymceInitOptions=this.wrapOptions(t.editorOptions)
kt["a"].alertFunc=this.addAlert
this.handleContentTrayClosing=this.handleContentTrayClosing.bind(this)
this.a11yCheckerReady=Promise.all([n.e(11),n.e(21),n.e(22),n.e(24),n.e(26),n.e(4121)]).then(n.bind(null,"sOmF")).then(e=>{e.default(this.language)
this.checkAccessibility()}).catch(e=>{console.error("Failed initializing a11y checker",e)})}getCanvasUrl(){this.canvasUrl||(this.canvasUrl=Ie(this.props.trayProps))
return this.canvasUrl.then(e=>{e||console.warn("Could not determine Canvas base URL.","Content will be referenced by relative URL.")
return e})}getCode(){return this.isHidden()?this.textareaValue():this.mceInstance().getContent()}checkReadyToGetCode(e){let t=true
this.mceInstance().dom.doc.querySelector("[data-placeholder-for]")&&(t=e(Object(V["a"])("Content is still being uploaded, if you continue it will not be embedded properly.")))
return t}setCode(e){var t
null===(t=this.mceInstance())||void 0===t||t.setContent(e)}RCEClosed(){this.storage&&this.storage.removeItem(this.autoSaveKey)}indicateEditor(e){if(document.querySelector('[role="dialog"][data-mce-component]')){window.setTimeout(()=>{this.indicateEditor(e)},100)
return}const t=this.mceInstance()
this.indicator?this.indicator(t,e):this.isHidden()||Object(Te["a"])(Object(Ce["a"])(t,e))}contentInserted(e){this.indicateEditor(e)
this.checkImageLoadError(e)
this.sizeEditorForContent(e)}sizeEditorForContent(e){let t
e&&1===e.nodeType&&(t=e.clientHeight)
if(t){const e=this.iframe
if(e){const n=e.contentWindow.getComputedStyle(this.iframe.contentDocument.body)
const o=e.contentDocument.body.clientHeight-parseInt(n["padding-top"],10)-parseInt(n["padding-bottom"],10)
const i=Math.ceil(t+24)
i>o&&this.onResize(null,{deltaY:i-o})}}}checkImageLoadError(e){if(!e||"IMG"!==e.tagName)return
if(!e.complete){e.onload=()=>this.checkImageLoadError(e)
return}setTimeout(()=>{if(0===e.naturalWidth){e.style.border="1px solid #000"
e.style.padding="2px"}},0)}insertCode(e){const t=this.mceInstance()
const n=ne(t,e)
this.contentInserted(n)}insertEmbedCode(e){const t=this.mceInstance()
t.selection.collapse()
const n=document.createElement("div")
n.innerHTML=e
const o=n.firstElementChild
if(o){o.hasAttribute("title")||o.hasAttribute("aria-label")||o.setAttribute("title",Object(V["a"])("embedded content"))
e=o.outerHTML}const i=ne(t,e)
const r=i&&i.querySelector&&i.querySelector("iframe")
r?this.contentInserted(r):this.contentInserted(i)}insertImage(e){var t,n
const o=this.mceInstance()
let i=ae(o,e)
""===(null===i||void 0===i||null===(t=i.nextSibling)||void 0===t||null===(n=t.data)||void 0===n?void 0:n.trim())&&i.nextSibling.remove()
if(i&&i.complete)this.contentInserted(i)
else if(i){i.onload=()=>this.contentInserted(i)
i.onerror=()=>this.checkImageLoadError(i)}}insertImagePlaceholder(e){let t,n
let o="middle"
if(Object(ee["d"])(e.contentType)&&"link"!==e.displayAs){const o=new Image
o.src=e.domObject.preview
t=o.width
n=o.height
const i=this.iframe.contentDocument.body.clientWidth
if(t>i){n=Math.round(i/t*n)
t=i}t+="px"
n+="px"}else if(Object(ee["f"])(e.contentType||e.type)){t=Ot["b"].width
n=Ot["b"].height
o="bottom"}else if(Object(ee["b"])(e.contentType||e.type)){t=Ot["a"].width
n=Ot["a"].height
o="bottom"}else{t=e.name.length+"rem"
n="1rem"}const i=`\n    <span\n      aria-label="${Object(V["a"])("Loading")}"\n      data-placeholder-for="${encodeURIComponent(e.name)}"\n      style="width: ${t}; height: ${n}; vertical-align: ${o};"\n    >\n      <svg xmlns="http://www.w3.org/2000/svg" version="1.1" x="0px" y="0px" viewBox="0 0 100 100" height="100px" width="100px">\n        <g style="stroke-width:.5rem;fill:none;stroke-linecap:round;">&nbsp;\n          <circle class="c1" cx="50%" cy="50%" r="28px">&nbsp;</circle>\n          <circle class="c2" cx="50%" cy="50%" r="28px">&nbsp;</circle>\n          &nbsp;\n        </g>\n        &nbsp;\n      </svg>\n    </span>`
const r=this.mceInstance()
r.undoManager.ignore(()=>{r.execCommand("mceInsertContent",false,i)})}insertVideo(e){const t=this.mceInstance()
const n=we(t,e)
this.contentInserted(n)}insertAudio(e){const t=this.mceInstance()
const n=ke(t,e)
this.contentInserted(n)}insertMathEquation(e){const t=this.mceInstance()
return this.getCanvasUrl().then(n=>ce(t,e,n))}removePlaceholders(e){const t=this.mceInstance().dom.doc.querySelector(`[data-placeholder-for="${encodeURIComponent(e)}"]`)
if(t){const e=this.mceInstance()
e.undoManager.ignore(()=>{e.dom.remove(t)})}}insertLink(e){const t=this.mceInstance()
const n=pe(t,e)
this.contentInserted(n)}existingContentToLink(){const e=this.mceInstance()
return de(e)}existingContentToLinkIsImg(){const e=this.mceInstance()
return _e(e)}tinymceOn(e,t){this.state.shouldShowEditor?this.mceInstance().on(e,t):this.pendingEventHandlers.push({name:e,handler:t})}mceInstance(){if(this.editor)return this.editor
const e=this.props.tinymce.editors||[]
return e.filter(e=>e.id===this.props.textareaId)[0]}onTinyMCEInstance(e,t){const n=this.mceInstance()
if(n){"mceRemoveEditor"===e&&n.execCommand("mceNewDocument")
n.execCommand(e,false,this.props.textareaId,t)}}destroy(){this._destroyCalled=true
this.unhandleTextareaChange()
this.props.handleUnmount&&this.props.handleUnmount()}getTextarea(){return document.getElementById(this.props.textareaId)}textareaValue(){return this.getTextarea().value}get id(){return this.state.id}_isFullscreen(){return this.state.fullscreenState.isTinyFullscreen||document[Xt]}_enterFullscreen(){switch(this.state.editorView){case ot:this._prettyHtmlEditorRef.current.addEventListener("fullscreenchange",this._toggleFullscreen)
this._prettyHtmlEditorRef.current.addEventListener("webkitfullscreenchange",this._toggleFullscreen)
this._prettyHtmlEditorRef.current.focus()
this._prettyHtmlEditorRef.current[Qt]()
break
case it:this.getTextarea().addEventListener("fullscreenchange",this._toggleFullscreen)
this.getTextarea().addEventListener("webkitfullscreenchange",this._toggleFullscreen)
this.getTextarea()[Qt]()
break
case nt:this.mceInstance().execCommand("mceFullScreen")}}_exitFullscreen(){this.state.fullscreenState.isTinyFullscreen?this.mceInstance().execCommand("mceFullScreen"):document[Xt]&&document[Xt][en]()}focus(){this.onTinyMCEInstance("mceFocus")
this.handleFocusEditor(new Event("focus",{target:this.mceInstance()}))}focusCurrentView(){switch(this.state.editorView){case nt:this.mceInstance().focus()
break
case ot:{const e=this._elementRef.current.querySelector(".CodeMirror textarea")
e?e.focus():window.setTimeout(()=>{var e
null===(e=this._elementRef.current.querySelector(".CodeMirror textarea"))||void 0===e||e.focus()},200)}break
case it:this.getTextarea().focus()}}is_dirty(){var e
if(this.mceInstance().isDirty())return true
const t=this.isHidden()?this.textareaValue():null===(e=this.mceInstance())||void 0===e?void 0:e.getContent()
return t!==this.cleanInitialContent()}cleanInitialContent(){if(!this._cleanInitialContent){const e=window.document.createElement("div")
e.innerHTML=this.props.defaultContent
const t=this.mceInstance().serializer
this._cleanInitialContent=t.serialize(e,{getInner:true})}return this._cleanInitialContent}isHtmlView(){return this.state.editorView!==nt}isHidden(){return this.mceInstance().isHidden()}get iframe(){return document.getElementById(this.props.textareaId+"_ifr")}get focused(){return this===Le["a"].getEditor()}handleFocus(){if(!this.focused){Le["a"].focusEditor(this)
this.props.onFocus&&this.props.onFocus(this)}}handleContentTrayClosing(e){this.contentTrayClosing=e}handleBlur(e){if(this.blurTimer)return
if(this.focused){e&&e.persist&&e.persist()
this.blurTimer=window.setTimeout(()=>{var t,n,o,i
this.blurTimer=0
if(this.contentTrayClosing)return
if(null!==(t=this._elementRef.current)&&void 0!==t&&t.contains(document.activeElement))return
const r=document.activeElement&&document.activeElement.getAttribute("class")
if((void 0===e.focusedEditor||e.target.id===(null===(n=e.focusedEditor)||void 0===n?void 0:n.id))&&null!==r&&void 0!==r&&r.includes("tox-"))return
if(null!==e&&void 0!==e&&null!==(o=e.relatedTarget)&&void 0!==o&&null!==(i=o.getAttribute("class"))&&void 0!==i&&i.includes("tox-"))return
const a=document.querySelectorAll("[data-mce-component]")
for(const e of a)if(e.contains(document.activeElement))return
Le["a"].blurEditor(this)
this.props.onBlur&&this.props.onBlur(e)},Bt)}}call(e,...t){if("exists?"===e)return true
return this[e](...t)}announceContextToolbars(e){e.on("NodeChange",()=>{const t=e.selection.getNode()
if(Object(Ct["k"])(t,e)){if(1!==this.announcing){this.setState({announcement:Object(V["a"])("type Control F9 to access image options. {text}",{text:t.getAttribute("alt")})})
this.announcing=1}}else if(Object(Ct["j"])(t,e)){if(2!==this.announcing){this.setState({announcement:Object(V["a"])("type Control F9 to access link options. {text}",{text:t.textContent})})
this.announcing=2}}else if(Kt(t,e)){if(3!==this.announcing){this.setState({announcement:Object(V["a"])("type Control F9 to access table options. {text}",{text:t.textContent})})
this.announcing=3}}else{this.setState({announcement:null})
this.announcing=0}})}patchAutosavedContent(e,t){const n=document.createElement("div")
n.innerHTML=e
n.querySelectorAll("[data-placeholder-for]").forEach(e=>{e.parentElement.removeChild(e)})
if(t)return n.textContent
return n.innerHTML}getAutoSaved(e){let t=null
try{t=this.storage&&JSON.parse(this.storage.getItem(e))}catch(e){this.storage.removeItem(this.autoSaveKey)}return t}get isAutoSaving(){const e=this.editor.getContainer().offsetParent
return this.props.autosave.enabled&&e&&1===document.querySelectorAll(".rce-wrapper").length&&Zt()}get autoSaveKey(){var e
const t=null===(e=this.props.trayProps)||void 0===e?void 0:e.containingContext.userId
return`rceautosave:${t}${window.location.href}:${this.props.textareaId}`}componentWillUnmount(){if(this.state.shouldShowEditor){var e,t
window.clearTimeout(this.blurTimer)
this._destroyCalled||this.destroy()
this._elementRef.current.removeEventListener("keydown",this.handleKey,true)
null===(e=this.mutationObserver)||void 0===e||e.disconnect()
null===(t=this.intersectionObserver)||void 0===t||t.disconnect()}}wrapOptions(e={}){var t,n,o
const r=!!(null!==(t=this.props.trayProps)&&void 0!==t&&t.host&&null!==(n=this.props.trayProps)&&void 0!==n&&n.jwt)
const a=e.setup
const c=r?["instructure_links","instructure_image","instructure_documents","instructure_equation","instructure_external_tools"]:["instructure_links"]
r&&!this.props.instRecordDisabled&&c.splice(2,0,"instructure_record")
r&&this.props.use_rce_buttons_and_icons&&"course"===(null===(o=this.props.trayProps)||void 0===o?void 0:o.contextType)&&c.push("instructure_buttons")
const s=this.props.editorOptions.menu?Object.keys(this.props.editorOptions.menu).join(" "):void 0
const l=Object(i["a"])(Object(i["a"])({},e),{},{readonly:this.props.readOnly,theme:"silver",height:e.height||Dt,language:Ee()(this.language),block_formats:e.block_formats||[Object(V["a"])("Heading 2")+"=h2",Object(V["a"])("Heading 3")+"=h3",Object(V["a"])("Heading 4")+"=h4",Object(V["a"])("Preformatted")+"=pre",Object(V["a"])("Paragraph")+"=p"].join("; "),setup:e=>{var t
$t(e)
qt.set(e,this)
const n=Object(i["a"])({brandColor:this.theme.canvasBrandColor},this.props.trayProps)
null===(t=Le["a"].trayProps)||void 0===t||t.set(e,n)
Le["a"].languages=this.props.languages
"function"===typeof a&&a(e)},content_css:e.content_css||[],content_style:Ut,menubar:on("edit view insert format tools table",s),menu:rn({format:{title:Object(V["a"])("Format"),items:"bold italic underline strikethrough superscript subscript codeformat | formats blockformats fontformats fontsizes align directionality | forecolor backcolor | removeformat"},insert:{title:Object(V["a"])("Insert"),items:"instructure_links instructure_image instructure_media instructure_document instructure_buttons | instructure_equation inserttable instructure_media_embed | hr"},tools:{title:Object(V["a"])("Tools"),items:"wordcount lti_tools_menuitem"},view:{title:Object(V["a"])("View"),items:"fullscreen instructure_html_view"}},e.menu),toolbar:an([{name:Object(V["a"])("Styles"),items:["fontsizeselect","formatselect"]},{name:Object(V["a"])("Formatting"),items:["bold","italic","underline","forecolor","backcolor","inst_subscript","inst_superscript"]},{name:Object(V["a"])("Content"),items:["instructure_links","instructure_image","instructure_record","instructure_documents","instructure_buttons"]},{name:Object(V["a"])("External Tools"),items:[...this.ltiToolFavorites,"lti_tool_dropdown","lti_mru_button"]},{name:Object(V["a"])("Alignment and Lists"),items:["align","bullist","inst_indent","inst_outdent"]},{name:Object(V["a"])("Miscellaneous"),items:["removeformat","table","instructure_equation","instructure_media_embed"]}],e.toolbar),contextmenu:"",toolbar_mode:"floating",toolbar_sticky:true,plugins:cn(["autolink","media","paste","table","link","directionality","lists","textpattern","hr","fullscreen","instructure-ui-icons","instructure_condensed_buttons","instructure_links","instructure_html_view","instructure_media_embed","instructure_external_tools","a11y_checker","wordcount",...c],Se(e.plugins)),textpattern_patterns:[{start:"* ",cmd:"InsertUnorderedList"},{start:"- ",cmd:"InsertUnorderedList"}]})
if(this.props.trayProps){l.canvas_rce_user_context={type:this.props.trayProps.contextType,id:this.props.trayProps.contextId}
l.canvas_rce_containing_context={type:this.props.trayProps.containingContext.contextType,id:this.props.trayProps.containingContext.contextId}}return l}unhandleTextareaChange(){this._textareaEl&&this._textareaEl.removeEventListener("input",this.handleTextareaChange)}registerTextareaChange(){const e=this.getTextarea()
if(this._textareaEl!==e){this.unhandleTextareaChange()
if(e){e.addEventListener("input",this.handleTextareaChange)
this.props.textareaClassName&&e.classList.add(...this.props.textareaClassName.split(/\s+/))
this._textareaEl=e}}}componentDidMount(){if(this.state.shouldShowEditor)this.editorReallyDidMount()
else{this.intersectionObserver=new IntersectionObserver(e=>{const t=e[0];(t.isIntersecting||t.intersectionRatio>0)&&this.setState({shouldShowEditor:true})},{root:null,rootMargin:"200px 0px",threshold:0})
this.intersectionObserver.observe(this._editorPlaceholderRef.current)}}componentDidUpdate(e,t){if(this.state.shouldShowEditor)if(t.shouldShowEditor){this.registerTextareaChange()
if(t.editorView!==this.state.editorView){this.setEditorView(this.state.editorView)
this.focusCurrentView()}e.readOnly!==this.props.readOnly&&this.mceInstance().mode.set(this.props.readOnly?"readonly":"design")}else{var n
this.editorReallyDidMount()
null===(n=this.intersectionObserver)||void 0===n||n.disconnect()}}editorReallyDidMount(){const e=this.mceInstance()
this.pendingEventHandlers.forEach(t=>{e.on(t.name,t.handler)})
this.registerTextareaChange()
this._elementRef.current.addEventListener("keydown",this.handleKey,true)
this.onResize(null,{deltaY:0})
this.ltiToolFavorites.length>0&&n.e(3717).then(n.bind(null,"DiQt"))
const t=document.querySelectorAll(".tox-tinymce-aux")
const o=t[t.length-1]
if(o){this.mutationObserver=new MutationObserver(e=>{e.forEach(e=>{"childList"===e.type&&e.addedNodes.length>0&&this.handleFocusEditor(new Event("focus",{target:e.target}))})})
this.mutationObserver.observe(o,{childList:true})}Le["a"].renderEditor(this)}setEditorView(e){var t,n,o,i,r,a,c
switch(e){case it:this.getTextarea().removeAttribute("aria-hidden")
null===(t=this.getTextarea().labels)||void 0===t||null===(n=t[0])||void 0===n||n.removeAttribute("aria-hidden")
this.mceInstance().hide()
break
case ot:this.getTextarea().setAttribute("aria-hidden",true)
null===(o=this.getTextarea().labels)||void 0===o||null===(i=o[0])||void 0===i||i.setAttribute("aria-hidden",true)
this.mceInstance().hide()
null===(r=this._elementRef.current.querySelector(".CodeMirror"))||void 0===r||r.CodeMirror.setCursor(0,0)
break
case nt:this.setCode(this.textareaValue())
this.getTextarea().setAttribute("aria-hidden",true)
null===(a=this.getTextarea().labels)||void 0===a||null===(c=a[0])||void 0===c||c.setAttribute("aria-hidden",true)
this.mceInstance().show()}}renderHtmlEditor(){return s.a.createElement(c["Suspense"],{fallback:s.a.createElement("div",{style:{height:this.state.height,display:"flex",justifyContent:"center",alignItems:"center"}},s.a.createElement($["a"],{renderTitle:Jt,size:"medium"}))},s.a.createElement(H["a"],{as:"div",borderRadius:"medium",borderWidth:"small"},s.a.createElement(Lt,{ref:this._prettyHtmlEditorRef,height:document[Xt]?window.screen.height+"px":this.state.height,code:this.getCode(),onChange:e=>{this.getTextarea().value=e
this.handleTextareaChange()},onFocus:this.handleFocusHtmlEditor})))}render(){const e=this.props,t=e.trayProps,n=Object(o["a"])(e,Et)
if(!this.state.shouldShowEditor)return s.a.createElement("div",{ref:this._editorPlaceholderRef,style:{width:this.props.editorOptions.width+"px",height:this.props.editorOptions.height+"px",border:"1px solid grey"}})
return s.a.createElement("div",{key:this.id,className:Pt.root+" rce-wrapper",ref:this._elementRef,onFocus:this.handleFocusRCE,onBlur:this.handleBlurRCE},this.state.shouldShowOnFocusButton&&s.a.createElement(xt,{onClick:this.openKBShortcutModal,margin:"xx-small",screenReaderLabel:Object(V["a"])("View keyboard shortcuts"),ref:e=>this._showOnFocusButton=e},s.a.createElement(N,null)),s.a.createElement(wt,{messages:this.state.messages,liveRegion:this.props.liveRegion,afterDismiss:this.removeAlert}),this.state.editorView===ot&&this.renderHtmlEditor(),s.a.createElement("div",{style:{display:this.state.editorView===ot?"none":"block"}},s.a.createElement(I,{id:n.textareaId,textareaName:n.name,init:this.tinymceInitOptions,initialValue:n.defaultContent,onInit:this.onInit,onClick:this.handleFocusEditor,onKeypress:this.handleFocusEditor,onActivate:this.handleFocusEditor,onRemove:this.onRemove,onFocus:this.handleFocusEditor,onBlur:this.handleBlurEditor,onNodeChange:this.onNodeChange,onEditorChange:this.onEditorChange})),s.a.createElement(st,{readOnly:this.props.readOnly,onChangeView:e=>this.toggleView(e),path:this.state.path,wordCount:this.state.wordCount,editorView:this.state.editorView,preferredHtmlEditor:Yt(),onResize:this.onResize,onKBShortcutModalOpen:this.openKBShortcutModal,onA11yChecker:this.onA11yChecker,onFullscreen:this.handleClickFullscreen,use_rce_a11y_checker_notifications:this.props.use_rce_a11y_checker_notifications,a11yBadgeColor:this.theme.canvasBadgeBackgroundColor,a11yErrorsCount:this.state.a11yErrorsCount}),this.props.trayProps&&this.props.trayProps.containingContext&&s.a.createElement(Be["a"],Object.assign({key:this.id,bridge:Le["a"],editor:this,onTrayClosing:this.handleContentTrayClosing,use_rce_buttons_and_icons:this.props.use_rce_buttons_and_icons},t)),s.a.createElement(vt,{onExited:this.KBShortcutModalExited,onDismiss:this.closeKBShortcutModal,open:this.state.KBShortcutModalOpen}),this.state.confirmAutoSave?s.a.createElement(c["Suspense"],{fallback:s.a.createElement($["a"],{renderTitle:Jt,size:"small"})},s.a.createElement(Tt,{savedContent:this.state.autoSavedContent,open:this.state.confirmAutoSave,onNo:()=>this.restoreAutoSave(false),onYes:()=>this.restoreAutoSave(true)})):null,s.a.createElement(U["a"],{screenReaderOnly:true,liveRegion:this.props.liveRegion},this.state.announcement))}},jt.propTypes={autosave:a.a.shape({enabled:a.a.bool,maxAge:a.a.number}),defaultContent:a.a.string,editorOptions:zt,handleUnmount:a.a.func,editorView:a.a.oneOf([nt,ot,it]),renderKBShortcutModal:a.a.bool,id:a.a.string,language:a.a.string,liveRegion:a.a.func.isRequired,ltiTools:Mt,onContentChange:a.a.func,onFocus:a.a.func,onBlur:a.a.func,onInitted:a.a.func,onRemove:a.a.func,textareaClassName:a.a.string,textareaId:a.a.string.isRequired,languages:a.a.arrayOf(a.a.shape({id:a.a.string.isRequired,label:a.a.string.isRequired})),readOnly:a.a.bool,tinymce:a.a.object,trayProps:Be["b"],toolbar:Rt,menu:Ft,plugins:a.a.arrayOf(a.a.string),instRecordDisabled:a.a.bool,highContrastCSS:a.a.arrayOf(a.a.string),maxInitRenderedRCEs:a.a.number,use_rce_buttons_and_icons:a.a.bool,use_rce_a11y_checker_notifications:a.a.bool},jt.defaultProps={trayProps:null,languages:[{id:"en",label:"English"}],autosave:{enabled:false},highContrastCSS:[],ltiTools:[],maxInitRenderedRCEs:-1},jt.skinCssInjected=false,It))||St)
function on(e,t){var n
let o=null===t||void 0===t||null===(n=t.trim)||void 0===n?void 0:n.call(t)
if(!o)return e
const i=new Set(e.split(/[\s|]+/))
o=o.split(/\s+/).filter(e=>!i.has(e))
o=o.join(" ").replace(/^\s*\|\s*/,"").replace(/\s*\|\s*$/,"")
return`${e} | ${o}`}function rn(e,t){if(!t)return e
Object.keys(t).forEach(n=>{const o=e[n]
o?o.items=on(o.items,t[n].items):e[n]=Object(i["a"])({},t[n])})
return e}function an(e,t){if(!t)return e
t.forEach(t=>{const n=e.find(e=>t.name&&Object(V["a"])(t.name)===e.name)
n?n.items.splice(n.items.length,0,...t.items):e.push(t)})
return e}function cn(e,t){if(!t)return e
const n=new Set(e)
for(const e of t)n.add(e)
return[...n]}t["a"]=nn},KAy6:function(e,t,n){"use strict"
e.exports=n("IDhZ")},LixQ:function(e,t,n){"use strict"
n.d(t,"a",(function(){return m}))
n.d(t,"b",(function(){return p}))
var o=n("vDqi")
var i=n.n(o)
var r=n("VAKy")
class a extends Error{static get type(){return"FileSizeError"}constructor({maxBytes:e,actualBytes:t},...n){super("Max file size exceeded",n)
this.name=a.type
this.maxBytes=e
this.actualBytes=t}}var c=a
const s=33
function l(e,t){const n=JSON.parse(JSON.stringify(t))
delete n.kaltura_setting
return{kaltura_session:n,allowedMediaTypes:e,uploadUrl:t.kaltura_setting.uploadUrl,entryUrl:t.kaltura_setting.entryUrl,uiconfUrl:t.kaltura_setting.uiconfUrl,entryDefaults:{partnerData:t.kaltura_setting.partner_data}}}function d(e,t){e.addEventListener("K5.ready",()=>{e.uploadFile(t)})}function u(e,t){e.addEventListener("K5.progress",e=>{const n=Math.round(e.loaded/e.total)*s
t(s+n)})}function x(e,t,n){e.addEventListener("K5.fileError",o=>{e.destroy()
f(t,o,{uploadedFile:n})})}function _(e,t,n,o,r){e.addEventListener("K5.complete",async a=>{a.contextCode=`${t.contextType}_${t.contextId}`
a.type=`${t.contextType}_${t.contextId}`
const c={id:a.entryId,type:{2:"image",5:"audio"}[a.mediaType]||a.type.includes("audio")?"audio":"video",context_code:a.contextCode,title:n.name,user_entered_title:n.name}
try{const t={onUploadProgress:e=>{const t=2*s
const n=Math.round(e.loaded/e.total)*(s+1)
r&&r(t+n)}}
const a=await i.a.post("/api/v1/media_objects",c,t)
e.destroy()
f(o,null,{mediaObject:a.data,uploadedFile:n})}catch(t){e.destroy()
f(o,t,{uploadedFile:n})}})}async function m(e,t,n,o){try{window.addEventListener("beforeunload",h)
const a=await i()({method:"POST",url:(t.origin||"")+"/api/v1/services/kaltura_session?include_upload_config=1",headers:t.headers})
o&&o(s)
const c=l(["video","audio","webm","video/webm","audio/webm"],a.data)
const m=new r["a"](c)
d(m,e)
o&&u(m,o)
x(m,n,e)
_(m,t,e,n,o)
return m}catch(t){f(n,t,{uploadedFile:e})}}async function p(e,t,n,o){const r=[]
t.forEach(e=>{if(e.isNew){const t=new Promise((t,n)=>{o&&e.file.size>o&&n(new c({maxBytes:o,actualBytes:e.file.size}))
const i=new FileReader
i.onload=function(n){t({locale:e.locale,content:n.target.result})}
i.onerror=function(e){e.target.abort()
n(e.target.error||e)}
i.readAsText(e.file)})
r.push(t)}else r.push(Promise.resolve({locale:e.locale}))})
const a=new Promise((t,o)=>{Promise.all(r).then(r=>{const a=n.origin?`${n.origin}/api/media_objects/${e}/media_tracks`:`/api/v1/media_objects/${e}/media_tracks`
i()({method:n.method||"PUT",url:a,headers:n.headers,data:r}).then(t).catch(e=>{o(e)})}).catch(e=>o(e))})
return a}function f(e,...t){window.removeEventListener("beforeunload",h)
e(...t)}function h(e){e.preventDefault()
e.returnValue=""}},LpSC:function(e,t,n){n("bZMm")
e.exports=self.fetch.bind(self)},Mesd:function(e,t,n){"use strict"
n.d(t,"b",(function(){return v}))
n.d(t,"a",(function(){return k}))
var o=n("q1tI")
var i=n.n(o)
var r=n("17x9")
var a=n("6SzX")
var c=n("sTNg")
var s=n("bzPi")
var l=n("TstA")
var d=n("/5Zp")
var u=n("GTSS")
var x=n("NFDp")
var _=n("C7l9")
function m(e){const t=e.dimensionState,n=e.label
const o=t.addOffset,r=t.inputValue,c=t.setInputValue
return i.a.createElement(_["a"],{renderLabel:i.a.createElement(a["a"],null,n),onChange:function(e,t){c(t)},onDecrement:function(){o(-1)},onIncrement:function(){o(1)},isRequired:true,showArrows:false,value:r})}m.propTypes={dimensionState:Object(r["shape"])({addOffset:r["func"].isRequired,inputValue:r["string"].isRequired,setInputValue:r["func"].isRequired}),label:r["string"].isRequired}
var p=n("VTBJ")
var f=n("ODXe")
var h=n("HoBo")
function y(e){if(null==e)return null
return Number.isFinite(e)?Math.round(e):NaN}function b(e){if(""===e.trim())return null
const t=Number.parseFloat(e,10)
return Number.isFinite(t)?Math.round(t):NaN}function g(e){return Number.isFinite(e)?""+e:""}function v(e,t){const n=e.appliedHeight,i=e.appliedWidth,r=e.appliedPercentage,a=e.naturalHeight,c=e.naturalWidth,s=e.usePercentageUnits
const l=t.minHeight,d=t.minWidth,u=t.minPercentage
const x={height:s?a:n||a,width:s?c:i||c,percentage:r||100}
const _=Object(o["useState"])({usePercentageUnits:s,inputHeight:g(x.height),inputWidth:g(x.width),inputPercentage:g(x.percentage),numericHeight:x.height,numericWidth:x.width,numericPercentage:x.percentage}),m=Object(f["a"])(_,2),v=m[0],w=m[1]
const k={height:v.numericHeight,width:v.numericWidth,percentage:v.numericPercentage}
const C={height:l,width:d,percentage:u}
const O={height:h["a"],width:h["b"]}
function E(e){w(Object(p["a"])(Object(p["a"])(Object(p["a"])({},v),e),{},{numericHeight:y(e.numericHeight),numericWidth:y(e.numericWidth),numericPercentage:y(e.numericPercentage)}))}function A(e,t,n){let o,i,r
if("percentage"===e){o=c
i=a
r=t}else{const s=O[e]
const l=s(c,a,t,n)
o=l.width
i=l.height
r=x.percentage}return{width:o,height:i,percentage:r}}function S(e,n){const o=A(e,n,t),i=o.height,r=o.width,a=o.percentage
E({numericHeight:i,numericWidth:r,numericPercentage:a,inputHeight:g(i),inputWidth:g(r),inputPercentage:g(a)})}function j(e,t){const n=b(t)
const o=A(e,n),i=o.height,r=o.width,a=o.percentage
E({numericHeight:i,numericWidth:r,numericPercentage:a,inputHeight:"height"===e?t:g(i),inputWidth:"width"===e?t:g(r),inputPercentage:"percentage"===e?t:g(a)})}function I(e,t){const n=C[e]
const o=x[e]
const i=k[e]
if(null!=i&&!Number.isFinite(i))return
const r=null==i?o+t:Math.max(n,Math.floor(i+t))
S(e,r)}const T={inputValue:v.inputWidth,addOffset(e){I("width",e)},setInputValue(e){j("width",e)}}
const L={inputValue:v.inputHeight,addOffset(e){I("height",e)},setInputValue(e){j("height",e)}}
const B={inputValue:v.inputPercentage,addOffset(e){I("percentage",e)},setInputValue(e){j("percentage",e)}}
const D=v.usePercentageUnits?Number.isFinite(v.numericPercentage):[v.numericHeight,v.numericWidth].every(Number.isFinite)
const R=v.usePercentageUnits?v.numericPercentage>=u:v.numericHeight>=l&&v.numericWidth>=d
return{widthState:T,heightState:L,percentageState:B,isAtLeastMinimums:R,isNumeric:D,width:v.numericWidth,height:v.numericHeight,percentage:v.numericPercentage,usePercentageUnits:v.usePercentageUnits,setUsePercentageUnits:e=>{w(Object(p["a"])(Object(p["a"])({},v),{},{usePercentageUnits:e}))},isValid:R&&D}}const w=(e,t,n,o)=>{let i={text:Object(x["a"])("Aspect ratio will be preserved"),type:"hint"}
e.usePercentageUnits?e.isNumeric?e.isAtLeastMinimums||(i={text:Object(x["a"])("Must be at least {percentage}%",{percentage:o}),type:"error"}):i={text:Object(x["a"])("Percentage must be a number"),type:"error"}:e.isNumeric?e.isAtLeastMinimums||(i={text:Object(x["a"])("Must be at least {width} x {height}px",{width:t,height:n}),type:"error"}):i={text:Object(x["a"])("Width and height must be numbers"),type:"error"}
return i}
function k(e){const t=e.dimensionsState,n=e.minHeight,o=e.minWidth,r=e.minPercentage
const _=w(t,o,n,r)
return i.a.createElement(i.a.Fragment,null,i.a.createElement(l["a"],{direction:"column"},i.a.createElement(l["a"].Item,{padding:"small"},i.a.createElement(d["a"],{"data-testid":"dimension-type",name:"dimension-type",description:Object(x["a"])("Dimension type"),onChange:e=>{t.setUsePercentageUnits("percentage"===e.target.value)},value:t.usePercentageUnits?"percentage":"pixels"},i.a.createElement(u["a"],{label:Object(x["a"])("Pixels"),value:"pixels"}),i.a.createElement(u["a"],{label:Object(x["a"])("Percentage"),value:"percentage"})))),i.a.createElement(c["b"],{description:i.a.createElement(a["a"],null,Object(x["a"])("Dimensions")),messages:[_]},i.a.createElement(l["a"],{alignItems:"start",direction:"row","data-testid":"input-number-container"},t.usePercentageUnits?i.a.createElement(i.a.Fragment,null,i.a.createElement(l["a"].Item,{shouldShrink:true,shouldGrow:true},i.a.createElement(m,{dimensionState:t.percentageState,label:Object(x["a"])("Percentage")})),i.a.createElement(l["a"].Item,{padding:"x-small small"},"%")):i.a.createElement(i.a.Fragment,null,i.a.createElement(l["a"].Item,{shrink:true},i.a.createElement(m,{dimensionState:t.widthState,label:Object(x["a"])("Width"),minValue:o})),i.a.createElement(l["a"].Item,{padding:"x-small small"},i.a.createElement(s["a"],null)),i.a.createElement(l["a"].Item,{shrink:true},i.a.createElement(m,{dimensionState:t.heightState,label:Object(x["a"])("Height"),minValue:n}))))))}k.propTypes={dimensionsState:Object(r["shape"])({heightState:Object(r["shape"])({addOffset:r["func"].isRequired,inputValue:r["string"].isRequired,setInputValue:r["func"].isRequired}).isRequired,isNumeric:r["bool"].isRequired,usePercentageUnits:r["bool"].isRequired,setUsePercentageUnits:r["func"].isRequired,widthState:Object(r["shape"])({addOffset:r["func"].isRequired,inputValue:r["string"].isRequired,setInputValue:r["func"].isRequired}).isRequired,percentageState:Object(r["shape"])({addOffset:r["func"].isRequired,inputValue:r["string"].isRequired,setInputValue:r["func"].isRequired}).isRequired}),minHeight:r["number"].isRequired,minWidth:r["number"].isRequired,minPercentage:r["number"].isRequired}},NFDp:function(e,t,n){"use strict"
var o=n("VTBJ")
var i=n("/HcR")
var r=n.n(i)
const a=r.a.namespace()
a.addLocale=e=>{a.setup({translations:Object(o["a"])(Object(o["a"])({},a.setup().translations),e)})}
t["a"]=a},NOPk:function(e,t,n){"use strict"
var o=n("ZoNA")
var i="AAAAAAACEEEEIIIIDNOOOOO.OUUUUY..aaaaaaaceeeeiiiidnooooo.ouuuuy.yAaAaAaCcCcCcCcDdDdEeEeEeEeEeGgGgGgGgHhHhIiIiIiIiIiIiJjKkkLlLlLlLlJlNnNnNnnNnOoOoOoOoRrRrRrSsSsSsSsTtTtTtUuUuUuUuUuUuWwYyYZzZzZz."
function r(e){var t=""
var n=e.length
var o=i.length
for(var r=0;r<n;++r){var a=e[r]
var c=a.charCodeAt(0)-192
if(c>=0&&c<o){var s=i[c]
"."!==s&&(a=s)}t+=a}return t}function a(e){return r(e).toLowerCase().replace(/[^a-z0-9]+/g,"_").replace(/^_|_$/g,"").slice(0,50)}e.exports=function(e){return a(o(e))}
e.exports.underscore=a},QUlp:function(e,t,n){"use strict"
n.d(t,"a",(function(){return c}))
var o=n("t6i0")
var i=n.n(o)
function r(e){return e.getContainer().querySelector("iframe")}function a(e){const t=e.getBoundingClientRect()
return{top:t.top,left:t.left,width:t.right-t.left,height:t.bottom-t.top}}function c(e,t,n=i.a){const o=r(e)
const c=n(o)
const s=a(t)
return{width:s.width,height:s.height,left:c.left+s.left,top:c.top+s.top}}},QV6e:function(e,t,n){"use strict"
var o=n("+oik")
t["a"]=new o["a"]},RqKb:function(e,t,n){"use strict"
n.d(t,"a",(function(){return x}))
var o=n("VTBJ")
var i=n("1OyB")
var r=n("vuIU")
var a=n("Ji7U")
var c=n("LK+K")
var s=n("q1tI")
var l=n.n(s)
var d=n("hPGw")
var u=l.a.createElement("path",{d:"M915.743529 213L915.743529 915.743529 213 915.743529 213 1003.58647 915.743529 1003.58647 915.743529 1706.33 1003.58647 1706.33 1003.58647 1003.58647 1706.33 1003.58647 1706.33 915.743529 1003.58647 915.743529 1003.58647 213z",fillRule:"evenodd",stroke:"none",strokeWidth:"1"})
var x=function(e){Object(a["a"])(n,e)
var t=Object(c["a"])(n)
function n(){Object(i["a"])(this,n)
return t.apply(this,arguments)}Object(r["a"])(n,[{key:"render",value:function(){return l.a.createElement(d["a"],Object.assign({},this.props,{name:"IconAdd",viewBox:"0 0 1920 1920"}),u)}}])
n.displayName="IconAddLine"
return n}(s["Component"])
x.glyphName="add"
x.variant="Line"
x.propTypes=Object(o["a"])({},d["a"].propTypes)},WRSb:function(e,t,n){"use strict"
n.d(t,"c",(function(){return _}))
n.d(t,"a",(function(){return m}))
n.d(t,"b",(function(){return p}))
n.d(t,"e",(function(){return f}))
n.d(t,"f",(function(){return y}))
n.d(t,"d",(function(){return b}))
n.d(t,"h",(function(){return g}))
n.d(t,"j",(function(){return v}))
n.d(t,"k",(function(){return w}))
n.d(t,"l",(function(){return C}))
n.d(t,"i",(function(){return O}))
n.d(t,"g",(function(){return E}))
var o=n("VTBJ")
var i=n("hlkS")
var r=n("DWdj")
var a=n("CxY0")
var c=n("NFDp")
const s=/^\/(courses\/\d+\/)?files\/\d+\/download$/
const l="link"
const d="file-link"
const u="image-embed"
const x="video-embed"
const _="link"
const m="embed"
const p="embed-disabled"
function f(e){const t=e.nodeName.toLowerCase()
if("img"!==t)return null
return Object(o["a"])(Object(o["a"])({},Object(i["f"])(e)),{},{$element:e,type:u})}function h(e,t){let n=e
"A"!==n.tagName&&(n=t.dom.getParent(n,"a[href]"))
if(!n||"A"!==n.tagName||!n.href)return null
const o=a["parse"](n.href),i=o.pathname
const c=s.test(i)?d:l
let u=_
n.classList.contains("auto_open")?u=m:n.classList.contains("inline_disabled")&&(u=p)
const x=n.hasAttribute("data-canvas-previewable")||n.classList.contains("instructure_scribd_file")
return{$element:n,displayAs:u,text:n.textContent,onlyTextSelected:Object(r["e"])(t.selection.getContent()),type:c,isPreviewable:x,url:n.href}}function y(e){var t
const n=E(e)
if(!C(n))return null
return Object(o["a"])(Object(o["a"])({},Object(i["g"])(n)),{},{$element:e,type:x,id:(null===(t=n.parentElement)||void 0===t?void 0:t.getAttribute("data-mce-p-data-media-id"))||n.getAttribute("data-mce-p-data-media-id")})}function b(e){var t
if(!e)return null
const n="IFRAME"===e.tagName?e:e.firstElementChild
const o=n.parentElement
const i=(n.getAttribute("title")||o.getAttribute("data-mce-p-title")||"").replace(Object(c["a"])("Video player for "),"")
const r={titleText:i,id:(null===(t=e.parentElement)||void 0===t?void 0:t.getAttribute("data-mce-p-data-media-id"))||e.getAttribute("data-mce-p-data-media-id")}
if("IFRAME"===n.tagName){const e=n.contentDocument
try{var a
const t=null===(a=e.querySelector("[data-tracks]"))||void 0===a?void 0:a.getAttribute("data-tracks")
t&&(r.tracks=JSON.parse(t))}catch(e){}}return r}function g(e){const t=e.selection.getNode()
return t?h(t,e):null}function v(e,t){return!!h(e,t)}function w(e){return!!f(e)&&!e.getAttribute("data-placeholder-for")}function k(e,t){var n
if(!(null!==e&&void 0!==e&&e.getAttribute))return false
const o="IFRAME"===e.tagName?e.parentElement:e
if("IFRAME"!==(null===(n=o.firstElementChild)||void 0===n?void 0:n.tagName))return false
const i=o.getAttribute("data-mce-p-data-media-id")
if(!i)return false
const r=o.getAttribute("data-mce-p-data-media-type")
return r===t}function C(e){return k(e,"video")}function O(e){return k(e,"audio")}function E(e){var t
if("IFRAME"===e.tagName)return e
if("IFRAME"===(null===(t=e.firstElementChild)||void 0===t?void 0:t.tagName))return e.firstElementChild
if(e.classList.contains("mce-shim")){var n
if("IFRAME"===(null===(n=e.previousSibling)||void 0===n?void 0:n.tagName))return e.previousSibling}return null}},Wfew:function(e,t,n){"use strict"
n.r(t)
var o=n("NFDp")
const i={UploadMediaStrings:{ADD_CLOSED_CAPTIONS_OR_SUBTITLES:Object(o["a"])("Add CC/Subtitles"),CLEAR_FILE_TEXT:Object(o["a"])("Clear selected file"),CLOSE_TEXT:Object(o["a"])("Close"),CLOSED_CAPTIONS_CHOOSE_FILE:Object(o["a"])("Choose caption file"),CLOSED_CAPTIONS_SELECT_LANGUAGE:Object(o["a"])("Select Language"),COMPUTER_PANEL_TITLE:Object(o["a"])("Computer"),DRAG_DROP_CLICK_TO_BROWSE:Object(o["a"])("Drag and drop, or click to browse your computer"),DRAG_FILE_TEXT:Object(o["a"])("Drag a file here"),EMBED_PANEL_TITLE:Object(o["a"])("Embed"),EMBED_VIDEO_CODE_TEXT:Object(o["a"])("Embed Code"),INVALID_FILE_TEXT:Object(o["a"])("Invalid File"),LOADING_MEDIA:Object(o["a"])("Loading..."),RECORD_PANEL_TITLE:Object(o["a"])("Record"),SUBMIT_TEXT:Object(o["a"])("Submit"),UPLOADING_ERROR:Object(o["a"])("An error occurred uploading your media."),UPLOAD_MEDIA_LABEL:Object(o["a"])("Upload Media"),MEDIA_RECORD_NOT_AVAILABLE:Object(o["a"])("Audio and video recording not supported; please use a different browser."),SUPPORTED_FILE_TYPES:Object(o["a"])("Supported file types: SRT or WebVTT"),NO_FILE_CHOSEN:Object(o["a"])("No file chosen"),REMOVE_FILE:"Remove {lang} closed captions",ADD_NEW_CAPTION_OR_SUBTITLE:Object(o["a"])("Add another"),ADDED_CAPTION:"Captions for {lang} added",DELETED_CAPTION:"Deleted captions for {lang}",PROGRESS_LABEL:Object(o["a"])("Uploading")},SelectStrings:{USE_ARROWS:"Use arrow keys to navigate options.",LIST_COLLAPSED:"List collapsed.",LIST_EXPANDED:"List expanded.",OPTION_SELECTED:"{option} selected."}}
t["default"]=i},Zk7g:function(e,t,n){"use strict"
n.d(t,"a",(function(){return x}))
var o=n("VTBJ")
var i=n("1OyB")
var r=n("vuIU")
var a=n("Ji7U")
var c=n("LK+K")
var s=n("q1tI")
var l=n.n(s)
var d=n("hPGw")
var u=l.a.createElement("path",{d:"M1920,113 L1920,1807.11765 L0,1807.11765 L0,113 L1920,113 Z M1807.05882,225.941176 L112.941176,225.941176 L112.941176,1694.28941 L1807.05882,1694.28941 L1807.05882,225.941176 Z M935.943529,1058.76941 C1118.79529,800.36 1268.44235,771.898824 1362.63529,793.922353 C1523.35059,831.305882 1634.71059,1036.18118 1693.44,1402.90118 L1693.44,1402.90118 L1703.94353,1468.29412 L207.924706,1468.29412 L228.028235,1396.57647 C313.411765,1090.50588 400.941176,939.503529 511.397647,906.863529 C613.948235,876.708235 696.734118,950.684706 770.258824,1015.96471 C813.854118,1054.47765 861.063529,1097.05647 892.8,1094.79765 C908.724706,1092.99059 924.988235,1074.24235 935.943529,1058.76941 Z M1337.11059,903.927059 C1254.09882,884.614118 1141.04471,964.689412 1028.21647,1123.93647 C992.978824,1173.74353 951.868235,1201.75294 905.901176,1207.06118 C829.674918,1216.08518 767.719319,1164.23433 707.088995,1110.79476 L703.220649,1107.38213 C700.642786,1105.10638 698.066824,1102.83002 695.491765,1100.55765 C641.28,1052.44471 584.809412,1003.54118 543.472941,1015.17412 C509.025882,1025.33882 441.148235,1084.29412 357.684706,1355.35294 L357.684706,1355.35294 L1570.44706,1355.35294 C1519.96235,1090.16706 1436.04706,926.967059 1337.11059,903.927059 Z M677.647059,338.882353 C802.221176,338.882353 903.529412,440.190588 903.529412,564.764706 C903.529412,689.338824 802.221176,790.647059 677.647059,790.647059 C553.072941,790.647059 451.764706,689.338824 451.764706,564.764706 C451.764706,440.190588 553.072941,338.882353 677.647059,338.882353 Z M677.647059,451.823529 C615.303529,451.823529 564.705882,502.534118 564.705882,564.764706 C564.705882,626.995294 615.303529,677.705882 677.647059,677.705882 C739.990588,677.705882 790.588235,626.995294 790.588235,564.764706 C790.588235,502.534118 739.990588,451.823529 677.647059,451.823529 Z",fillRule:"evenodd",stroke:"none",strokeWidth:"1"})
var x=function(e){Object(a["a"])(n,e)
var t=Object(c["a"])(n)
function n(){Object(i["a"])(this,n)
return t.apply(this,arguments)}Object(r["a"])(n,[{key:"render",value:function(){return l.a.createElement(d["a"],Object.assign({},this.props,{name:"IconImage",viewBox:"0 0 1920 1920"}),u)}}])
n.displayName="IconImageLine"
return n}(s["Component"])
x.glyphName="image"
x.variant="Line"
x.propTypes=Object(o["a"])({},d["a"].propTypes)},ZoNA:function(e,t,n){"use strict"
var o=n("O92E")
var i=n("CpOe")
e.exports=function(e){return i(o(e)).replace(/\s+/g," ")}},"b5/e":function(e,t,n){"use strict"
n.d(t,"c",(function(){return m}))
n.d(t,"d",(function(){return p}))
n.d(t,"b",(function(){return h}))
n.d(t,"e",(function(){return y}))
n.d(t,"a",(function(){return b}))
var o=n("Ff2n")
var i=n("VTBJ")
var r=n("q1tI")
var a=n.n(r)
var c=n("KAy6")
var s=n("DWdj")
var l=n("NFDp")
var d=n("G1G5")
var u=n("kyQv")
var x=n("qScw")
const _=["href","url","title","display_name","alt_text","isDecorativeImage","link"]
function m(e,t){const n=Object(i["a"])({},e)
n.href=Object(x["d"])(n.href||n.url)
delete n.url
n.href&&(n.href=Object(s["a"])(n.href))
n.title=n.title||Object(l["a"])("Link")
const o=t||n.text||n.title
delete n.selectionDetails
delete n.text
n.className=n.class
delete n.class
Object.keys(n).forEach(e=>{"boolean"===typeof n[e]&&(n[e]=n[e].toString())})
return Object(c["renderToStaticMarkup"])(a.a.createElement("a",n,o))}function p(e,t){const n=e.getAttribute("href")
t.href=Object(x["c"])(t.href)
return Object(c["renderToStaticMarkup"])(a.a.createElement("a",{href:n,"data-mce-href":n},f(t,{doNotLink:true})))}function f(e,t={}){const n=e.href,i=e.url,r=e.title,c=e.display_name,s=e.alt_text,l=e.isDecorativeImage,d=e.link,u=Object(o["a"])(e,_)
let x=s||r||c||""
if(l){x=""
u.role="presentation"}const m=a.a.createElement("img",Object.assign({alt:x,src:n||i,width:e.width,height:e.height},u))
if(d&&!t.doNotLink)return a.a.createElement("a",{href:d,target:"_blank",rel:"noopener noreferrer"},m)
return m}function h(e,t){e.href=Object(x["c"])(e.href)
return Object(c["renderToStaticMarkup"])(f(e,t))}function y(e){const t=Object(u["g"])(e)
return`\n  <iframe\n      allow="fullscreen"\n      allowfullscreen\n      data-media-id="${e.media_id||e.id||e.file_id}"\n      data-media-type="video"\n      src="${t}"\n      style="width:${d["b"].width};height:${d["b"].height};display:inline-block;"\n      title="${Object(l["a"])("Video player for {title}",{title:e.title||e.name||e.text})}"></iframe>\n  `.trim().replace(/\s+/g," ")}function b(e){const t=Object(u["g"])(e)
return`\n  <iframe\n      data-media-id="${e.media_id||e.id||e.file_id}"\n      data-media-type="audio"\n      src="${t}"\n      style="width:${d["a"].width};height:${d["a"].height};display:inline-block;"\n      title="${Object(l["a"])("Audio player for {title}",{title:e.title||e.name||e.text})}"></iframe>\n  `.trim().replace(/\s+/g," ")}},bQgK:function(e,t,n){(function(t){(function(){var n,o,i,r,a,c
if("undefined"!==typeof performance&&null!==performance&&performance.now)e.exports=function(){return performance.now()}
else if("undefined"!==typeof t&&null!==t&&t.hrtime){e.exports=function(){return(n()-a)/1e6}
o=t.hrtime
n=function(){var e
e=o()
return 1e9*e[0]+e[1]}
r=n()
c=1e9*t.uptime()
a=r-c}else if(Date.now){e.exports=function(){return Date.now()-i}
i=Date.now()}else{e.exports=function(){return(new Date).getTime()-i}
i=(new Date).getTime()}}).call(this)}).call(this,n("8oxB"))},bZMm:function(e,t,n){"use strict"
n.r(t)
n.d(t,"Headers",(function(){return u}))
n.d(t,"Request",(function(){return v}))
n.d(t,"Response",(function(){return C}))
n.d(t,"DOMException",(function(){return E}))
n.d(t,"fetch",(function(){return A}))
var o="undefined"!==typeof globalThis&&globalThis||"undefined"!==typeof self&&self||"undefined"!==typeof o&&o
var i={searchParams:"URLSearchParams"in o,iterable:"Symbol"in o&&"iterator"in Symbol,blob:"FileReader"in o&&"Blob"in o&&function(){try{new Blob
return true}catch(e){return false}}(),formData:"FormData"in o,arrayBuffer:"ArrayBuffer"in o}
function r(e){return e&&DataView.prototype.isPrototypeOf(e)}if(i.arrayBuffer){var a=["[object Int8Array]","[object Uint8Array]","[object Uint8ClampedArray]","[object Int16Array]","[object Uint16Array]","[object Int32Array]","[object Uint32Array]","[object Float32Array]","[object Float64Array]"]
var c=ArrayBuffer.isView||function(e){return e&&a.indexOf(Object.prototype.toString.call(e))>-1}}function s(e){"string"!==typeof e&&(e=String(e))
if(/[^a-z0-9\-#$%&'*+.^_`|~!]/i.test(e)||""===e)throw new TypeError('Invalid character in header field name: "'+e+'"')
return e.toLowerCase()}function l(e){"string"!==typeof e&&(e=String(e))
return e}function d(e){var t={next:function(){var t=e.shift()
return{done:void 0===t,value:t}}}
i.iterable&&(t[Symbol.iterator]=function(){return t})
return t}function u(e){this.map={}
e instanceof u?e.forEach((function(e,t){this.append(t,e)}),this):Array.isArray(e)?e.forEach((function(e){this.append(e[0],e[1])}),this):e&&Object.getOwnPropertyNames(e).forEach((function(t){this.append(t,e[t])}),this)}u.prototype.append=function(e,t){e=s(e)
t=l(t)
var n=this.map[e]
this.map[e]=n?n+", "+t:t}
u.prototype["delete"]=function(e){delete this.map[s(e)]}
u.prototype.get=function(e){e=s(e)
return this.has(e)?this.map[e]:null}
u.prototype.has=function(e){return this.map.hasOwnProperty(s(e))}
u.prototype.set=function(e,t){this.map[s(e)]=l(t)}
u.prototype.forEach=function(e,t){for(var n in this.map)this.map.hasOwnProperty(n)&&e.call(t,this.map[n],n,this)}
u.prototype.keys=function(){var e=[]
this.forEach((function(t,n){e.push(n)}))
return d(e)}
u.prototype.values=function(){var e=[]
this.forEach((function(t){e.push(t)}))
return d(e)}
u.prototype.entries=function(){var e=[]
this.forEach((function(t,n){e.push([n,t])}))
return d(e)}
i.iterable&&(u.prototype[Symbol.iterator]=u.prototype.entries)
function x(e){if(e.bodyUsed)return Promise.reject(new TypeError("Already read"))
e.bodyUsed=true}function _(e){return new Promise((function(t,n){e.onload=function(){t(e.result)}
e.onerror=function(){n(e.error)}}))}function m(e){var t=new FileReader
var n=_(t)
t.readAsArrayBuffer(e)
return n}function p(e){var t=new FileReader
var n=_(t)
t.readAsText(e)
return n}function f(e){var t=new Uint8Array(e)
var n=new Array(t.length)
for(var o=0;o<t.length;o++)n[o]=String.fromCharCode(t[o])
return n.join("")}function h(e){if(e.slice)return e.slice(0)
var t=new Uint8Array(e.byteLength)
t.set(new Uint8Array(e))
return t.buffer}function y(){this.bodyUsed=false
this._initBody=function(e){this.bodyUsed=this.bodyUsed
this._bodyInit=e
if(e)if("string"===typeof e)this._bodyText=e
else if(i.blob&&Blob.prototype.isPrototypeOf(e))this._bodyBlob=e
else if(i.formData&&FormData.prototype.isPrototypeOf(e))this._bodyFormData=e
else if(i.searchParams&&URLSearchParams.prototype.isPrototypeOf(e))this._bodyText=e.toString()
else if(i.arrayBuffer&&i.blob&&r(e)){this._bodyArrayBuffer=h(e.buffer)
this._bodyInit=new Blob([this._bodyArrayBuffer])}else i.arrayBuffer&&(ArrayBuffer.prototype.isPrototypeOf(e)||c(e))?this._bodyArrayBuffer=h(e):this._bodyText=e=Object.prototype.toString.call(e)
else this._bodyText=""
this.headers.get("content-type")||("string"===typeof e?this.headers.set("content-type","text/plain;charset=UTF-8"):this._bodyBlob&&this._bodyBlob.type?this.headers.set("content-type",this._bodyBlob.type):i.searchParams&&URLSearchParams.prototype.isPrototypeOf(e)&&this.headers.set("content-type","application/x-www-form-urlencoded;charset=UTF-8"))}
if(i.blob){this.blob=function(){var e=x(this)
if(e)return e
if(this._bodyBlob)return Promise.resolve(this._bodyBlob)
if(this._bodyArrayBuffer)return Promise.resolve(new Blob([this._bodyArrayBuffer]))
if(this._bodyFormData)throw new Error("could not read FormData body as blob")
return Promise.resolve(new Blob([this._bodyText]))}
this.arrayBuffer=function(){if(this._bodyArrayBuffer){var e=x(this)
if(e)return e
return ArrayBuffer.isView(this._bodyArrayBuffer)?Promise.resolve(this._bodyArrayBuffer.buffer.slice(this._bodyArrayBuffer.byteOffset,this._bodyArrayBuffer.byteOffset+this._bodyArrayBuffer.byteLength)):Promise.resolve(this._bodyArrayBuffer)}return this.blob().then(m)}}this.text=function(){var e=x(this)
if(e)return e
if(this._bodyBlob)return p(this._bodyBlob)
if(this._bodyArrayBuffer)return Promise.resolve(f(this._bodyArrayBuffer))
if(this._bodyFormData)throw new Error("could not read FormData body as text")
return Promise.resolve(this._bodyText)}
i.formData&&(this.formData=function(){return this.text().then(w)})
this.json=function(){return this.text().then(JSON.parse)}
return this}var b=["DELETE","GET","HEAD","OPTIONS","POST","PUT"]
function g(e){var t=e.toUpperCase()
return b.indexOf(t)>-1?t:e}function v(e,t){if(!(this instanceof v))throw new TypeError('Please use the "new" operator, this DOM object constructor cannot be called as a function.')
t=t||{}
var n=t.body
if(e instanceof v){if(e.bodyUsed)throw new TypeError("Already read")
this.url=e.url
this.credentials=e.credentials
t.headers||(this.headers=new u(e.headers))
this.method=e.method
this.mode=e.mode
this.signal=e.signal
if(!n&&null!=e._bodyInit){n=e._bodyInit
e.bodyUsed=true}}else this.url=String(e)
this.credentials=t.credentials||this.credentials||"same-origin"
!t.headers&&this.headers||(this.headers=new u(t.headers))
this.method=g(t.method||this.method||"GET")
this.mode=t.mode||this.mode||null
this.signal=t.signal||this.signal
this.referrer=null
if(("GET"===this.method||"HEAD"===this.method)&&n)throw new TypeError("Body not allowed for GET or HEAD requests")
this._initBody(n)
if(("GET"===this.method||"HEAD"===this.method)&&("no-store"===t.cache||"no-cache"===t.cache)){var o=/([?&])_=[^&]*/
if(o.test(this.url))this.url=this.url.replace(o,"$1_="+(new Date).getTime())
else{var i=/\?/
this.url+=(i.test(this.url)?"&":"?")+"_="+(new Date).getTime()}}}v.prototype.clone=function(){return new v(this,{body:this._bodyInit})}
function w(e){var t=new FormData
e.trim().split("&").forEach((function(e){if(e){var n=e.split("=")
var o=n.shift().replace(/\+/g," ")
var i=n.join("=").replace(/\+/g," ")
t.append(decodeURIComponent(o),decodeURIComponent(i))}}))
return t}function k(e){var t=new u
var n=e.replace(/\r?\n[\t ]+/g," ")
n.split("\r").map((function(e){return 0===e.indexOf("\n")?e.substr(1,e.length):e})).forEach((function(e){var n=e.split(":")
var o=n.shift().trim()
if(o){var i=n.join(":").trim()
t.append(o,i)}}))
return t}y.call(v.prototype)
function C(e,t){if(!(this instanceof C))throw new TypeError('Please use the "new" operator, this DOM object constructor cannot be called as a function.')
t||(t={})
this.type="default"
this.status=void 0===t.status?200:t.status
this.ok=this.status>=200&&this.status<300
this.statusText=void 0===t.statusText?"":""+t.statusText
this.headers=new u(t.headers)
this.url=t.url||""
this._initBody(e)}y.call(C.prototype)
C.prototype.clone=function(){return new C(this._bodyInit,{status:this.status,statusText:this.statusText,headers:new u(this.headers),url:this.url})}
C.error=function(){var e=new C(null,{status:0,statusText:""})
e.type="error"
return e}
var O=[301,302,303,307,308]
C.redirect=function(e,t){if(-1===O.indexOf(t))throw new RangeError("Invalid status code")
return new C(null,{status:t,headers:{location:e}})}
var E=o.DOMException
try{new E}catch(e){E=function(e,t){this.message=e
this.name=t
var n=Error(e)
this.stack=n.stack}
E.prototype=Object.create(Error.prototype)
E.prototype.constructor=E}function A(e,t){return new Promise((function(n,r){var a=new v(e,t)
if(a.signal&&a.signal.aborted)return r(new E("Aborted","AbortError"))
var c=new XMLHttpRequest
function s(){c.abort()}c.onload=function(){var e={status:c.status,statusText:c.statusText,headers:k(c.getAllResponseHeaders()||"")}
e.url="responseURL"in c?c.responseURL:e.headers.get("X-Request-URL")
var t="response"in c?c.response:c.responseText
setTimeout((function(){n(new C(t,e))}),0)}
c.onerror=function(){setTimeout((function(){r(new TypeError("Network request failed"))}),0)}
c.ontimeout=function(){setTimeout((function(){r(new TypeError("Network request failed"))}),0)}
c.onabort=function(){setTimeout((function(){r(new E("Aborted","AbortError"))}),0)}
function d(e){try{return""===e&&o.location.href?o.location.href:e}catch(t){return e}}c.open(a.method,d(a.url),true)
"include"===a.credentials?c.withCredentials=true:"omit"===a.credentials&&(c.withCredentials=false)
"responseType"in c&&(i.blob?c.responseType="blob":i.arrayBuffer&&a.headers.get("Content-Type")&&-1!==a.headers.get("Content-Type").indexOf("application/octet-stream")&&(c.responseType="arraybuffer"))
!t||"object"!==typeof t.headers||t.headers instanceof u?a.headers.forEach((function(e,t){c.setRequestHeader(t,e)})):Object.getOwnPropertyNames(t.headers).forEach((function(e){c.setRequestHeader(e,l(t.headers[e]))}))
if(a.signal){a.signal.addEventListener("abort",s)
c.onreadystatechange=function(){4===c.readyState&&a.signal.removeEventListener("abort",s)}}c.send("undefined"===typeof a._bodyInit?null:a._bodyInit)}))}A.polyfill=true
if(!o.fetch){o.fetch=A
o.Headers=u
o.Request=v
o.Response=C}},bzPi:function(e,t,n){"use strict"
n.d(t,"a",(function(){return x}))
var o=n("VTBJ")
var i=n("1OyB")
var r=n("vuIU")
var a=n("Ji7U")
var c=n("LK+K")
var s=n("q1tI")
var l=n.n(s)
var d=n("hPGw")
var u=l.a.createElement("path",{d:"M1581.29412,1694.11765 C1581.29412,1756.34824 1530.69647,1807.05882 1468.35294,1807.05882 L451.882353,1807.05882 C389.651765,1807.05882 338.941176,1756.34824 338.941176,1694.11765 L338.941176,1016.47059 L451.882353,1016.47059 L1468.35294,1016.47059 L1581.29412,1016.47059 L1581.29412,1694.11765 Z M1468.35294,903.529412 L1468.35294,508.235294 C1468.35294,228.028235 1240.32471,0 960.117647,0 C679.910588,0 451.882353,228.028235 451.882353,508.235294 L451.882353,903.529412 L226,903.529412 L226,1694.11765 C226,1818.69176 327.308235,1920 451.882353,1920 L1468.35294,1920 C1592.92706,1920 1694.23529,1818.69176 1694.23529,1694.11765 L1694.23529,903.529412 L1468.35294,903.529412 Z M1016.58824,1242.35294 L1016.58824,1581.17647 L903.647059,1581.17647 L903.647059,1242.35294 L1016.58824,1242.35294 Z M960.117647,112.941176 C1178.09412,112.941176 1355.41176,290.258824 1355.41176,508.235294 L1355.41176,903.529412 L564.823529,903.529412 L564.823529,508.235294 C564.823529,290.258824 742.141176,112.941176 960.117647,112.941176 Z",fillRule:"evenodd",stroke:"none",strokeWidth:"1"})
var x=function(e){Object(a["a"])(n,e)
var t=Object(c["a"])(n)
function n(){Object(i["a"])(this,n)
return t.apply(this,arguments)}Object(r["a"])(n,[{key:"render",value:function(){return l.a.createElement(d["a"],Object.assign({},this.props,{name:"IconLock",viewBox:"0 0 1920 1920"}),u)}}])
n.displayName="IconLockLine"
return n}(s["Component"])
x.glyphName="lock"
x.variant="Line"
x.propTypes=Object(o["a"])({},d["a"].propTypes)},eAGa:function(e,t,n){"use strict"
class o{constructor(e){this.handleAlert=e=>{if(null==this.alertFunc)throw new Error("Tried to alert without alertFunc being set first")
this.alertFunc(e)}
this.alertFunc=e}}t["a"]=new o},eHui:function(e,t,n){"use strict"
n.d(t,"a",(function(){return eo}))
n.d(t,"b",(function(){return to}))
var o=n("ODXe")
var i=n("VTBJ")
var r=n("Ff2n")
var a=n("q1tI")
var c=n.n(a)
var s=n("/MKj")
var l=n("QV6e")
const d="CHANGE_TAB"
const u="CHANGE_ACCORDION"
const x="RESET_UI"
const _="HIDE_SIDEBAR"
const m="SHOW_SIDEBAR"
function p(e){return{type:d,index:e}}function f(e){return{type:u,index:e}}const h="REQUEST_INITIAL_PAGE"
const y="REQUEST_PAGE"
const b="RECEIVE_PAGE"
const g="FAIL_PAGE"
function v(e,t){return{type:h,key:e,searchString:t}}function w(e){return{type:y,key:e}}function k(e,t){const n=t.links,o=t.bookmark
return{type:b,key:e,links:n,bookmark:o}}function C(e,t){return{type:g,key:e,error:t}}function O(e){return(t,n)=>{const o=n()
const i=o.source
return i.fetchLinks(e,o).then(n=>t(k(e,n))).catch(n=>t(C(e,n)))}}function E(e){return(t,n)=>{const o=n()
const i=o.collections[e]
if(i&&!i.isLoading){t(w(e))
return t(O(e))}}}function A(e){return(t,n)=>{const o=n()
const i=o.collections[e]
if(i&&!i.isLoading&&(0===i.links.length||i.searchString!==o.searchString)){t(v(e,o.searchString))
return t(O(e))}}}var S=n("0k/6")
var j=n("/rex")
const I="action.images.add_image"
const T="action.images.request_initial_images"
const L="action.images.request_images"
const B="action.images.receive_images"
const D="action.images.fail_images_load"
function R({id:e,filename:t,display_name:n,url:o,thumbnail_url:i},r){return{type:I,payload:{newImage:{id:e,filename:t,display_name:n,preview_url:o,thumbnail_url:i},contextType:r}}}function F(e){return{type:T,payload:{contextType:e}}}function M(e){return{type:L,payload:{contextType:e}}}function z({response:e,contextType:t,opts:n={}}){const o=e.files,i=e.bookmark,r=e.searchString
return{type:B,payload:{files:o.map(e=>N(e,n)),bookmark:i,contextType:t,searchString:r}}}function P({error:e,contextType:t}){return{type:D,payload:{error:e,contextType:t}}}const N=(e,t)=>{const n=Object(i["a"])({},e)
if(t.category===S["c"]){n[S["a"]]=true
n[S["b"]]=Object(j["a"])(e.download_url)}return n}
function U(e={}){const t=e.category
return(n,o)=>{const r=o()
return r.source.fetchImages(Object(i["a"])(Object(i["a"])({},r),{},{category:t})).then(t=>n(z({response:t,contextType:r.contextType,opts:e}))).catch(e=>n(P({error:e,contextType:r.contextType})))}}function $(e={}){return(t,n)=>{const o=n()
const i=o.images[o.contextType]
if(!(null!==i&&void 0!==i&&i.isLoading)&&null!==i&&void 0!==i&&i.hasMore){t(M(o.contextType))
return t(U(e))}}}function H(e={}){return(t,n)=>{const o=n()
t(F(o.contextType))
return t(U(e))}}var W=n("LixQ")
var q=n("n/1O")
const V="action.files.add_file"
const G="action.files.add_folder"
const K="action.files.receive_files"
const Z="action.files.insert_file"
const Y="action.files.receive_subfolders"
const J="action.files.request_files"
const X="action.files.request_subfolders"
const Q="action.files.toggle"
const ee="action.files.set_root"
function te(e){return{type:Q,id:e}}function ne({id:e,name:t,url:n,type:o,embed:i}){return{type:V,id:e,name:t,url:n,embed:i,fileType:o}}function oe(e){return{type:J,id:e}}function ie(e,t){return{type:K,id:e,fileIds:t.map(e=>e.id)}}function re(e,t){return{type:Z,id:e,fileId:t}}function ae(e,t){return(n,o)=>{const i=o(),r=i.source,a=i.folders
n(oe(e))
return r.fetchFiles(t||a[e].filesUrl).then(({files:t,bookmark:o})=>{n(t.map(ne).concat(ie(e,t)))
o&&n(ae(e,o))})}}function ce(e){return{type:G,id:e.id,name:e.name,parentId:e.parentId,filesUrl:e.filesUrl,foldersUrl:e.foldersUrl}}function se(e){return{type:X,id:e}}function le(e,t){return{type:Y,id:e,folderIds:t.map(e=>e.id)}}function de(e,t){return(n,o)=>{const i=o(),r=i.source,a=i.folders
n(se(e))
return r.fetchPage(t||a[e].foldersUrl).then(({folders:t,bookmark:o})=>{n(t.map(ce).concat(le(e,t,o)))
o&&n(de(e,o))})}}function ue(e){return(t,n)=>{t(te(e))
const o=n().folders[e]
if(!o.requested&&o.expanded){t(de(o.id))
t(ae(o.id))}}}var xe=n("s54W")
var _e=n("rCsd")
var me=n("kyQv")
var pe=n("qScw")
var fe=n("9dNb")
const he="COMPLETE_FILE_UPLOAD"
const ye="FAIL_FILE_UPLOAD"
const be="FAIL_FOLDERS_LOAD"
const ge="FAIL_MEDIA_UPLOAD"
const ve="MEDIA_UPLOAD_SUCCESS"
const we="PROCESSED_FOLDER_BATCH"
const ke="QUOTA_EXCEEDED_UPLOAD"
const Ce="RECEIVE_FOLDER"
const Oe="START_FILE_UPLOAD"
const Ee="START_LOADING"
const Ae="START_MEDIA_UPLOADING"
const Se="STOP_LOADING"
const je="STOP_MEDIA_UPLOADING"
const Ie="TOGGLE_UPLOAD_FORM"
function Te(){return{type:Ee}}function Le(){return{type:Se}}function Be({id:e,name:t,parentId:n}){return{type:Ce,id:e,name:t,parentId:n}}function De(e){return{type:be,error:e}}function Re(e){l["a"].showError(e)
return{type:ge,error:e}}function Fe(){return{type:ve}}function Me(e){return{type:Oe,file:e}}function ze(e){return{type:ye,error:e}}function Pe(e){return{type:ke,error:e}}function Ne(e){return{type:he,results:e}}function Ue(){return{type:Ie}}function $e({folders:e}){return{type:we,folders:e}}function He(e){return{type:Ae,payload:e}}function We(){return{type:je}}function qe(e){return t=>{t(He(e))
l["a"].insertImagePlaceholder(e)}}function Ve(e){return t=>{t(We())
l["a"].removePlaceholders(e)}}function Ge(e,t,n){const o=[]
o.push(Ne(e))
const i={id:e.id,name:e.display_name,url:e.preview_url,type:t.contentType,embed:Object(xe["a"])(e)}
o.push(ne(i))
o.push(re(t.parentFolderId,e.id));/^image\//.test(e["content-type"])&&o.push(R(e,n))
return o}function Ke(e,t){const n=Object(xe["a"])(e)
if("images"===t&&Object(me["d"])(n.type)&&"link"!==e.displayAs){var o,r
null===(o=l["a"].activeEditor())||void 0===o||null===(r=o.mceInstance())||void 0===r||r.selection.collapse()
const t={href:e.href||e.url,title:e.title,display_name:e.display_name||e.name||e.title||e.filename,alt_text:e.alt_text,isDecorativeImage:e.isDecorativeImage,content_type:e["content-type"],contextType:e.contextType,contextId:e.contextId,uuid:e.uuid}
l["a"].insertImage(t)}else if("media"===t&&Object(me["c"])(n.type)){var a,c
null===(a=l["a"].activeEditor())||void 0===a||null===(c=a.mceInstance())||void 0===c||c.selection.collapse()
l["a"].embedMedia({id:e.id,embedded_iframe_url:e.embedded_iframe_url,href:e.href||e.url,media_id:e.media_id,title:e.title,type:n.type,contextType:e.contextType,contextId:e.contextId,uuid:e.uuid})}else l["a"].insertLink({"data-canvas-previewable":Object(_e["a"])(e["content-type"]),href:e.href||e.url,title:e.alt_text||e.display_name||e.name||e.title||e.filename,content_type:e["content-type"],embed:Object(i["a"])(Object(i["a"])({},n),{},{disablePreview:true}),target:"_blank",contextType:e.contextType,contextId:e.contextId,uuid:e.uuid},false)
return e}function Ze(e){return(t,n)=>{t(Te())
const o=n(),i=o.source,r=o.jwt,a=o.upload,c=o.host,s=o.contextId,l=o.contextType
if(e||a.folders&&0===Object.keys(a.folders).length)return i.fetchFolders({jwt:r,host:c,contextId:s,contextType:l},e).then(({folders:e,bookmark:o})=>{t(e.map(Be))
const i=n(),r=i.upload
t($e(r))
t(o?Ze(o):Le())}).catch(e=>{t(De(e))})}}function Ye(e,t){const n=t||{},o=n.mediaObject,i=n.uploadedFile
return t=>{if(e){t(Re(e))
t(Ve(null===i||void 0===i?void 0:i.name))}else{const e={embedded_iframe_url:o.embedded_iframe_url,media_id:o.media_object.media_id,type:i.type,title:i.title||i.name}
t(Ve(i.name))
Ke(e,"media")
t(Fe())}}}function Je(){return(e,t)=>{const n=t(),o=n.source
if(!l["a"].mediaServerSession)return o.mediaServerSession().then(e=>{l["a"].setMediaServerSession(e)})}}function Xe(e,t={}){return(n,o)=>{const i=o(),r=i.source,a=i.jwt,c=i.host,s=i.contextId,l=i.contextType
const d=t.onDuplicate
const u=new File([e.domElement.outerHTML],e.name,{type:"image/svg+xml"})
const x={file:{name:e.name,type:"image/svg+xml"},name:e.name}
return r.fetchButtonsAndIconsFolder({jwt:a,host:c,contextId:s,contextType:l}).then(({folders:e})=>{x.parentFolderId=e[0].id
return r.preflightUpload(x,{host:c,contextId:s,contextType:l,onDuplicate:d,category:S["c"]}).then(e=>r.uploadFRD(u,e))})}}function Qe(e,t){return(n,o)=>{var r
const a=l["a"].activeEditor()
const c=null===a||void 0===a||null===(r=a.editor)||void 0===r?void 0:r.selection.getBookmark(2,true)
n(qe(t))
const s=o(),d=s.source,u=s.jwt,x=s.host,_=s.contextId,m=s.contextType
if("media"===e&&t.domObject)return Object(W["a"])(t.domObject,{contextId:_,contextType:m,origin:Object(q["c"])(x),headers:Object(q["b"])(u)},(e,t)=>{n(Ye(e,t))})
return d.fetchMediaFolder({jwt:u,host:x,contextId:_,contextType:m}).then(({folders:o})=>{t.parentFolderId=o[0].id
t.domObject&&delete t.domObject.preview
n(at(e,Object(i["a"])(Object(i["a"])({},t),{},{bookmark:c})))}).catch(e=>{n(Ve(t.name))
console.error("Fetching the media folder failed.",e)})}}function et(e,t,n){const o=t.usageRights
o&&e.setUsageRights(n.id,o)
return n}function tt(e,t){if(t.href||t.url)return Promise.resolve(t)
return e.getFile(t.id).then(e=>{t.url=e.url
return t})}function nt(e,t=new FileReader){return new Promise((n,o)=>{t.onerror=()=>{t.abort()
o(new DOMException("Unable to parse file"))}
t.onload=()=>{n(t.result)}
t.readAsDataURL(e)})}function ot(e,t,n){return/^image\//.test(e["content-type"])?nt(t,n).then(t=>{e.thumbnail_url=t
return e}):Promise.resolve(e)}function it(e,t){e&&(t.alt_text=e)
return t}function rt(e,t){if(e&&e.response)return e.response.json().then(n=>{"file size exceeds quota"===n.message?t(Pe(e)):t(ze(e))}).catch(e=>t(ze(e)))
if(e)return Promise.resolve().then(()=>t(ze(e)))}function at(e,t){return(n,o)=>{const r=o(),a=r.source,c=r.jwt,s=r.host,d=r.contextId,u=r.contextType
const x=t.fileReader
n(Me(t))
return(async e=>{const t=await fe["a"](e.domObject)
return null===t||void 0===t?void 0:t.category})(t).then(o=>a.preflightUpload(t,{jwt:c,host:s,contextId:d,contextType:u,category:o}).then(e=>a.uploadFRD(t.domObject,e)).then(e=>et(a,t,e)).then(e=>tt(a,e)).then(e=>Object(pe["b"])(u,d,e)).then(e=>ot(e,t.domObject,x)).then(e=>it(t.altText,e)).then(e=>{t.isDecorativeImage&&(e.isDecorativeImage=t.isDecorativeImage)
t.displayAs&&(e.displayAs=t.displayAs)
return e}).then(e=>{n(Ve(t.name))
return e}).then(n=>{let o
const r=l["a"].activeEditor()
if(t.bookmark){o=r.editor.selection.getBookmark(2,true)
r.editor.selection.moveToBookmark(t.bookmark)}const a=Ke(Object(i["a"])({contextType:u,contextId:d},n),e)
t.bookmark&&r.editor.selection.moveToBookmark(o)
return a}).then(e=>{n(Ge(e,t,u))}).catch(e=>{n(Ve(t.name))
rt(e,n)}))}}const ct="START_FLICKR_SEARCH"
const st="RECEIVE_FLICKR_RESULTS"
const lt="FAIL_FLICKR_SEARCH"
const dt="TOGGLE_FLICKR_FORM"
function ut(e){return{type:ct,term:e}}function xt(e){return{type:st,results:e}}function _t(e){return{type:lt,error:e}}function mt(){return{type:dt}}function pt(e){return(t,n)=>{const o=n(),i=o.source,r=o.host,a=o.flickr
if(a&&!a.searching){t(ut(e))
return i.searchFlickr(e,{host:r}).then(e=>t(xt(e))).catch(e=>t(_t(e)))}}}const ft="TOGGLE_NEWPAGE_FORM"
function ht(){return{type:ft}}const yt="REQUEST_INITIAL_DOCS"
const bt="REQUEST_NEXT_DOCS"
const gt="RECEIVE_DOCS"
const vt="FAIL_DOCS"
function wt(e){return{type:yt,payload:{contextType:e}}}function kt(e){return{type:bt,payload:{contextType:e}}}function Ct({response:e,contextType:t,contextId:n}){const o=e.files,i=e.bookmark
return{type:gt,payload:{files:o,bookmark:i,contextType:t,contextId:n}}}function Ot({error:e,contextType:t}){return{type:vt,payload:{error:e,contextType:t}}}function Et(){return(e,t)=>{const n=t()
return n.source.fetchDocs(n).then(t=>e(Ct({response:t,contextType:n.contextType,contextId:n.contextId}))).catch(t=>e(Ot({error:t,contextType:n.contextType})))}}function At(){return(e,t)=>{const n=t()
const o=n.documents[n.contextType]
if(!(null!==o&&void 0!==o&&o.isLoading)&&null!==o&&void 0!==o&&o.hasMore){e(kt(n.contextType))
return e(Et())}}}function St(){return(e,t)=>{const n=t()
e(wt(n.contextType))
return e(Et())}}var jt=n("eAGa")
var It=n("NFDp")
const Tt="REQUEST_INITIAL_MEDIA"
const Lt="REQUEST_MEDIA"
const Bt="RECEIVE_MEDIA"
const Dt="FAIL_MEDIA"
function Rt(e){return{type:Tt,payload:{contextType:e}}}function Ft(e){return{type:Lt,payload:{contextType:e}}}function Mt({response:e,contextType:t}){const n=e.files,o=e.bookmark
return{type:Bt,payload:{files:n,bookmark:o,contextType:t}}}function zt({error:e,contextType:t}){return{type:Dt,payload:{error:e,contextType:t}}}function Pt(){return(e,t)=>{const n=t()
e(Ft(n.contextType))
return n.source.fetchMedia(n).then(t=>e(Mt({response:t,contextType:n.contextType}))).catch(t=>e(zt({error:t,contextType:n.contextType})))}}function Nt(){return(e,t)=>{const n=t()
const o=n.media[n.contextType]
if(!(null!==o&&void 0!==o&&o.isLoading)&&null!==o&&void 0!==o&&o.hasMore){e(Ft(n.contextType))
return e(Pt())}}}function Ut(){return(e,t)=>{const n=t()
e(Rt(n.contextType))
return e(Pt())}}function $t({media_object_id:e,title:t,subtitles:n}){return(o,i)=>{const r=i()
const a=r.source.updateMediaObject(r,{media_object_id:e,title:t}).catch(e=>{jt["a"].handleAlert({text:Object(It["a"])("Though your video will have the correct title in the browser, we failed to update it in the database."),variant:"error"})
throw e})
const c=r.source.updateClosedCaptions(r,{media_object_id:e,subtitles:n})
return Promise.all([a,c])}}const Ht="CHANGE_CONTEXT"
const Wt="CHANGE_CONTEXT_TYPE"
const qt="CHANGE_CONTEXT_ID"
const Vt="CHANGE_SEARCH_STRING"
const Gt="CHANGE_SORT_BY"
function Kt({contextType:e,contextId:t}){return n=>{n(Zt(e))
n(Yt(t))
n({type:Ht,payload:{contextType:e,contextId:t}})}}function Zt(e){return{type:Wt,payload:e}}function Yt(e){return{type:qt,payload:e}}function Jt(e){return{type:Vt,payload:e}}function Xt(e){return{type:Gt,payload:e}}const Qt="ALL_FILES_LOADING"
function en(e){return{type:Qt,payload:e}}const tn="action.session.receive_session"
function nn(e){return{type:tn,data:e}}function on(e,t){var n
const o=t(),i=o.source
return null===(n=i.getSession)||void 0===n?void 0:n.call(i).then(t=>e(nn(t)))}const rn="uncategorized"
function an(e){return{loadSession:()=>e(on),onChangeTab:t=>e(p(t)),onChangeAccordion:t=>e(f(t)),fetchInitialPage:t=>e(A(t)),fetchNextPage:t=>e(E(t)),toggleFolder:t=>e(ue(t)),fetchFolders:()=>e(Ze()),fetchInitialImages:(t={category:rn})=>e(H(t)),fetchNextImages:(t={category:rn})=>e($(t)),startUpload:(t,n)=>e(at(t,n)),flickrSearch:t=>e(pt(t)),toggleFlickrForm:()=>e(mt()),toggleUploadForm:()=>e(Ue()),toggleNewPageForm:()=>e(ht()),startButtonsAndIconsUpload:(t,n)=>e(Xe(t,n)),startMediaUpload:(t,n)=>e(Qe(t,n)),createMediaServerSession:()=>e(Je()),mediaUploadComplete:(t,n)=>e(Ye(t,n)),fetchInitialDocs:()=>e(St()),fetchNextDocs:()=>e(At()),fetchInitialMedia:()=>e(Ut()),fetchNextMedia:()=>e(Nt()),updateMediaObject:t=>e($t(t)),onChangeContext:t=>e(Kt(t)),onChangeSearchString:t=>e(Jt(t)),onChangeSortBy:t=>e(Xt(t)),onAllFilesLoading:t=>e(en(t))}}function cn(e){const t=e.ui,n=e.containingContext,o=e.contextType,r=e.contextId,a=e.files,c=e.images,s=e.documents,l=e.media,d=e.folders,u=e.rootFolderId,x=e.flickr,_=e.upload,m=e.session,p=e.newPageLinkExpanded,f=e.all_files,h=e.jwt,y=e.host,b=e.source
const g={}
for(const t in e.collections){const n=e.collections[t]
g[t]=n}return Object(i["a"])(Object(i["a"])({containingContext:n,contextType:o,contextId:r,collections:g,files:a,images:c,documents:s,media:l,folders:d,rootFolderId:u,flickr:x,upload:_,session:m,newPageLinkExpanded:p},t),{},{all_files:f,jwt:h,host:y,source:b})}var sn=n("ANjH")
var ln=function(e=""){return e}
function dn(e=false,t){switch(t.type){case _:return true
case x:case m:return false
default:return e}}function un(e=0,t){switch(t.type){case x:return 0
case d:return t.index
default:return e}}function xn(e="",t){switch(t.type){case x:case d:return""
case u:return t.index
default:return e}}var _n=Object(sn["combineReducers"])({hidden:dn,selectedTabIndex:un,selectedAccordionIndex:xn})
var mn=function(e={},t){switch(t.type){case h:return Object(i["a"])(Object(i["a"])({},e),{},{links:[],bookmark:null,isLoading:true,hasMore:true,searchString:t.searchString})
case y:return Object(i["a"])(Object(i["a"])({},e),{},{isLoading:true})
case b:return Object(i["a"])(Object(i["a"])({},e),{},{links:e.links.concat(t.links),bookmark:t.bookmark,isLoading:false,hasMore:!!t.bookmark})
case g:{const n={isLoading:false,error:t.error}
0===e.links.length&&(n.bookmark=null)
return Object(i["a"])(Object(i["a"])({},e),n)}default:return e}}
function pn(e){return function(t={},n){switch(n.type){case h:case y:case b:case g:return n.key===e?mn(t,n):t
default:return t}}}var fn=Object(sn["combineReducers"])({announcements:pn("announcements"),assignments:pn("assignments"),discussions:pn("discussions"),modules:pn("modules"),quizzes:pn("quizzes"),wikiPages:pn("wikiPages")})
function hn(e={},t){switch(t.type){case V:return Object(i["a"])(Object(i["a"])({},e),{},{[t.id]:{id:t.id,name:t.name,type:t.fileType,url:t.url,embed:t.embed}})
default:return e}}const yn={id:null,name:null,loadingCount:0,loading:false,requested:false,expanded:false,filesUrl:null,foldersUrl:null,parentId:null,fileIds:[],folderIds:[]}
function bn(e=yn,t){let n
switch(t.type){case G:return Object(i["a"])(Object(i["a"])({},e),{},{id:t.id,name:t.name,parentId:t.parentId,filesUrl:t.filesUrl,foldersUrl:t.foldersUrl})
case K:n=e.loadingCount-1
return Object(i["a"])(Object(i["a"])({},e),{},{loadingCount:n,loading:!!n,fileIds:e.fileIds.concat(t.fileIds)})
case Z:return Object(i["a"])(Object(i["a"])({},e),{},{fileIds:e.fileIds.concat(t.fileId)})
case Y:n=e.loadingCount-1
return Object(i["a"])(Object(i["a"])({},e),{},{loadingCount:n,loading:!!n,folderIds:e.folderIds.concat(t.folderIds)})
case J:case X:n=e.loadingCount+1
return Object(i["a"])(Object(i["a"])({},e),{},{requested:true,loadingCount:n,loading:!!n})
case Q:return Object(i["a"])(Object(i["a"])({},e),{},{expanded:!e.expanded})
default:return e}}function gn(e={},t){switch(t.type){case G:case K:case Z:case Y:case J:case X:case Q:return Object(i["a"])(Object(i["a"])({},e),{},{[t.id]:bn(e[t.id],t)})
default:return e}}function vn(e=null,t){switch(t.type){case ee:return t.id
default:return e}}function wn(e={},t){const n=t.payload&&t.payload.contextType
const o=Object(i["a"])({},e)
n&&!o[n]&&(o[n]={files:[],bookmark:null,isLoading:false,hasMore:true})
switch(t.type){case I:{const e=t.payload.newImage,i=e.id,r=e.filename,a=e.display_name,c=e.href,s=e.preview_url,l=e.thumbnail_url
o[n]={files:o[n].files.concat({id:i,filename:r,display_name:a,preview_url:s,thumbnail_url:l,href:s||c})}
return o}case T:o[n]={files:[],bookmark:null,isLoading:true,hasMore:true}
return o
case L:o[n].isLoading=true
return o
case B:t.payload.searchString===o.searchString&&(o[n]={files:o[n].files.concat(t.payload.files),isLoading:false,bookmark:t.payload.bookmark,hasMore:!!t.payload.bookmark})
return o
case D:o[n]={isLoading:false,error:t.payload.error,files:[]}
t.payload.files&&0===t.payload.files.length&&(o[n].bookmark=null)
return o
case Ht:return o
case Vt:o.searchString=t.payload
return o
default:return e}}function kn(e={},t){const n=t.payload&&t.payload.contextType
const o=Object(i["a"])({},e)
n&&!o[n]&&(o[n]={files:[],bookmark:null,isLoading:false,hasMore:true})
switch(t.type){case yt:o[n]={files:[],bookmark:null,isLoading:true,hasMore:true}
return o
case bt:o[n].isLoading=true
return o
case gt:o[n]={files:o[n].files.concat(t.payload.files),bookmark:t.payload.bookmark,isLoading:false,hasMore:!!t.payload.bookmark}
return o
case vt:o[n]={isLoading:false,error:t.payload.error}
t.payload.files&&0===t.payload.files.length&&(o[n].bookmark=null)
return o
case Ht:case Vt:return o
default:return e}}function Cn(e={},t){const n=t.payload&&t.payload.contextType
const o=Object(i["a"])({},e)
n&&!o[n]&&(o[n]={files:[],bookmark:null,isLoading:false,hasMore:true})
switch(t.type){case Tt:o[n]={files:[],bookmark:null,isLoading:true,hasMore:true}
return o
case Lt:o[n].isLoading=true
return o
case Bt:o[n]={files:o[n].files.concat(t.payload.files),bookmark:t.payload.bookmark,isLoading:false,hasMore:!!t.payload.bookmark}
return o
case Dt:o[n]={isLoading:false,error:t.payload.error}
t.payload.files&&0===t.payload.files.length&&(o[n].bookmark=null)
return o
case Ht:case Vt:return o
default:return e}}function On(e=false,t){switch(t.type){case Oe:return true
case ye:case he:case ke:return false
default:return e}}function En(e={},t){switch(t.type){case he:return{}
case ke:return Object(i["a"])(Object(i["a"])({},e),{},{type:t.type})
default:return e}}function An(e=false,t){switch(t.type){case he:return false
case Ie:return!e
default:return e}}function Sn(e={},t){switch(t.type){case Ce:return Object(i["a"])(Object(i["a"])({},e),{},{[t.id]:{id:t.id,name:t.name,parentId:t.parentId}})
case be:default:return e}}function jn(e=null,t){switch(t.type){case Ce:return null===t.parentId?t.id:e
default:return e}}function In(e={},t){switch(t.type){case we:{const e=t.folders
const n={}
for(const t in e){const o=e[t]
n[o.id]=n[o.id]||[]
if(o.parentId){n[o.parentId]=n[o.parentId]||[]
n[o.parentId].push(o.id)}}for(const t in n){const o=n[t]
o.sort((t,n)=>e[t].name.localeCompare(e[n].name))}return n}default:return e}}function Tn(e=false,t){switch(t.type){case Ee:return true
case Se:case be:return false
default:return e}}function Ln(e=false,t){switch(t.type){case Ee:return{loading:true,uploaded:false,error:false}
case ge:return{loading:false,uploaded:false,error:true}
case ve:return{loading:false,uploaded:true,error:false}
default:return e}}var Bn=Object(sn["combineReducers"])({uploading:On,formExpanded:An,folders:Sn,rootFolderId:jn,folderTree:In,error:En,loadingFolders:Tn,uploadingMediaStatus:Ln})
var Dn=function(e={},t){switch(t.type){case ct:return Object(i["a"])(Object(i["a"])({},e),{},{searching:true,searchTerm:t.term})
case st:return Object(i["a"])(Object(i["a"])({},e),{},{searching:false,searchResults:t.results})
case lt:return Object(i["a"])(Object(i["a"])({},e),{},{searching:false,searchTerm:"",searchResults:[]})
case dt:return Object(i["a"])(Object(i["a"])({},e),{},{formExpanded:!e.formExpanded})
default:return e}}
const Rn={}
function Fn(e=Rn,t){switch(t.type){case tn:return Object(i["a"])(Object(i["a"])({},e),t.data)
default:return e}}var Mn=function(e=false,t){switch(t.type){case ft:return!e
default:return e}}
function zn(e="",t){if(t.type===Wt)return t.payload
return e}function Pn(e="",t){if(t.type===qt)return t.payload
return e}function Nn(e="",t){if(t.type===Vt)return t.payload
return e}function Un(e={order:"desc",sort:"date_added"},t){if(t.type===Gt)return t.payload
return e}function $n(e={},t){if(t.type===Qt)return Object(i["a"])(Object(i["a"])({},e),{},{isLoading:t.payload})
return e}var Hn=Object(sn["combineReducers"])({ui:_n,source:ln,jwt:ln,host:ln,containingContext:ln,contextType:zn,contextId:Pn,searchString:Nn,sortBy:Un,all_files:$n,collections:fn,files:hn,folders:gn,rootFolderId:vn,images:wn,documents:kn,media:Cn,upload:Bn,flickr:Dn,session:Fn,newPageLinkExpanded:Mn})
function Wn(e){switch(e){case"course":case"courses":return"course"
case"group":case"groups":return"group"
case"user":case"users":return"user"
default:return}}var qn=function(e={}){let t=e,n=t.source,o=t.jwt,r=t.refreshToken,a=t.host,c=t.contextType,s=t.contextId,l=t.collections,d=t.files,u=t.folders,x=t.upload,_=t.images,m=t.documents,p=t.media,f=t.flickr,h=t.newPageLinkExpanded,y=t.searchString,b=t.sortBy,g=t.all_files
c=Wn(c)
e=Object(i["a"])(Object(i["a"])({},e),{},{contextType:c})
void 0===y&&(y="")
void 0===g&&(g={isLoading:false})
b||(b={})
b=Object(i["a"])({sort:"date_added",dir:"desc"},b)
null==n&&(n=new q["a"]({jwt:o,refreshToken:r,host:a}))
void 0===l&&(l={announcements:n.initializeCollection("announcements",e),assignments:n.initializeCollection("assignments",e),discussions:n.initializeCollection("discussions",e),modules:n.initializeCollection("modules",e),quizzes:n.initializeCollection("quizzes",e),wikiPages:n.initializeCollection("wikiPages",e)})
void 0===x&&(x=n.initializeUpload(e))
void 0===f&&(f=n.initializeFlickr(e))
void 0===_&&(_=n.initializeImages(e))
void 0===m&&(m=n.initializeDocuments(e))
void 0===p&&(p=n.initializeMedia(e))
void 0===h&&(h=false)
const v={selectedAccordionIndex:function(){try{return window.sessionStorage.getItem("canvas_rce_links_accordion_index")}catch(e){return}}()}
return{ui:v,source:n,jwt:o,host:a,contextType:c,contextId:s,collections:l,files:d,folders:u,upload:x,images:_,documents:m,media:p,flickr:f,newPageLinkExpanded:h,searchString:y,sortBy:b,all_files:g}}
var Vn=n("sINF")
var Gn=n("FkO2")
var Kn=function(e,t){const n=Object(sn["createStore"])(Object(Gn["batching"])(Hn),t||qn(e),Object(sn["applyMiddleware"])(Vn["a"],Gn["batch"]))
n.subscribe(()=>{try{const e=n.getState().ui.selectedAccordionIndex
e!==window.sessionStorage.getItem("canvas_rce_links_accordion_index")&&window.sessionStorage.setItem("canvas_rce_links_accordion_index",e)}catch(e){}})
return n}
const Zn=["children"],Yn=["children"]
function Jn(e){let t=e.children,n=Object(r["a"])(e,Zn)
return t(Object(i["a"])({onLinkClick:l["a"].insertLink,onImageEmbed:l["a"].embedImage,onMediaEmbed:l["a"].embedMedia,onFileSelect:l["a"].insertFileLink},n))}const Xn=Object(s["b"])(cn,an)(Jn)
const Qn=Object(a["createContext"])()
function eo(e){let t=e.children,n=Object(r["a"])(e,Yn)
const i=Object(a["useState"])(()=>Kn(n)),l=Object(o["a"])(i,1),d=l[0]
return c.a.createElement(s["a"],{store:d},c.a.createElement(Xn,null,e=>c.a.createElement(Qn.Provider,{value:e},t(e))))}function to(){const e=Object(a["useContext"])(Qn)
if(!e)throw new Error("useStoreProps should be used within a StoreProvider")
return e}},eIUg:function(e,t,n){"use strict"
n.d(t,"a",(function(){return x}))
var o=n("VTBJ")
var i=n("1OyB")
var r=n("vuIU")
var a=n("Ji7U")
var c=n("LK+K")
var s=n("q1tI")
var l=n.n(s)
var d=n("hPGw")
var u=l.a.createElement("path",{d:"M1813.33333,1557.19467 C1255.57333,1684.02133 664.853333,1684.02133 106.666667,1557.19467 L106.666667,468.448 C664.426667,341.621333 1255.14667,341.514667 1813.33333,468.448 L1813.33333,1557.19467 Z M1879.04,374.261333 C1278.72,230.688 640.64,230.794667 40.96,374.261333 L0,384.074667 L0,1641.568 L40.96,1651.38133 C341.013333,1723.168 650.24,1759.43467 960,1759.43467 C1269.86667,1759.43467 1579.2,1723.168 1879.04,1651.38133 L1920,1641.568 L1920,384.074667 L1879.04,374.261333 Z M853.333333,786.986667 L1229.65333,1012.8 L853.333333,1238.61333 L853.333333,786.986667 Z M746.666667,1426.98667 L1437.01333,1012.8 L746.666667,598.613333 L746.666667,1426.98667 Z",fillRule:"evenodd",stroke:"none",strokeWidth:"1"})
var x=function(e){Object(a["a"])(n,e)
var t=Object(c["a"])(n)
function n(){Object(i["a"])(this,n)
return t.apply(this,arguments)}Object(r["a"])(n,[{key:"render",value:function(){return l.a.createElement(d["a"],Object.assign({},this.props,{name:"IconVideo",viewBox:"0 0 1920 1920"}),u)}}])
n.displayName="IconVideoLine"
return n}(s["Component"])
x.glyphName="video"
x.variant="Line"
x.propTypes=Object(o["a"])({},d["a"].propTypes)},hlkS:function(e,t,n){"use strict"
n.d(t,"b",(function(){return r}))
n.d(t,"d",(function(){return a}))
n.d(t,"e",(function(){return c}))
n.d(t,"c",(function(){return s}))
n.d(t,"a",(function(){return _}))
n.d(t,"h",(function(){return m}))
n.d(t,"k",(function(){return p}))
n.d(t,"f",(function(){return g}))
n.d(t,"g",(function(){return v}))
n.d(t,"j",(function(){return w}))
n.d(t,"i",(function(){return k}))
var o=n("ODXe")
var i=n("NFDp")
n("HoBo")
const r=10
const a=10
const c=320
const s=10
const l="small"
const d="medium"
const u="large"
const x="extra-large"
const _="custom"
const m=["small","medium","large","extra-large","custom"]
const p=["medium","large","extra-large","custom"]
const f={200:"small",320:"medium",400:"large",640:"extra-large"}
function h(e,t){const n=e.hasAttribute(t)?e.getAttribute(t):e[t]
return n?Math.round(Number.parseInt(n,10)):null}function y(e){const t=e.appliedWidth||e.naturalWidth
const n=e.appliedHeight||e.naturalHeight
const o=Math.max(t,n)
return f[o]||_}function b(e){const t=t=>e.hasAttribute(t)?e.getAttribute(t):e[t]
const n=t("width")
const o=t("height")
const i=[n,o].find(e=>/\d+(?:\.\d+)?%/.test(e))
return i?Math.round(Number.parseInt(i,10)):null}function g(e){const t=e.getAttribute("alt")
const n=b(e)
const o={appliedWidth:h(e,"width"),appliedHeight:h(e,"height"),naturalWidth:e.naturalWidth,naturalHeight:e.naturalHeight,appliedPercentage:n||100,usePercentageUnits:!!n,altText:t||"",isDecorativeImage:null!==t&&""===t.replace(/\s/g,""),url:e.src}
o.imageSize=y(o)
return o}function v(e){let t=null
let n
let o,r
const a="IFRAME"===e.tagName?e:e.firstElementChild
const c=a.parentElement
if("IFRAME"===a.tagName){n=a.contentDocument
n&&(t=n.querySelector("video"))
if(t&&(t.loadedmetadata||t.readyState>=1)){o=t.videoWidth
r=t.videoHeight}}const s=(a.getAttribute("title")||c.getAttribute("data-mce-p-title")||"").replace(Object(i["a"])("Video player for "),"")
const l=e.getBoundingClientRect()
const d={titleText:s||"",appliedHeight:l.height,appliedWidth:l.width,naturalHeight:r,naturalWidth:o,source:t&&t.querySelector("source")}
try{var u
const e=null===(u=n.querySelector("[data-tracks]"))||void 0===u?void 0:u.getAttribute("data-tracks")
e&&(d.tracks=JSON.parse(e))}catch(e){}d.videoSize=y(d)
return d}function w(e,t,n){if(e===_)return{width:t,height:n}
const i=Object.entries(f).find(([,t])=>t===e),r=Object(o["a"])(i,1),a=r[0]
const c=a/Math.max(t,n)
return{height:Math.round(n*c),width:Math.round(t*c)}}function k(e){switch(e){case l:return Object(i["a"])("Small")
case d:return Object(i["a"])("Medium")
case u:return Object(i["a"])("Large")
case x:return Object(i["a"])("Extra Large")
default:return Object(i["a"])("Custom")}}},jtOZ:function(e,t,n){"use strict"
n.d(t,"a",(function(){return x}))
var o=n("VTBJ")
var i=n("1OyB")
var r=n("vuIU")
var a=n("Ji7U")
var c=n("LK+K")
var s=n("q1tI")
var l=n.n(s)
var d=n("hPGw")
var u=l.a.createElement("g",{fillRule:"evenodd",stroke:"none",strokeWidth:"1"},l.a.createElement("path",{d:"M1251.65412,1.13686838e-13 C1296.15294,1.13686838e-13 1339.86118,18.0705882 1371.37176,49.5811765 L1371.37176,49.5811765 L1700.59529,378.804706 C1732.55765,410.767059 1750.17647,453.345882 1750.17647,498.522353 L1750.17647,498.522353 L1750.17647,1920 L169,1920 L169,1.13686838e-13 Z M1185.47059,112.941176 L281.941176,112.941176 L281.941176,1807.05882 L1637.23529,1807.05882 L1637.23529,564.705882 L1185.47059,564.705882 L1185.47059,112.941176 Z M1298.41176,136.32 L1298.41176,451.764706 L1613.85647,451.764706 L1298.41176,136.32 Z"}),l.a.createElement("path",{d:"M900.497412,677.669647 C927.264471,677.669647 950.869176,690.319059 968.488,715.504941 C1010.38918,774.573176 1007.45271,837.481412 991.979765,922.187294 C986.671529,951.326118 992.092706,980.803765 1008.24329,1005.312 C1031.05741,1040.09788 1063.92329,1087.98494 1096.22447,1128.53082 C1119.94212,1158.46024 1156.42212,1174.38494 1193.35388,1169.41553 C1217.07153,1166.14024 1245.64565,1163.42965 1275.01035,1163.42965 C1406.02212,1163.42965 1396.19624,1210.18729 1408.05506,1253.10494 C1414.60565,1279.08141 1411.33035,1301.78259 1397.89035,1318.61082 C1381.17506,1341.312 1346.728,1353.05788 1296.35624,1353.05788 C1240.56329,1353.05788 1222.15388,1343.57082 1173.58918,1328.09788 C1146.14447,1319.28847 1117.68329,1317.48141 1089.89976,1324.82259 C1034.44565,1339.27906 942.963294,1361.30259 866.615059,1371.80612 C825.843294,1377.45318 788.798588,1398.46024 764.177412,1432.68141 C708.723294,1509.48141 657.335059,1581.19906 575.904471,1581.19906 C554.897412,1581.19906 535.584471,1573.632 519.659765,1558.49788 C496.168,1535.00612 486.116235,1508.91671 491.085647,1478.64847 C504.864471,1385.69788 619.160941,1333.85788 687.151529,1296.02259 C703.189176,1287.10024 715.838588,1273.43435 723.744471,1256.49318 L723.744471,1256.49318 L831.603294,1023.26965 C839.283294,1006.89318 841.655059,988.709647 838.831529,970.752 C826.295059,891.693176 807.772706,758.761412 857.579765,698.676706 C868.535059,685.236706 883.669176,677.669647 900.497412,677.669647 Z M921.052706,1017.62259 C877.796235,1144.22965 801.335059,1281.90494 791.057412,1297.94259 C883.330353,1254.57318 1066.97271,1232.66259 1066.97271,1232.66259 C974.586824,1143.66494 921.052706,1017.62259 921.052706,1017.62259 Z"}))
var x=function(e){Object(a["a"])(n,e)
var t=Object(c["a"])(n)
function n(){Object(i["a"])(this,n)
return t.apply(this,arguments)}Object(r["a"])(n,[{key:"render",value:function(){return l.a.createElement(d["a"],Object.assign({},this.props,{name:"IconPdf",viewBox:"0 0 1920 1920"}),u)}}])
n.displayName="IconPdfLine"
return n}(s["Component"])
x.glyphName="pdf"
x.variant="Line"
x.propTypes=Object(o["a"])({},d["a"].propTypes)},"k3+9":function(e,t,n){"use strict"
n.d(t,"a",(function(){return o}))
function o(e){const t=new Promise((t,o)=>{n.e(27).then(n.t.bind(null,"9Uei",7)).then(()=>{let i
switch(e){case"ar":i=n.e(4218).then(n.bind(null,"venI"))
break
case"ca":i=n.e(4219).then(n.bind(null,"1Y6O"))
break
case"cy":i=n.e(4220).then(n.bind(null,"we+z"))
break
case"da":i=n.e(4222).then(n.bind(null,"PTiq"))
break
case"da-x-k12":i=n.e(4221).then(n.bind(null,"yNIZ"))
break
case"de":i=n.e(4223).then(n.bind(null,"S8cF"))
break
case"el":i=n.e(4224).then(n.bind(null,"FwcW"))
break
case"en":i=n.e(4339).then(n.bind(null,"NQfO"))
break
case"en-AU-x-unimelb":i=n.e(4225).then(n.bind(null,"3W0S"))
break
case"en-GB-x-ukhe":i=n.e(4226).then(n.bind(null,"KQzV"))
break
case"en-AU":i=n.e(4227).then(n.bind(null,"voS+"))
break
case"en-CA":i=n.e(4340).then(n.bind(null,"m+Mn"))
break
case"en-CY":i=n.e(4341).then(n.bind(null,"mgnU"))
break
case"en-GB":i=n.e(4228).then(n.bind(null,"nxzM"))
break
case"es":i=n.e(4229).then(n.bind(null,"2MaM"))
break
case"es-ES":i=n.e(4230).then(n.bind(null,"HM1o"))
break
case"fa-IR":i=n.e(4231).then(n.bind(null,"01hr"))
break
case"fi":i=n.e(4232).then(n.bind(null,"QFVQ"))
break
case"fr":i=n.e(4233).then(n.bind(null,"8o6s"))
break
case"fr-CA":i=n.e(4234).then(n.bind(null,"Bm8W"))
break
case"he":i=n.e(4235).then(n.bind(null,"mYM8"))
break
case"ht":i=n.e(4342).then(n.bind(null,"ZkKP"))
break
case"hu":i=n.e(4236).then(n.bind(null,"sbbs"))
break
case"hy":i=n.e(4237).then(n.bind(null,"WoYt"))
break
case"is":i=n.e(4343).then(n.bind(null,"/C+o"))
break
case"it":i=n.e(4238).then(n.bind(null,"Qvrh"))
break
case"ja":i=n.e(4239).then(n.bind(null,"XZYX"))
break
case"ko":i=n.e(4240).then(n.bind(null,"vrKU"))
break
case"mi":i=n.e(4344).then(n.bind(null,"LP6z"))
break
case"nb":i=n.e(4242).then(n.bind(null,"Uc+e"))
break
case"nb-x-k12":i=n.e(4241).then(n.bind(null,"56N6"))
break
case"nl":i=n.e(4243).then(n.bind(null,"17Or"))
break
case"nn":i=n.e(4244).then(n.bind(null,"HZtm"))
break
case"pl":i=n.e(4245).then(n.bind(null,"JcWQ"))
break
case"pt":i=n.e(4246).then(n.bind(null,"I9Ke"))
break
case"pt-BR":i=n.e(4247).then(n.bind(null,"7P9b"))
break
case"ru":i=n.e(4248).then(n.bind(null,"V5X0"))
break
case"se":i=n.e(4345).then(n.bind(null,"JKpP"))
break
case"sl":i=n.e(4249).then(n.bind(null,"h8aU"))
break
case"sv":i=n.e(4251).then(n.bind(null,"lfo/"))
break
case"sv-x-k12":i=n.e(4250).then(n.bind(null,"4MO5"))
break
case"th":i=n.e(4252).then(n.bind(null,"TDbP"))
break
case"tr":i=n.e(4253).then(n.bind(null,"V0pu"))
break
case"uk-UA":i=n.e(4254).then(n.bind(null,"yL5t"))
break
case"vi":i=n.e(4255).then(n.bind(null,"rGya"))
break
case"zh":i=n.e(4258).then(n.bind(null,"Sx0h"))
break
case"zh-Hans":i=n.e(4256).then(n.bind(null,"32vL"))
break
case"zh-Hant":i=n.e(4257).then(n.bind(null,"Iyx8"))
break
case"zh-HK":i=n.e(4259).then(n.bind(null,"v1QM"))
break
default:i=Promise.resolve(null)}i.then(t).catch(o)}).catch(()=>{throw new Error("Failed loading tinymce.")})})
return t}},kyQv:function(e,t,n){"use strict"
n.d(t,"a",(function(){return v}))
n.d(t,"d",(function(){return w}))
n.d(t,"c",(function(){return k}))
n.d(t,"f",(function(){return C}))
n.d(t,"b",(function(){return O}))
n.d(t,"e",(function(){return E}))
n.d(t,"g",(function(){return A}))
var o=n("CxY0")
var i=n("eIUg")
var r=n("VTBJ")
var a=n("1OyB")
var c=n("vuIU")
var s=n("Ji7U")
var l=n("LK+K")
var d=n("q1tI")
var u=n.n(d)
var x=n("hPGw")
var _=u.a.createElement("path",{d:"M1129.4317,113 L1129.4317,1807.14754 L936.637705,1807.14754 L484.865027,1355.37487 L169.414754,1355.37487 C76.0107531,1355.37487 0,1279.36411 0,1185.96011 L0,1185.96011 L0,734.187433 C0,640.783431 76.0107531,564.772678 169.414754,564.772678 L169.414754,564.772678 L484.865027,564.772678 L936.637705,113 L1129.4317,113 Z M1016.48853,225.94317 L983.396178,225.94317 L564.715848,644.623499 L564.715848,1275.52404 L983.396178,1694.20437 L1016.48853,1694.20437 L1016.48853,225.94317 Z M1671.9768,361.057083 C1831.90433,521.097555 1920,733.769543 1920,960.107655 C1920,1186.33282 1831.90433,1399.00481 1671.9768,1559.04528 L1671.9768,1559.04528 L1592.12598,1479.19446 C1730.82019,1340.50025 1807.05683,1156.177 1807.05683,960.107655 C1807.05683,763.925369 1730.82019,579.602117 1592.12598,440.907904 L1592.12598,440.907904 Z M1432.86482,600.801549 C1528.52768,697.819732 1581.1592,825.445514 1581.1592,960.073772 C1581.1592,1094.70203 1528.52768,1222.32781 1432.86482,1319.34599 L1432.86482,1319.34599 L1352.33634,1240.05989 C1427.10471,1164.27502 1468.21603,1064.88503 1468.21603,960.073772 C1468.21603,855.262511 1427.10471,755.872521 1352.33634,680.087654 L1352.33634,680.087654 Z M451.772678,677.715848 L169.414754,677.715848 C138.355383,677.715848 112.94317,703.015118 112.94317,734.187433 L112.94317,734.187433 L112.94317,1185.96011 C112.94317,1217.13243 138.355383,1242.4317 169.414754,1242.4317 L169.414754,1242.4317 L451.772678,1242.4317 L451.772678,677.715848 Z",fillRule:"evenodd",stroke:"none",strokeWidth:"1"})
var m=function(e){Object(s["a"])(n,e)
var t=Object(l["a"])(n)
function n(){Object(a["a"])(this,n)
return t.apply(this,arguments)}Object(c["a"])(n,[{key:"render",value:function(){return u.a.createElement(x["a"],Object.assign({},this.props,{name:"IconAudio",viewBox:"0 0 1920 1920",bidirectional:true}),_)}}])
n.displayName="IconAudioLine"
return n}(d["Component"])
m.glyphName="audio"
m.variant="Line"
m.propTypes=Object(r["a"])({},x["a"].propTypes)
var p=u.a.createElement("g",{fillRule:"evenodd",stroke:"none",strokeWidth:"1"},u.a.createElement("path",{d:"M1251.65412,0 C1296.15294,0 1339.86118,18.0705882 1371.37176,49.5811765 L1371.37176,49.5811765 L1700.59529,378.804706 C1732.55765,410.767059 1750.17647,453.345882 1750.17647,498.522353 L1750.17647,498.522353 L1750.17647,1920 L169,1920 L169,0 Z M1185.47059,112.941176 L281.941176,112.941176 L281.941176,1807.05882 L1637.23529,1807.05882 L1637.23529,564.705882 L1185.47059,564.705882 L1185.47059,112.941176 Z M1298.41176,136.32 L1298.41176,451.764706 L1613.85647,451.764706 L1298.41176,136.32 Z"}),u.a.createElement("path",{d:"M959.588235 338.823529L959.588235 790.588235 507.823529 790.588235 507.823529 338.823529 959.588235 338.823529zM846.647059 451.764706L620.764706 451.764706 620.764706 677.647059 846.647059 677.647059 846.647059 451.764706zM507.823529 1016.47059L1411.35294 1016.47059 1411.35294 903.529412 507.823529 903.529412zM507.823529 1468.23529L1298.41176 1468.23529 1298.41176 1355.29412 507.823529 1355.29412zM507.823529 1242.35294L1185.47059 1242.35294 1185.47059 1129.41176 507.823529 1129.41176z"}))
var f=function(e){Object(s["a"])(n,e)
var t=Object(l["a"])(n)
function n(){Object(a["a"])(this,n)
return t.apply(this,arguments)}Object(c["a"])(n,[{key:"render",value:function(){return u.a.createElement(x["a"],Object.assign({},this.props,{name:"IconMsWord",viewBox:"0 0 1920 1920"}),p)}}])
n.displayName="IconMsWordLine"
return n}(d["Component"])
f.glyphName="ms-word"
f.variant="Line"
f.propTypes=Object(r["a"])({},x["a"].propTypes)
var h=n("1pz7")
var y=n("jtOZ")
var b=n("vM4J")
var g=n("+Gzo")
function v(e){if(C(e))return i["a"]
if(O(e))return m
switch(e){case"application/msword":case"application/vnd.openxmlformats-officedocument.wordprocessingml.document":return f
case"application/vnd.ms-powerpoint":case"application/vnd.openxmlformats-officedocument.presentationml.presentation":return h["a"]
case"application/pdf":return y["a"]
case"application/vnd.ms-excel":case"application/vnd.openxmlformats-officedocument.spreadsheetml.sheet":return b["a"]
default:return g["a"]}}function w(e){return/^image/.test(e)}function k(e){return C(e)||O(e)}function C(e){return/^video/.test(e)}function O(e){return/^audio/.test(e)}function E(e){return/^text/.test(e)}function A(e){const t=e["content-type"]||e.content_type||e.type
const n=t.replace(/\/.*$/,"")
if(e.embedded_iframe_url)return`${e.embedded_iframe_url}?type=${n}`
if(k(t)){var i
const t=e.media_entry_id||(null===(i=e.embed)||void 0===i?void 0:i.id)
if(t&&"maybe"!==t)return`/media_objects_iframe/${t}?type=${n}`
const r=Object(o["parse"])(e.url||e.href,true)
const a=r.query.verifier?"&verifier="+r.query.verifier:""
return`/media_objects_iframe?mediahref=${r.pathname}${a}&type=${n}`}return}},lcQH:function(e,t,n){"use strict"
n.d(t,"a",(function(){return q}))
n.d(t,"b",(function(){return K}))
var o=n("VTBJ")
var i=n("ODXe")
var r=n("q1tI")
var a=n.n(r)
var c=n("17x9")
var s=n.n(c)
var l=n("Ci/e")
var d=n("Mmr1")
var u=n("msMH")
var x=n("uSnb")
var _=n("TstA")
var m=n("NFDp")
class p extends a.a.Component{constructor(e){super(e)
this.state={hasError:false}}static getDerivedStateFromError(e){return{hasError:true,error:e}}render(){if(this.state.hasError){const e=this.state.error.message?this.state.error.message:this.state.error.toString()
return a.a.createElement("div",{style:{margin:"1rem"}},a.a.createElement("h2",null,Object(m["a"])("Something went wrong.")),a.a.createElement("p",null,e))}return this.props.children}}p.propTypes={children:s.a.node}
var f=n("+oik")
var h=n("n12J")
var y=n("WEeK")
var b=n("2zZe")
var g=n("Zgll")
var v=n("6SzX")
var w=n("0k/6")
var k=n("d3fI")
var C=n("+Pml")
var O=n("Zk7g")
var E=n("+Gzo")
var A=n("bKqk")
var S=n("CMdt")
var j=n("3Sge")
const I={contentSubtype:"all",contentType:"links",sortValue:"date_added",searchString:""}
function T(e){const t=Object(r["useState"])(e||I),n=Object(i["a"])(t,2),a=n[0],c=n[1]
return[a,function(e){c(Object(o["a"])(Object(o["a"])({},a),e))}]}function L(e){switch(e){case"user":return Object(m["a"])("User Files")
case"course":return Object(m["a"])("Course Files")
case"group":return Object(m["a"])("Group Files")
case"files":default:return Object(m["a"])("Files")}}function B(e,t,n){const o=[a.a.createElement(b["a"].Option,{key:"links",id:"links",value:"links",renderBeforeLabel:k["a"]},Object(m["a"])("Links"))]
"course"===n&&"links"!==e&&"all"!==t&&o.push(a.a.createElement(b["a"].Option,{key:"course_files",id:"course_files",value:"course_files",renderBeforeLabel:C["a"]},L("course")))
"group"===n&&"links"!==e&&"all"!==t&&o.push(a.a.createElement(b["a"].Option,{key:"group_files",id:"group_files",value:"group_files",renderBeforeLabel:C["a"]},L("group")))
t!==w["c"]&&o.push(a.a.createElement(b["a"].Option,{key:"user_files",id:"user_files",value:"user_files",renderBeforeLabel:C["a"]},L("links"===e||"all"===t?"files":"user")))
return o}function D(e,t,n,o,i){return"course"===i||"group"===i?a.a.createElement(b["a"],{renderLabel:a.a.createElement(v["a"],null,Object(m["a"])("Content Type")),assistiveText:Object(m["a"])("Use arrow keys to navigate options."),onChange:(t,o)=>{const i={contentType:o.value}
"links"===e&&(i.contentSubtype="all")
n(i)},value:e},B(e,t,o)):a.a.createElement(h["a"],{as:"div",borderWidth:"small",padding:"x-small small",borderRadius:"medium",width:"100%"},a.a.createElement(v["a"],null,Object(m["a"])("Content Type")),L("user",t))}function R(e){return 0===e.length||e.length>=3}function F(e){const t=e.contentType,n=e.contentSubtype,o=e.onChange,c=e.sortValue,s=e.searchString,l=e.userContextType,d=e.isContentLoading,u=e.containingContextType
const x=Object(r["useState"])(s),p=Object(i["a"])(x,2),f=p[0],k=p[1]
const C=Object(r["useState"])(0),I=Object(i["a"])(C,2),T=I[0],L=I[1]
Object(r["useEffect"])(()=>{o({contentType:t})},[])
function B(e){if(R(e)){if(T){window.clearTimeout(T)
L(0)}o({searchString:e})}}function F(e){k(e)
T&&window.clearTimeout(T)
const t=window.setTimeout(()=>B(e),250)
L(t)}function M(){F("")}const z=Object(m["a"])("Enter at least 3 characters to search")
const P=Object(m["a"])("Loading, please wait")
const N=d?P:z
return a.a.createElement(h["a"],{display:"block",direction:"column"},D(t,n,o,l,u),"links"!==t&&a.a.createElement(_["a"],{margin:"small none none none"},a.a.createElement(_["a"].Item,{grow:true,shrink:true,margin:"none xx-small none none"},a.a.createElement(b["a"],{renderLabel:a.a.createElement(v["a"],null,Object(m["a"])("Content Subtype")),assistiveText:Object(m["a"])("Use arrow keys to navigate options."),onChange:(e,t)=>{const n={contentSubtype:t.value}
"all"===n.contentSubtype?n.contentType="user_files":n.contentSubtype===w["c"]&&(n.contentType="course_files")
o(n)},value:n},a.a.createElement(b["a"].Option,{id:"images",value:"images",renderBeforeLabel:O["a"]},Object(m["a"])("Images")),a.a.createElement(b["a"].Option,{id:"documents",value:"documents",renderBeforeLabel:E["a"]},Object(m["a"])("Documents")),a.a.createElement(b["a"].Option,{id:"media",value:"media",renderBeforeLabel:A["a"]},Object(m["a"])("Media")),e.use_rce_buttons_and_icons&&a.a.createElement(b["a"].Option,{id:"buttons_and_icons",value:"buttons_and_icons",renderBeforeLabel:O["a"]},Object(m["a"])("Buttons and Icons")),a.a.createElement(b["a"].Option,{id:"all",value:"all"},Object(m["a"])("All")))),"all"!==n&&a.a.createElement(_["a"].Item,{grow:true,shrink:true,margin:"none none none xx-small"},a.a.createElement(b["a"],{renderLabel:a.a.createElement(v["a"],null,Object(m["a"])("Sort By")),assistiveText:Object(m["a"])("Use arrow keys to navigate options."),onChange:(e,t)=>{o({sortValue:t.value})},value:c},a.a.createElement(b["a"].Option,{id:"date_added",value:"date_added"},Object(m["a"])("Date Added")),a.a.createElement(b["a"].Option,{id:"alphabetical",value:"alphabetical"},Object(m["a"])("Alphabetical"))))),a.a.createElement(h["a"],{as:"div",margin:"small none none none"},a.a.createElement(y["a"],{renderLabel:a.a.createElement(v["a"],null,Object(m["a"])("Search")),renderBeforeInput:a.a.createElement(S["a"],{inline:false}),renderAfterInput:function(){if(f)return a.a.createElement(g["a"],{screenReaderLabel:Object(m["a"])("Clear"),onClick:M,interaction:d?"disabled":"enabled",withBorder:false,withBackground:false,size:"small"},a.a.createElement(j["a"],null))
return}(),messages:[{type:"hint",text:N}],placeholder:Object(m["a"])("Search"),value:f,onChange:(e,t)=>F(t),onKeyDown:e=>{"Enter"===e.key&&B(f)},interaction:d?"readonly":"enabled"})))}F.propTypes={contentSubtype:c["string"].isRequired,contentType:Object(c["oneOf"])(["links","user_files","course_files","group_files"]).isRequired,onChange:c["func"].isRequired,sortValue:c["string"].isRequired,searchString:c["string"].isRequired,userContextType:Object(c["oneOf"])(["user","course","group"]),isContentLoading:c["bool"],containingContextType:Object(c["oneOf"])(["user","course","group"])}
var M=n("eHui")
var z=n("z7I/")
function P(e,t,n){if("links"===e&&"course"===n)return Object(m["a"])("Course Links")
if("links"===e&&"group"===n)return Object(m["a"])("Group Links")
switch(t){case w["c"]:return Object(m["a"])("Buttons and Icons")
case"images":if("course_files"===e)return Object(m["a"])("Course Images")
if("group_files"===e)return Object(m["a"])("Group Images")
return Object(m["a"])("User Images")
case"media":if("course_files"===e)return Object(m["a"])("Course Media")
if("group_files"===e)return Object(m["a"])("Group Media")
return Object(m["a"])("User Media")
case"documents":if("course_files"===e)return Object(m["a"])("Course Documents")
if("group_files"===e)return Object(m["a"])("Group Documents")
return Object(m["a"])("User Documents")
default:return Object(m["a"])("Tray")}}const N={buttons_and_icons:a.a.lazy(()=>Promise.all([n.e(13),n.e(87),n.e(4177)]).then(n.bind(null,"F/nJ"))),links:a.a.lazy(()=>n.e(4131).then(n.bind(null,"2k/U"))),images:a.a.lazy(()=>Promise.all([n.e(13),n.e(87),n.e(4190)]).then(n.bind(null,"ZXxL"))),documents:a.a.lazy(()=>n.e(4145).then(n.bind(null,"3R0a"))),media:a.a.lazy(()=>n.e(4146).then(n.bind(null,"bfKp"))),all:a.a.lazy(()=>Promise.all([n.e(28),n.e(66),n.e(82),n.e(4170)]).then(n.bind(null,"NhNB"))),unknown:a.a.lazy(()=>n.e(4338).then(n.bind(null,"G/Kj")))}
function U(e){let t=""
t="links"===e.contentType?"links":e.contentSubtype in N?e.contentSubtype:"unknown"
const n=N[t]
return a.a.createElement(r["Suspense"],{fallback:a.a.createElement(x["a"],{renderTitle:$,size:"large"})},a.a.createElement(n,e))}function $(){return Object(m["a"])("Loading")}const H={user_documents:{contextType:"user",contentType:"user_files",contentSubtype:"documents",sortValue:"date_added",sortDir:"desc",searchString:""},course_documents:{contextType:"course",contentType:"course_files",contentSubtype:"documents",sortValue:"date_added",sortDir:"desc",searchString:""},group_documents:{contextType:"group",contentType:"group_files",contentSubtype:"documents",sortValue:"date_added",sortDir:"desc",searchString:""},user_images:{contextType:"user",contentType:"user_files",contentSubtype:"images",sortValue:"date_added",sortDir:"desc",searchString:""},course_images:{contextType:"course",contentType:"course_files",contentSubtype:"images",sortValue:"date_added",sortDir:"desc",searchString:""},group_images:{contextType:"group",contentType:"group_files",contentSubtype:"images",sortValue:"date_added",sortDir:"desc",searchString:""},user_media:{contextType:"user",contentType:"user_files",contentSubtype:"media",sortValue:"date_added",sortDir:"desc",searchString:""},course_media:{contextType:"course",contentType:"course_files",contentSubtype:"media",sortValue:"date_added",sortDir:"desc",searchString:""},group_media:{contextType:"group",contentType:"group_files",contentSubtype:"media",sortValue:"date_added",sortDir:"desc",searchString:""},course_links:{contextType:"course",contentType:"links",contentSubtype:"all",sortValue:"date_added",sortDir:"desc",searchString:""},group_links:{contextType:"group",contentType:"links",contentSubtype:"all",sortValue:"date_added",sortDir:"desc",searchString:""},list_buttons_and_icons:{contextType:"course",contentType:"course_files",contentSubtype:w["c"],sortValue:"date_added",sortDir:"desc",searchString:""},all:{contextType:"course",contentType:"course_files",contentSubtype:"all",sortValue:"alphabetical",sortDir:"asc",searchString:""}}
function W(e){var t,n,o,i,r,a,c,s,l,d,u,x,_
return(null===(t=e.collections.announcements)||void 0===t?void 0:t.isLoading)||(null===(n=e.collections.assignments)||void 0===n?void 0:n.isLoading)||(null===(o=e.collections.discussions)||void 0===o?void 0:o.isLoading)||(null===(i=e.collections.modules)||void 0===i?void 0:i.isLoading)||(null===(r=e.collections.quizzes)||void 0===r?void 0:r.isLoading)||(null===(a=e.collections.wikiPages)||void 0===a?void 0:a.isLoading)||(null===(c=e.documents.course)||void 0===c?void 0:c.isLoading)||(null===(s=e.documents.user)||void 0===s?void 0:s.isLoading)||(null===(l=e.documents.group)||void 0===l?void 0:l.isLoading)||(null===(d=e.media.course)||void 0===d?void 0:d.isLoading)||(null===(u=e.media.user)||void 0===u?void 0:u.isLoading)||(null===(x=e.media.group)||void 0===x?void 0:x.isLoading)||(null===(_=e.all_files)||void 0===_?void 0:_.isLoading)}function q(e){const t=Object(r["useState"])(false),n=Object(i["a"])(t,2),c=n[0],s=n[1]
const x=Object(r["useState"])(false),f=Object(i["a"])(x,2),h=f[0],y=f[1]
const b=Object(r["useState"])(true),g=Object(i["a"])(b,2),v=g[0],w=g[1]
const k=Object(r["useRef"])(null)
const C=Object(r["useRef"])(null)
const O=T(),E=Object(i["a"])(O,2),A=E[0],S=E[1]
const j=Object(o["a"])({},e),I=j.bridge,L=j.editor,B=j.onTrayClosing
const D=Object(r["useCallback"])(()=>{k.current&&k.current.contains(document.activeElement)&&I.focusActiveEditor(false)
B&&B(q.globalOpenCount)
s(false)},[I,B])
Object(r["useEffect"])(()=>{I.attachController({showTrayForPlugin(e){++q.globalOpenCount
S(H[e])
s(true)},hideTray(e){(e||v)&&D()}},L.id)
return()=>{I.detachController(L.id)}},[L.id,I,D,v])
Object(r["useEffect"])(()=>{h&&C.current&&!C.current.style.overscrollBehaviorY&&(C.current.style.overscrollBehaviorY="contain")},[h])
function R(){I.focusEditor(L)
y(true)}function N(){B&&B(true)}function $(){y(false)
B&&B(false)}function V(t,n,i,r){const a=Object(o["a"])({},t)
if(a.sortValue){a.sortDir="alphabetical"===a.sortValue?"asc":"desc"
r({sort:a.sortValue,dir:a.sortDir})}"searchString"in a&&A.searchString!==a.searchString&&i(a.searchString)
S(a)
if(a.contentType){let t,o
switch(a.contentType){case"user_files":t="user"
o=e.containingContext.userId
break
case"group_files":t="group"
o=e.containingContext.contextId
break
case"course_files":t=e.contextType
o=e.containingContext.contextId
break
case"links":t=e.containingContext.contextType
o=e.containingContext.contextId}n({contextType:t,contextId:o})}}return a.a.createElement(M["a"],Object.assign({},e,{key:q.globalOpenCount,contextType:A.contextType||e.contextType}),t=>a.a.createElement(l["a"],{"data-mce-component":true,"data-testid":"CanvasContentTray",label:P(A.contentType,A.contentSubtype,t.contextType),open:c,placement:"end",size:"regular",shouldContainFocus:true,shouldReturnFocus:false,shouldCloseOnDocumentClick:false,onDismiss:D,onClose:$,onExit:N,onOpen:R,onEntered:()=>{const e=document.querySelector('[role="main"]')
let t=0
if(e){var n
const o="ltr"===window.getComputedStyle(e).direction?document.body.getBoundingClientRect().right-e.getBoundingClientRect().right:e.getBoundingClientRect().left
t=e.offsetWidth-(null===(n=k.current)||void 0===n?void 0:n.offsetWidth)+o
if(t>=320&&t<e.offsetWidth){e.style.boxSizing="border-box"
e.style.width=t+"px"}}w(t<320)},onExiting:()=>{const e=document.querySelector('[role="main"]')
e&&(e.style.width="")},contentRef:e=>k.current=e},c&&h?a.a.createElement(_["a"],{direction:"column",as:"div",height:Object(z["a"])(),overflowY:"hidden",tabIndex:"-1","data-canvascontenttray-content":true},a.a.createElement(_["a"].Item,{padding:"medium",shadow:"above"},a.a.createElement(_["a"],{margin:"none none medium none"},a.a.createElement(_["a"].Item,{shouldgrow:true,shouldshrink:true},a.a.createElement(u["a"],{level:"h2"},Object(m["a"])("Add"))),a.a.createElement(_["a"].Item,null,a.a.createElement(d["a"],{placement:"end",onClick:D,"data-testid":"CloseButton_ContentTray",screenReaderLabel:Object(m["a"])("Close")}))),a.a.createElement(F,Object.assign({},A,{userContextType:e.contextType,containingContextType:e.containingContext.contextType,onChange:e=>{V(e,t.onChangeContext,t.onChangeSearchString,t.onChangeSortBy)},isContentLoading:W(t),use_rce_buttons_and_icons:e.use_rce_buttons_and_icons}))),a.a.createElement(_["a"].Item,{shouldgrow:true,shouldshrink:true,margin:"xx-small xxx-small 0",elementRef:e=>C.current=e},a.a.createElement(p,null,a.a.createElement(U,Object.assign({contentType:A.contentType,contentSubtype:A.contentSubtype,sortBy:{sort:A.sortValue,order:A.sortDir},searchString:A.searchString,source:e.source,jwt:e.jwt,host:e.host,refreshToken:e.refreshToken,context:{type:e.contextType,id:e.contextId}},t))))):null))}q.globalOpenCount=0
function V(e,t,n){if(null==e.source&&null==e[t])throw new Error(`The prop \`${t}\` is marked as required in \`${n}\`, but its value is \`${e[t]}\`.`)}const G={canUploadFiles:c["bool"].isRequired,contextId:c["string"].isRequired,contextType:c["string"].isRequired,containingContext:Object(c["shape"])({contextType:c["string"].isRequired,contextId:c["string"].isRequired,userId:c["string"].isRequired}),filesTabDisabled:c["bool"],host:V,jwt:V,refreshToken:c["func"],source:Object(c["shape"])({fetchImages:c["func"].isRequired}),themeUrl:c["string"]}
const K=Object(c["shape"])(G)
q.propTypes=Object(o["a"])({bridge:Object(c["instanceOf"])(f["a"]).isRequired,editor:Object(c["shape"])({id:c["string"]}).isRequired,onTrayClosing:c["func"]},G)
q.defaultProps={canUploadFiles:false,filesTabDisabled:false,refreshToken:null,source:null,themeUrl:null}},"n/1O":function(e,t,n){"use strict"
n.d(t,"b",(function(){return u}))
n.d(t,"c",(function(){return x}))
var o=n("VTBJ")
n("LpSC")
var i=n("CxY0")
var r=n("LixQ")
var a=n("qScw")
var c=n("NFDp")
var s=n("eAGa")
const l=3e5
const d=5e3
function u(e){return{Authorization:"Bearer "+e}}function x(e,t){let n=e
if("string"!==typeof n)n=""
else if(n&&"http"!==n.substr(0,4)){var o
n="//"+n
const e=t||("undefined"!==typeof window?window:void 0)
n.length>0&&null!==e&&void 0!==e&&null!==(o=e.location)&&void 0!==o&&o.protocol&&(n=`${e.location.protocol}${n}`)}return n}function _(e){if(e.status<400)return e
{const t=new Error(e.statusText)
t.response=e
throw t}}function m(){throw new Error("Token expired, no refresh function provided")}function p(e){return Object(o["a"])(Object(o["a"])({display_name:e.name},e),{},{href:Object(a["a"])(e.href||e.url)})}function f(e){"TypeError"===e.name&&console.error("Failed to fetch from the canvas-rce-api.\n      Did you forget to start it or configure it?\n      Details can be found at https://github.com/instructure/canvas-rce-api\n    ")
throw e}class h{constructor(e={}){this.jwt=e.jwt
this.host=e.host
this.refreshToken=e.refreshToken||m
this.hasSession=false
this.alertFunc=e.alertFunc||s["a"].handleAlert}getSession(){const e=u(this.jwt)
const t=this.baseUri("session")
return this.apiReallyFetch(t,e).then(e=>{this.hasSession=true
return e}).catch(f)}initializeCollection(e,t){return{links:[],bookmark:this.uriFor(e,t),isLoading:false,hasMore:true,searchString:t.searchString}}initializeUpload(){return{uploading:false,folders:{},formExpanded:false}}initializeImages(e){return this.initializeDocuments(e)}initializeDocuments(e){return{[e.contextType]:{files:[],bookmark:null,isLoading:false,hasMore:true},searchString:""}}initializeMedia(e){return this.initializeDocuments(e)}initializeFlickr(){return{searchResults:[],searching:false,formExpanded:false}}fetchPage(e){return this.apiFetch(e,u(this.jwt))}fetchBookmarkedData(e,t,n,o,i){return e(t,i).then(i=>{n(i)
i.bookmark&&this.fetchBookmarkedData(e,t,n,o,i.bookmark)}).catch(e=>{o(e)})}fetchDocs(e){const t=e.documents[e.contextType]
const n=t.bookmark||this.uriFor("documents",e)
return this.apiFetch(n,u(this.jwt)).then(({bookmark:t,files:n})=>({bookmark:t,files:n.map(t=>Object(a["b"])(e.contextType,e.contextId,t))}))}fetchMedia(e){const t=e.media[e.contextType]
const n=t.bookmark||this.uriFor("media_objects",e)
return this.apiFetch(n,u(this.jwt))}fetchFiles(e){return this.fetchPage(e).then(({bookmark:e,files:t})=>({bookmark:e,files:t.map(p)}))}fetchLinks(e,t){const n=t.collections
const o=n[e].bookmark||this.uriFor(e,t)
return this.fetchPage(o)}fetchRootFolder(e){return this.fetchPage(this.uriFor("folders",e),this.jwt)}mediaServerSession(){return this.apiPost(this.baseUri("v1/services/kaltura_session"),u(this.jwt),{})}uploadMediaToCanvas(e){const t={id:e.entryId,type:{2:"image",5:"audio"}[e.mediaType]||e.type.includes("audio")?"audio":"video",context_code:e.contextCode,title:e.title,user_entered_title:e.userTitle}
return this.apiPost(this.baseUri("media_objects"),u(this.jwt),t)}updateMediaObject(e,{media_object_id:t,title:n}){const o=`${this.baseUri("media_objects",e.host)}/${t}?user_entered_title=${encodeURIComponent(n)}`
return this.apiPost(o,u(this.jwt),null,"PUT")}updateClosedCaptions(e,{media_object_id:t,subtitles:n},o){return Object(r["b"])(t,n,{origin:x(e.host),headers:u(e.jwt)},o||l-d).catch(e=>{console.error("Failed saving CC",e)
const t="FileSizeError"===e.name?Object(c["a"])("Closed caption file must be less than {maxKb} kb",{maxKb:e.maxBytes/1e3}):Object(c["a"])("Uploading closed captions/subtitles failed.")
this.alertFunc({text:t,variant:"error"})})}fetchClosedCaptions(){return Promise.resolve([{locale:"af",content:"1\r\n00:00:00,000 --\x3e 00:00:01,251\r\nThis is the content\r\n"},{locale:"es",content:"1\r\n00:00:00,000 --\x3e 00:00:01,251\r\nThis is the content\r\n"}])}fetchFolders(e,t){const n=u(this.jwt)
const o=t||this.uriFor("folders/all",e)
return this.apiFetch(o,n)}fetchFilesForFolder(e,t){let n
if(!t){const t=e.perPage?"per_page="+e.perPage:""
n=`${e.filesUrl}?${t}${g(e.searchString)}`
e.sortBy&&(n+=""+y(e.sortBy.sort,e.sortBy.order))}return this.fetchPage(n||t,this.jwt)}fetchSubFolders(e,t){const n=t||`${this.baseUri("folders",e.host)}/${e.folderId}`
return this.apiFetch(n,u(this.jwt))}fetchButtonsAndIconsFolder({contextId:e,contextType:t}){const n=this.uriFor("folders/buttons_and_icons",{contextId:e,contextType:t,host:this.host,jwt:this.jwt})
return this.fetchPage(n)}fetchMediaFolder(e){let t
t="user"===e.contextType?this.uriFor("folders",e):this.uriFor("folders/media",e)
return this.fetchPage(t)}fetchMediaObjectIframe(e){return this.fetchPage(this.uriFor("media_objects_iframe/"+e))}fetchImages(e){const t=e.images[e.contextType]
const n=t.bookmark||this.uriFor("images",e)
const o=u(this.jwt)
return this.apiFetch(n,o).then(({bookmark:t,files:n})=>({bookmark:t,files:n.map(t=>Object(a["b"])(e.contextType,e.contextId,t)),searchString:e.searchString}))}preflightUpload(e,t){const n=u(this.jwt)
const o=this.baseUri("upload",t.host)
const i={contextId:t.contextId,contextType:t.contextType,file:e,no_redirect:true,onDuplicate:t.onDuplicate,category:t.category}
return this.apiPost(o,n,i)}uploadFRD(e,t){const n=new window.FormData
Object.keys(t.upload_params).forEach(e=>{n.append(e,t.upload_params[e])})
n.append("file",e)
const o={method:"POST",body:n}
t.upload_params["x-amz-signature"]||(o.credentials="include")
return fetch(t.upload_url,o).then(_).then(e=>e.json()).then(e=>this.finalizeUpload(t,e)).catch(()=>{this.alertFunc({text:Object(c["a"])("Something went wrong uploading, check your connection and try again."),variant:"error"})})}finalizeUpload(e,t){if(e.upload_params.success_url)return fetch(e.upload_params.success_url).then(_).then(e=>e.json())
if(t.location){const e=Object(i["parse"])(t.location),n=e.pathname
const o=n.match(/^\/api\/v1\/files\/((?:\d+~)?\d+)$/)
if(!o){const e=new Error("cannot determine file ID from location")
e.location=t.location
throw e}const r=o[1]
return this.getFile(r).then(e=>{e.uuid=t.uuid
return e})}return Promise.resolve(t)}setUsageRights(e,t){const n=u(this.jwt)
const i=this.baseUri("usage_rights")
const r=Object(o["a"])({fileId:e},t)
return this.apiPost(i,n,r)}searchFlickr(e,t){const n=u(this.jwt)
const o=this.baseUri("flickr_search",t.host)
const i=`${o}?term=${encodeURIComponent(e)}`
return this.apiFetch(i,n)}searchUnsplash(e,t){const n=u(this.jwt)
const o=this.baseUri("unsplash/search")
const i=`${o}?term=${encodeURIComponent(e)}&page=${t}&per_page=12`
return this.apiFetch(i,n)}pingbackUnsplash(e){const t=u(this.jwt)
const n=this.baseUri("unsplash/pingback")
return this.apiFetch(`${n}?id=${e}`,t,{skipParse:true})}getFile(e){const t=u(this.jwt)
const n=this.baseUri("file")
return this.apiFetch(`${n}/${e}`,t).then(p)}async apiFetch(e,t,n){this.hasSession||await this.getSession()
return this.apiReallyFetch(e,t,n)}apiReallyFetch(e,t,n={}){e=this.normalizeUriProtocol(e)
return fetch(e,{headers:t}).then(n=>401===n.status?this.buildRetryHeaders(t).then(t=>fetch(e,{headers:t})):n).then(_).then(n.skipParse?()=>{}:e=>e.json()).catch(f).catch(e=>{this.alertFunc({text:Object(c["a"])("Something went wrong, try again after refreshing the page"),variant:"error"})
throw e})}apiPost(e,t,n,i="POST"){t=Object(o["a"])(Object(o["a"])({},t),{},{"Content-Type":"application/json"})
const r={method:i,headers:t}
n?r.body=JSON.stringify(n):r.form=n
e=this.normalizeUriProtocol(e)
return fetch(e,r).then(t=>401===t.status?this.buildRetryHeaders(r.headers).then(t=>{const n=Object(o["a"])(Object(o["a"])({},r),{},{headers:t})
return fetch(e,n)}):t).then(_).then(e=>e.json()).catch(f).catch(e=>{console.error(e)
this.alertFunc({text:Object(c["a"])("Something went wrong, check your connection and try again."),variant:"error"})
throw e})}normalizeUriProtocol(e,t){const n=t||("undefined"!==typeof window?window:void 0)
if(n&&n.location&&"https:"===n.location.protocol)return e.replace("http://","https://")
return e}buildRetryHeaders(e){return new Promise(t=>{this.refreshToken(n=>{this.jwt=n
const i=u(n)
const r=Object(o["a"])(Object(o["a"])({},e),i)
t(r)})})}baseUri(e,t,n){!t&&this.host&&(t=this.host)
t=x(t,n)
const o=["images","media","documents","all"].includes(e)?"documents":e
return`${t}/api/${o}`}uriFor(e,t){const n=t.host,o=t.contextType,i=t.contextId,r=t.sortBy,a=t.searchString,c=t.perPage
let s=""
const l=c?"&per_page="+c:""
switch(e){case"images":s=`&content_types=image${y(r.sort,r.dir)}${g(a)}${b(t,"category")}`
break
case"media":s=`&content_types=video,audio${y(r.sort,r.dir)}${g(a)}`
break
case"documents":s=`&exclude_content_types=image,video,audio${y(r.sort,r.dir)}${g(a)}`
break
case"media_objects":s=`${y("alphabetical"===r.sort?"title":"date",r.dir)}${g(a)}`
break
default:s=g(a)}return`${this.baseUri(e,n)}?contextType=${o}&contextId=${i}${l}${s}`}}function y(e,t){let n=e
"date_added"===n?n="created_at":"alphabetical"===n&&(n="name")
return`&sort=${n}&order=${t}`}function b(e,t){return e[t]?`&${t}=${e[t]}`:""}function g(e){return(null===e||void 0===e?void 0:e.length)>=3?"&search_term="+encodeURIComponent(e):""}t["a"]=h},q8CT:function(e,t,n){"use strict"
n.d(t,"a",(function(){return x}))
var o=n("VTBJ")
var i=n("1OyB")
var r=n("vuIU")
var a=n("Ji7U")
var c=n("LK+K")
var s=n("q1tI")
var l=n.n(s)
var d=n("hPGw")
var u=l.a.createElement("path",{d:"M686.211429,137.142857 C686.211429,137.142857 686.211429,137.142857 686.211429,137.005714 L754.782857,137.142857 L686.211429,137.142857 Z M686.211429,1645.71429 C761.777143,1645.71429 823.354286,1707.29143 823.354286,1782.85714 C823.354286,1858.42286 761.777143,1920 686.211429,1920 C610.508571,1920 549.068571,1858.42286 549.068571,1782.85714 C549.068571,1707.29143 610.508571,1645.71429 686.211429,1645.71429 Z M1234.78286,1645.71429 C1310.34857,1645.71429 1371.92571,1707.29143 1371.92571,1782.85714 C1371.92571,1858.42286 1310.34857,1920 1234.78286,1920 C1159.08,1920 1097.64,1858.42286 1097.64,1782.85714 C1097.64,1707.29143 1159.08,1645.71429 1234.78286,1645.71429 Z M686.211429,1097.14286 C761.777143,1097.14286 823.354286,1158.72 823.354286,1234.28571 C823.354286,1309.85143 761.777143,1371.42857 686.211429,1371.42857 C610.508571,1371.42857 549.068571,1309.85143 549.068571,1234.28571 C549.068571,1158.72 610.508571,1097.14286 686.211429,1097.14286 Z M1234.78286,1097.14286 C1310.34857,1097.14286 1371.92571,1158.72 1371.92571,1234.28571 C1371.92571,1309.85143 1310.34857,1371.42857 1234.78286,1371.42857 C1159.08,1371.42857 1097.64,1309.85143 1097.64,1234.28571 C1097.64,1158.72 1159.08,1097.14286 1234.78286,1097.14286 Z M686.211429,548.571429 C761.777143,548.571429 823.354286,610.148571 823.354286,685.714286 C823.354286,761.28 761.777143,822.857143 686.211429,822.857143 C610.508571,822.857143 549.068571,761.28 549.068571,685.714286 C549.068571,610.148571 610.508571,548.571429 686.211429,548.571429 Z M1234.78286,548.571429 C1310.34857,548.571429 1371.92571,610.148571 1371.92571,685.714286 C1371.92571,761.28 1310.34857,822.857143 1234.78286,822.857143 C1159.08,822.857143 1097.64,761.28 1097.64,685.714286 C1097.64,610.148571 1159.08,548.571429 1234.78286,548.571429 Z M686.211429,0 C761.777143,0 823.354286,61.5771429 823.354286,137.142857 C823.354286,212.708571 761.777143,274.285714 686.211429,274.285714 C610.508571,274.285714 549.068571,212.708571 549.068571,137.142857 C549.068571,61.5771429 610.508571,0 686.211429,0 Z M1234.71429,0 C1310.28,0 1371.85714,61.5771429 1371.85714,137.142857 C1371.85714,212.708571 1310.28,274.285714 1234.71429,274.285714 C1159.14857,274.285714 1097.57143,212.708571 1097.57143,137.142857 C1097.57143,61.5771429 1159.14857,0 1234.71429,0 Z",fillRule:"evenodd",stroke:"none",strokeWidth:"1"})
var x=function(e){Object(a["a"])(n,e)
var t=Object(c["a"])(n)
function n(){Object(i["a"])(this,n)
return t.apply(this,arguments)}Object(r["a"])(n,[{key:"render",value:function(){return l.a.createElement(d["a"],Object.assign({},this.props,{name:"IconDragHandle",viewBox:"0 0 1920 1920"}),u)}}])
n.displayName="IconDragHandleLine"
return n}(s["Component"])
x.glyphName="drag-handle"
x.variant="Line"
x.propTypes=Object(o["a"])({},d["a"].propTypes)},qScw:function(e,t,n){"use strict"
n.d(t,"a",(function(){return i}))
n.d(t,"b",(function(){return r}))
n.d(t,"c",(function(){return a}))
n.d(t,"d",(function(){return c}))
var o=n("CxY0")
function i(e){if(!e)return e
const t=Object(o["parse"])(e,true)
if(t.host&&window.location.host!==t.host)return e
delete t.search
delete t.query.download_frd
t.query.wrap="1"
t.pathname=t.pathname.replace(/\/(?:download|preview)\/?$/,"")
return Object(o["format"])(t)}function r(e,t,n){const i=n.href?"href":"url"
if(n[i]){const r=Object(o["parse"])(n[i],true)
if(!r.host||window.location.host===r.host){delete r.search
delete r.query.download_frd
r.query.wrap="1"
r.pathname=r.pathname.replace(/\/download\/?$/,"")
if(/^\/files/.test(r.pathname)){const n=e.replace(/([^s])$/,"$1s")
r.pathname=`/${n}/${t}${r.pathname}`}if(n.uuid&&e.includes("user")){delete r.search
r.query.verifier=n.uuid}n[i]=Object(o["format"])(r)}}return n}function a(e){if(!e)return e
const t=Object(o["parse"])(e,true)
if(t.host&&window.location.host!==t.host)return e;/\/preview(?:\?|$)/.test(t.pathname)||(t.pathname=t.pathname.replace(/(?:\/download)?\/?(\?|$)/,"/preview$1"))
delete t.search
delete t.query.wrap
return Object(o["format"])(t)}function c(e){if(!e)return e
const t=Object(o["parse"])(e,true)
if(t.host&&window.location.host!==t.host)return e
delete t.search
t.pathname=t.pathname.replace(/\/preview(\?|$)/,"$1")
t.query.wrap="1"
return Object(o["format"])(t)}},rCsd:function(e,t,n){"use strict"
n.d(t,"a",(function(){return i}))
const o=["application/vnd.openxmlformats-officedocument.wordprocessingml.template","application/vnd.oasis.opendocument.spreadsheet","application/vnd.sun.xml.writer","application/excel","application/vnd.openxmlformats-officedocument.spreadsheetml.sheet","text/rtf","application/vnd.openxmlformats-officedocument.spreadsheetml.template","application/vnd.sun.xml.impress","application/vnd.sun.xml.calc","application/vnd.ms-excel","application/msword","application/mspowerpoint","application/rtf","application/vnd.oasis.opendocument.presentation","application/vnd.oasis.opendocument.text","application/vnd.openxmlformats-officedocument.presentationml.template","application/vnd.openxmlformats-officedocument.presentationml.slideshow","text/plain","application/vnd.openxmlformats-officedocument.presentationml.presentation","application/vnd.openxmlformats-officedocument.wordprocessingml.document","application/postscript","application/pdf","application/vnd.ms-powerpoint"]
function i(e){return o.includes(e)}},s54W:function(e,t,n){"use strict"
n.d(t,"a",(function(){return o}))
function o(e){const t=i(e)
return"image"===t?{type:"image"}:"video"===t||"audio"===t?{type:t}:e.preview_url?{type:"scribd"}:{type:"file"}}function i(e){if(e.mime_class)return e.mime_class
{const t=r(e)
return{"text/html":"html","text/x-csharp":"code","text/xml":"code","text/css":"code",text:"text","text/plain":"text","application/rtf":"doc","text/rtf":"doc","application/vnd.oasis.opendocument.text":"doc","application/pdf":"pdf","application/vnd.openxmlformats-officedocument.wordprocessingml.document":"doc","application/x-docx":"doc","application/msword":"doc","application/vnd.ms-powerpoint":"ppt","application/vnd.openxmlformats-officedocument.presentationml.presentation":"ppt","application/vnd.ms-excel":"xls","application/vnd.openxmlformats-officedocument.spreadsheetml.sheet":"xls","application/vnd.oasis.opendocument.spreadsheet":"xls","image/jpeg":"image","image/pjpeg":"image","image/png":"image","image/gif":"image","image/bmp":"image","image/svg+xml":"image","application/x-rar":"zip","application/x-rar-compressed":"zip","application/x-zip":"zip","application/x-zip-compressed":"zip","application/xml":"code","application/zip":"zip","audio/mp3":"audio","audio/mpeg":"audio","audio/basic":"audio","audio/mid":"audio","audio/3gpp":"audio","audio/x-aiff":"audio","audio/x-m4a":"audio","audio/x-mpegurl":"audio","audio/x-ms-wma":"audio","audio/x-pn-realaudio":"audio","audio/x-wav":"audio","audio/mp4":"audio","audio/wav":"audio","audio/webm":"audio","audio/*":"audio",audio:"audio","video/mpeg":"video","video/quicktime":"video","video/x-la-asf":"video","video/x-ms-asf":"video","video/x-ms-wma":"audio","video/x-ms-wmv":"video","video/x-msvideo":"video","video/x-sgi-movie":"video","video/3gpp":"video","video/mp4":"video","video/webm":"video","video/avi":"video","video/*":"video",video:"video","application/x-shockwave-flash":"flash"}[t]||e.mime_class||"file"}}function r(e){return e["content-type"]||e.content_type||e.type}},syYy:function(e,t,n){"use strict"
var o=n("vAQ1")
var i=n("ZoNA")
var r=n("NOPk").underscore
e.exports=function(e){e=i(e)
var t=r(e)
var n=o(e.length+":"+e).toString(16)
return t+"_"+n}},t6i0:function(e,t){function n(){var e=window.pageYOffset
if("number"==typeof e)return{top:e,left:window.pageXOffset}
return{top:document.documentElement.scrollTop,left:document.documentElement.scrollLeft}}function o(e){return parseInt(e,10)}e.exports=function(e){var t=e.getBoundingClientRect()
var i=n()
return{top:o(t.top+i.top),left:o(t.left+i.left),width:o(t.right-t.left),height:o(t.bottom-t.top)}}},uTvJ:function(e,t,n){"use strict"
n.d(t,"a",(function(){return r}))
var o=n("/7Jz")
const i=3
function r(e,t=i){const n=document.createElement("div")
Object.assign(n.style,{width:e.width+2*t+"px",height:e.height+2*t+"px",left:e.left-t+"px",top:e.top-t+"px",pointerEvents:"none"})
n.className=Object(o["css"])(a.indicator,a.enter)
document.body.appendChild(n)
n.className=Object(o["css"])(a.indicator,a.enter,a.active)
const r=setTimeout(()=>{n.className=Object(o["css"])(a.indicator,a.leave)},900)
n.addEventListener("mouseover",()=>{clearTimeout(r)
n.className=Object(o["css"])(a.indicator,a.leaveFast)})
setTimeout(()=>document.body.removeChild(n),2e3)
return n}const a=o["StyleSheet"].create({indicator:{border:"2px solid #870",backgroundColor:"#fd0",position:"absolute",display:"block",borderRadius:"5px",zIndex:999999},enter:{opacity:0},active:{transition:"opacity 0.4s",opacity:.8},leave:{transition:"opacity 0.6s",opacity:0},leaveFast:{transition:"opacity 0.2s",opacity:0}})},vM4J:function(e,t,n){"use strict"
n.d(t,"a",(function(){return x}))
var o=n("VTBJ")
var i=n("1OyB")
var r=n("vuIU")
var a=n("Ji7U")
var c=n("LK+K")
var s=n("q1tI")
var l=n.n(s)
var d=n("hPGw")
var u=l.a.createElement("path",{d:"M790.588235,959.588235 L1016.47059,959.588235 L1016.47059,733.705882 L790.588235,733.705882 L790.588235,959.588235 Z M1129.41176,1298.41176 L1355.29412,1298.41176 L1355.29412,1072.52941 L1129.41176,1072.52941 L1129.41176,1298.41176 Z M790.588235,1298.41176 L1016.47059,1298.41176 L1016.47059,1072.52941 L790.588235,1072.52941 L790.588235,1298.41176 Z M451.764706,1298.41176 L677.647059,1298.41176 L677.647059,1072.52941 L451.764706,1072.52941 L451.764706,1298.41176 Z M451.764706,959.588235 L677.647059,959.588235 L677.647059,733.705882 L451.764706,733.705882 L451.764706,959.588235 Z M1355.29412,281.941176 L1355.29412,733.705882 L1807.05882,733.705882 L1807.05882,1637.23529 L112.941176,1637.23529 L112.941176,281.941176 L1355.29412,281.941176 Z M1468.23529,305.32 L1783.68,620.764706 L1468.23529,620.764706 L1468.23529,305.32 Z M1870.41882,547.804706 L1541.19529,218.581176 C1509.68471,187.070588 1465.97647,169 1421.47765,169 L5.68434189e-14,169 L5.68434189e-14,1750.17647 L1920,1750.17647 L1920,667.522353 C1920,622.345882 1902.38118,579.767059 1870.41882,547.804706 L1870.41882,547.804706 Z",fillRule:"evenodd",stroke:"none",strokeWidth:"1"})
var x=function(e){Object(a["a"])(n,e)
var t=Object(c["a"])(n)
function n(){Object(i["a"])(this,n)
return t.apply(this,arguments)}Object(r["a"])(n,[{key:"render",value:function(){return l.a.createElement(d["a"],Object.assign({},this.props,{name:"IconMsExcel",viewBox:"0 0 1920 1920"}),u)}}])
n.displayName="IconMsExcelLine"
return n}(s["Component"])
x.glyphName="ms-excel"
x.variant="Line"
x.propTypes=Object(o["a"])({},d["a"].propTypes)},vlle:function(e,t,n){"use strict"
n.d(t,"a",(function(){return r}))
var o=n("BpCD")
var i=n.n(o)
function r(e,t){return i()(e).lighten(t).toRgbString()}},xEkU:function(e,t,n){(function(t){var o=n("bQgK"),i="undefined"===typeof window?t:window,r=["moz","webkit"],a="AnimationFrame",c=i["request"+a],s=i["cancel"+a]||i["cancelRequest"+a]
for(var l=0;!c&&l<r.length;l++){c=i[r[l]+"Request"+a]
s=i[r[l]+"Cancel"+a]||i[r[l]+"CancelRequest"+a]}if(!c||!s){var d=0,u=0,x=[],_=1e3/60
c=function(e){if(0===x.length){var t=o(),n=Math.max(0,_-(t-d))
d=n+t
setTimeout((function(){var e=x.slice(0)
x.length=0
for(var t=0;t<e.length;t++)if(!e[t].cancelled)try{e[t].callback(d)}catch(e){setTimeout((function(){throw e}),0)}}),Math.round(n))}x.push({handle:++u,callback:e,cancelled:false})
return u}
s=function(e){for(var t=0;t<x.length;t++)x[t].handle===e&&(x[t].cancelled=true)}}e.exports=function(e){return c.call(i,e)}
e.exports.cancel=function(){s.apply(i,arguments)}
e.exports.polyfill=function(e){e||(e=i)
e.requestAnimationFrame=c
e.cancelAnimationFrame=s}}).call(this,n("yLpj"))},"z7I/":function(e,t,n){"use strict"
n.d(t,"a",(function(){return r}))
n.d(t,"b",(function(){return a}))
const o="body.is-masquerading-or-student-view"
let i=null
const r=()=>{if(!i){const e=document.querySelector(o)
i=e?"calc(100vh - 50px)":"100vh"}return i}
const a=e=>{const t=window.location.origin
return new URL(e,t).origin!==t}}}])

//# sourceMappingURL=30-c-dba287050f.js.map