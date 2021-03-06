<style>
@charset "UTF-8";
/**
* Template Styles
*
* [Table of contents]
*   1. Bootstrap Framework
*     1.1 Bootstrap Mixins
*     1.2 Bootstrap Normalize
*     1.3 Bootstrap Print
*     1.4 Bootstrap Scaffolding
*     1.5 Bootstrap Type
*     1.6 Bootstrap Code
*     1.7 Bootstrap Tables
*     1.8 Bootstrap Forms
*     1.9 Bootstrap Buttons
*     1.10 Bootstrap Grid
*     1.11 Bootstrap Component-animations
*     1.12 Bootstrap dropdowns
*     1.13 Bootstrap button-groups
*     1.14 Bootstrap input-groups
*     1.15 Bootstrap navs
*     1.16 Bootstrap navbar
*     1.17 Bootstrap breadcrumbs
*     1.18 Bootstrap pagination
*     1.19 Bootstrap pager
*     1.20 Bootstrap labels
*     1.21 Bootstrap badges
*     1.22 Bootstrap jumbotron
*     1.23 Bootstrap thumbnails
*     1.24 Bootstrap alerts
*     1.25 Bootstrap progress-bars
*     1.26 Bootstrap media
*     1.27 Bootstrap list-group
*     1.28 Bootstrap panels
*     1.29 Bootstrap responsive-embed
*     1.30 Bootstrap wells
*     1.31 Bootstrap close
*     1.32 Bootstrap glyphicons
*     1.33 Bootstrap modals
*     1.34 Bootstrap tooltip
*     1.35 Bootstrap popovers
*     1.36 Bootstrap carousel
*     1.37 Bootstrap utilities
*     1.38 Bootstrap responsive-utilities
*   2. Bootstrap Toolkit Styles
*     2.2 Custom mixins-custom
*     2.3 Custom reset
*     2.4 Custom flex-grid
*     2.5 Custom text-responsive
*     2.6 Custom pull-responsive
*     2.7 Custom visibility-responsive
*     2.8 Custom buttons-custom
*     2.9 Custom icons
*     2.10 Custom fl-glypho
*     2.11 Custom restaurant
*     2.12 Custom thumbnails-custom
*     2.13 Custom scaffolding-custom
*     2.14 Custom sections
*     2.15 Custom jumbotron-custom
*     2.16 Custom utilities-custom
*     2.17 Custom type-custom
*     2.18 Custom pricing-table-custom
*     2.19 Custom product-custom
*     2.20 Custom panels-custom
*     2.21 Custom fl-bigmug-line.
*   3. Bootstrap Toolkit Plugins Styles
*     3.1 Plugins animate
*     3.2 Plugins rd-navbar
*     3.3 Plugins ui-to-top
*     3.4 Plugins scrollspy
*     3.5 Plugins rd-google-map
*     3.6 Plugins rd-mailform
*     3.7 Plugins rd-validator
*/
/*
 * Bootstrap Framework
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}

body {
  margin: 0;
}

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}

audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}

audio:not([controls]) {
  display: none;
  height: 0;
}

[hidden],
template {
  display: none;
}

a {
  background-color: transparent;
}

a:active,
a:hover {
  outline: 0;
}

abbr[title] {
  border-bottom: 1px dotted;
}

b,
strong {
  font-weight: bold;
}

dfn {
  font-style: italic;
}

h1 {
  font-size: 2em;
  margin: 0.67em 0;
}

mark {
  background: #ff0;
  color: #000;
}

small {
  font-size: 80%;
}

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sup {
  top: -0.5em;
}

sub {
  bottom: -0.25em;
}

img {
  border: 0;
}

svg:not(:root) {
  overflow: hidden;
}

figure {
  margin: 1em 40px;
}

hr {
  box-sizing: content-box;
  height: 0;
}

pre {
  overflow: auto;
}

code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}

button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}

button {
  overflow: visible;
}

button,
select {
  text-transform: none;
}

button,
html input[type="button"], input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}

button[disabled],
html input[disabled] {
  cursor: default;
}

button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}

input {
  line-height: normal;
}

input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}

input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}

input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}

input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}

fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}

legend {
  border: 0;
  padding: 0;
}

textarea {
  overflow: auto;
}

optgroup {
  font-weight: bold;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}

td,
th {
  padding: 0;
}

/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    color: #000 !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}

* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}

*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}

html {
  font-size: 10px;
  -webkit-tap-highlight-color: transparent;
}

body {
  font-family: "Roboto", sans-serif;
  font-size: 18px;
  line-height: 1.55556;
  color: #cdcdcd;
  background-color: #fff;
}

input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}

a {
  color: #e89e00;
  text-decoration: none;
}

a:hover,
a:focus {
  color: #e89e00;
  text-decoration: none;
}

a:focus {
  outline: thin dotted;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}

figure {
  margin: 0;
}

img {
  vertical-align: middle;
}

.img-responsive {
  display: block;
  max-width: 100%;
  height: auto;
}

.img-rounded {
  border-radius: 6px;
}

.img-thumbnail {
  padding: 4px;
  line-height: 1.55556;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 0px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}

.img-circle {
  border-radius: 50%;
}

hr {
  margin-top: 28px;
  margin-bottom: 28px;
  border: 0;
  border-top: 1px solid white;
}

.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}

.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}

[role="button"] {
  cursor: pointer;
}

h1, h2, h3, h4, h5, h6,
.h1, .h2, .h3, .h4, .h5, .h6 {
  font-family: "Cinzel", serif;
  font-weight: 700;
  line-height: 1.1;
  color: #fff;
}

h1 small,
h1 .small, h2 small,
h2 .small, h3 small,
h3 .small, h4 small,
h4 .small, h5 small,
h5 .small, h6 small,
h6 .small,
.h1 small,
.h1 .small, .h2 small,
.h2 .small, .h3 small,
.h3 .small, .h4 small,
.h4 .small, .h5 small,
.h5 .small, .h6 small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: white;
}

h1, .h1,
h2, .h2,
h3, .h3 {
  margin-top: 28px;
  margin-bottom: 14px;
}

h1 small,
h1 .small, .h1 small,
.h1 .small,
h2 small,
h2 .small, .h2 small,
.h2 .small,
h3 small,
h3 .small, .h3 small,
.h3 .small {
  font-size: 65%;
}

h4, .h4,
h5, .h5,
h6, .h6 {
  margin-top: 14px;
  margin-bottom: 14px;
}

h4 small,
h4 .small, .h4 small,
.h4 .small,
h5 small,
h5 .small, .h5 small,
.h5 .small,
h6 small,
h6 .small, .h6 small,
.h6 .small {
  font-size: 75%;
}

h1, .h1 {
  font-size: 64px;
}

h2, .h2 {
  font-size: 42px;
}

h3, .h3 {
  font-size: 36px;
}

h4, .h4 {
  font-size: 30px;
}

h5, .h5 {
  font-size: 24px;
}

h6, .h6 {
  font-size: 22px;
}

p {
  margin: 0 0 14px;
}

.lead {
  margin-bottom: 28px;
  font-size: 20px;
  font-weight: 300;
  line-height: 1.4;
}

@media (min-width: 768px) {
  .lead {
    font-size: 27px;
  }
}

small,
.small {
  font-size: 88%;
}

mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}

.text-left {
  text-align: left;
}

.text-right {
  text-align: right;
}

.text-center {
  text-align: center;
}

.text-justify {
  text-align: justify;
}

.text-nowrap {
  white-space: nowrap;
}

.text-lowercase {
  text-transform: lowercase;
}

.text-uppercase, .initialism {
  text-transform: uppercase;
}

.text-capitalize {
  text-transform: capitalize;
}

.text-muted {
  color: white;
}

.text-primary {
  color: #e89e00;
}

a.text-primary:hover,
a.text-primary:focus {
  color: #b57b00;
}

.text-success {
  color: #3c763d;
}

a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}

.text-info {
  color: #31708f;
}

a.text-info:hover,
a.text-info:focus {
  color: #245269;
}

.text-warning {
  color: #8a6d3b;
}

a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}

.text-danger {
  color: #a94442;
}

a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}

.bg-primary {
  color: #fff;
}

.bg-primary {
  background-color: #e89e00;
}

a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #b57b00;
}

.bg-success {
  background-color: #dff0d8;
}

a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}

.bg-info {
  background-color: #d9edf7;
}

a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}

.bg-warning {
  background-color: #fcf8e3;
}

a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}

.bg-danger {
  background-color: #f2dede;
}

a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}

.page-header {
  padding-bottom: 13px;
  margin: 56px 0 28px;
  border-bottom: 1px solid white;
}

ul,
ol {
  margin-top: 0;
  margin-bottom: 14px;
}

ul ul,
ul ol,
ol ul,
ol ol {
  margin-bottom: 0;
}

.list-unstyled {
  padding-left: 0;
  list-style: none;
}

.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}

.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}

dl {
  margin-top: 0;
  margin-bottom: 28px;
}

dt,
dd {
  line-height: 1.55556;
}

dt {
  font-weight: bold;
}

dd {
  margin-left: 0;
}

.dl-horizontal dd:before,
.dl-horizontal dd:after {
  content: " ";
  display: table;
}

.dl-horizontal dd:after {
  clear: both;
}

@media (min-width: 768px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}

abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted white;
}

.initialism {
  font-size: 90%;
}

blockquote {
  padding: 14px 28px;
  margin: 0 0 28px;
  font-size: 22.5px;
  border-left: 5px solid white;
}

blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}

blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.55556;
  color: white;
}

blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}

.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid white;
  border-left: 0;
  text-align: right;
}

.blockquote-reverse footer:before,
.blockquote-reverse small:before,
.blockquote-reverse .small:before,
blockquote.pull-right footer:before,
blockquote.pull-right small:before,
blockquote.pull-right .small:before {
  content: '';
}

.blockquote-reverse footer:after,
.blockquote-reverse small:after,
.blockquote-reverse .small:after,
blockquote.pull-right footer:after,
blockquote.pull-right small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}

address {
  margin-bottom: 28px;
  font-style: normal;
  line-height: 1.55556;
}

code,
kbd,
pre,
samp {
  font-family: Menlo, Monaco, Consolas, "Courier New", monospace;
}

code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 0px;
}

kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #fff;
  background-color: #333;
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}

kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}

pre {
  display: block;
  padding: 13.5px;
  margin: 0 0 14px;
  font-size: 17px;
  line-height: 1.55556;
  word-break: break-all;
  word-wrap: break-word;
  color: white;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 0px;
}

pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}

.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}

table {
  background-color: transparent;
}

caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: white;
  text-align: left;
}

th {
  text-align: left;
}

.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 28px;
}

.table > thead > tr > th,
.table > thead > tr > td,
.table > tbody > tr > th,
.table > tbody > tr > td,
.table > tfoot > tr > th,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.55556;
  vertical-align: top;
  border-top: 1px solid #ddd;
}

.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}

.table > caption + thead > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > th,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}

.table > tbody + tbody {
  border-top: 2px solid #ddd;
}

.table .table {
  background-color: #fff;
}

.table-condensed > thead > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > th,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > th,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}

.table-bordered {
  border: 1px solid #ddd;
}

.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > th,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > th,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}

.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}

.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}

.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}

table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}

table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}

.table > thead > tr > td.active,
.table > thead > tr > th.active,
.table > thead > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr > td.active,
.table > tbody > tr > th.active,
.table > tbody > tr.active > td,
.table > tbody > tr.active > th,
.table > tfoot > tr > td.active,
.table > tfoot > tr > th.active,
.table > tfoot > tr.active > td,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}

.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}

.table > thead > tr > td.success,
.table > thead > tr > th.success,
.table > thead > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr > td.success,
.table > tbody > tr > th.success,
.table > tbody > tr.success > td,
.table > tbody > tr.success > th,
.table > tfoot > tr > td.success,
.table > tfoot > tr > th.success,
.table > tfoot > tr.success > td,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}

.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}

.table > thead > tr > td.info,
.table > thead > tr > th.info,
.table > thead > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr > td.info,
.table > tbody > tr > th.info,
.table > tbody > tr.info > td,
.table > tbody > tr.info > th,
.table > tfoot > tr > td.info,
.table > tfoot > tr > th.info,
.table > tfoot > tr.info > td,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}

.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}

.table > thead > tr > td.warning,
.table > thead > tr > th.warning,
.table > thead > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr > td.warning,
.table > tbody > tr > th.warning,
.table > tbody > tr.warning > td,
.table > tbody > tr.warning > th,
.table > tfoot > tr > td.warning,
.table > tfoot > tr > th.warning,
.table > tfoot > tr.warning > td,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}

.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}

.table > thead > tr > td.danger,
.table > thead > tr > th.danger,
.table > thead > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr > td.danger,
.table > tbody > tr > th.danger,
.table > tbody > tr.danger > td,
.table > tbody > tr.danger > th,
.table > tfoot > tr > td.danger,
.table > tfoot > tr > th.danger,
.table > tfoot > tr.danger > td,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}

.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}

.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}

@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 21px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}

fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}

legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 28px;
  font-size: 27px;
  line-height: inherit;
  color: white;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}

label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}

input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}

input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}

input[type="file"] {
  display: block;
}

input[type="range"] {
  display: block;
  width: 100%;
}

select[multiple],
select[size] {
  height: auto;
}

input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: thin dotted;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}

output {
  display: block;
  padding-top: 19px;
  font-size: 18px;
  line-height: 1.55556;
  color: white;
}

.form-control {
  display: block;
  width: 100%;
  height: 66px;
  padding: 18px 39px;
  font-size: 18px;
  line-height: 1.55556;
  color: white;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 0px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s;
  -o-transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s;
  transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s;
}

.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 8px rgba(102, 175, 233, 0.6);
}

.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}

.form-control:-ms-input-placeholder {
  color: #999;
}

.form-control::-webkit-input-placeholder {
  color: #999;
}

.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}

.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: white;
  opacity: 1;
}

.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}

textarea.form-control {
  height: auto;
}

input[type="search"] {
  -webkit-appearance: none;
}

@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 66px;
  }
  input[type="date"].input-sm,
  .input-group-sm > input[type="date"].form-control,
  .input-group-sm > input[type="date"].input-group-addon,
  .input-group-sm > .input-group-btn > input[type="date"].btn,
  .input-group-sm input[type="date"],
  input[type="time"].input-sm,
  .input-group-sm > input[type="time"].form-control,
  .input-group-sm > input[type="time"].input-group-addon,
  .input-group-sm > .input-group-btn > input[type="time"].btn,
  .input-group-sm input[type="time"],
  input[type="datetime-local"].input-sm,
  .input-group-sm > input[type="datetime-local"].form-control,
  .input-group-sm > input[type="datetime-local"].input-group-addon,
  .input-group-sm > .input-group-btn > input[type="datetime-local"].btn,
  .input-group-sm input[type="datetime-local"],
  input[type="month"].input-sm,
  .input-group-sm > input[type="month"].form-control,
  .input-group-sm > input[type="month"].input-group-addon,
  .input-group-sm > .input-group-btn > input[type="month"].btn,
  .input-group-sm input[type="month"] {
    line-height: 52px;
  }
  input[type="date"].input-lg,
  .input-group-lg > input[type="date"].form-control,
  .input-group-lg > input[type="date"].input-group-addon,
  .input-group-lg > .input-group-btn > input[type="date"].btn,
  .input-group-lg input[type="date"],
  input[type="time"].input-lg,
  .input-group-lg > input[type="time"].form-control,
  .input-group-lg > input[type="time"].input-group-addon,
  .input-group-lg > .input-group-btn > input[type="time"].btn,
  .input-group-lg input[type="time"],
  input[type="datetime-local"].input-lg,
  .input-group-lg > input[type="datetime-local"].form-control,
  .input-group-lg > input[type="datetime-local"].input-group-addon,
  .input-group-lg > .input-group-btn > input[type="datetime-local"].btn,
  .input-group-lg input[type="datetime-local"],
  input[type="month"].input-lg,
  .input-group-lg > input[type="month"].form-control,
  .input-group-lg > input[type="month"].input-group-addon,
  .input-group-lg > .input-group-btn > input[type="month"].btn,
  .input-group-lg input[type="month"] {
    line-height: 76.2px;
  }
}

.form-group {
  margin-bottom: 15px;
}

.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}

.radio label,
.checkbox label {
  min-height: 28px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}

.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}

.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}

.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}

.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}

input[type="radio"][disabled],
input[type="radio"].disabled,
fieldset[disabled] input[type="radio"],
input[type="checkbox"][disabled],
input[type="checkbox"].disabled,
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}

.radio-inline.disabled,
fieldset[disabled] .radio-inline,
.checkbox-inline.disabled,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}

.radio.disabled label,
fieldset[disabled] .radio label,
.checkbox.disabled label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}

.form-control-static {
  padding-top: 19px;
  padding-bottom: 19px;
  margin-bottom: 0;
  min-height: 46px;
}

.form-control-static.input-lg,
.input-group-lg > .form-control-static.form-control,
.input-group-lg > .form-control-static.input-group-addon,
.input-group-lg > .input-group-btn > .form-control-static.btn,
.form-control-static.input-sm, .input-group-sm > .form-control-static.form-control,
.input-group-sm > .form-control-static.input-group-addon,
.input-group-sm > .input-group-btn > .form-control-static.btn {
  padding-left: 0;
  padding-right: 0;
}

.input-sm, .input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 52px;
  padding: 13px 37px;
  font-size: 16px;
  line-height: 1.5;
  border-radius: 3px;
}

select.input-sm, .input-group-sm > select.form-control,
.input-group-sm > select.input-group-addon,
.input-group-sm > .input-group-btn > select.btn {
  height: 52px;
  line-height: 52px;
}

textarea.input-sm,
.input-group-sm > textarea.form-control,
.input-group-sm > textarea.input-group-addon,
.input-group-sm > .input-group-btn > textarea.btn,
select[multiple].input-sm, .input-group-sm > select[multiple].form-control,
.input-group-sm > select[multiple].input-group-addon,
.input-group-sm > .input-group-btn > select[multiple].btn {
  height: auto;
}

.form-group-sm .form-control {
  height: 52px;
  padding: 13px 37px;
  font-size: 16px;
  line-height: 1.5;
  border-radius: 3px;
}

.form-group-sm select.form-control {
  height: 52px;
  line-height: 52px;
}

.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}

.form-group-sm .form-control-static {
  height: 52px;
  min-height: 44px;
  padding: 14px 37px;
  font-size: 16px;
  line-height: 1.5;
}

.input-lg, .input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 76.2px;
  padding: 21.6px 46.8px;
  font-size: 23px;
  line-height: 1.33333;
  border-radius: 6px;
}

select.input-lg, .input-group-lg > select.form-control,
.input-group-lg > select.input-group-addon,
.input-group-lg > .input-group-btn > select.btn {
  height: 76.2px;
  line-height: 76.2px;
}

textarea.input-lg,
.input-group-lg > textarea.form-control,
.input-group-lg > textarea.input-group-addon,
.input-group-lg > .input-group-btn > textarea.btn,
select[multiple].input-lg, .input-group-lg > select[multiple].form-control,
.input-group-lg > select[multiple].input-group-addon,
.input-group-lg > .input-group-btn > select[multiple].btn {
  height: auto;
}

.form-group-lg .form-control {
  height: 76.2px;
  padding: 21.6px 46.8px;
  font-size: 23px;
  line-height: 1.33333;
  border-radius: 6px;
}

.form-group-lg select.form-control {
  height: 76.2px;
  line-height: 76.2px;
}

.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}

.form-group-lg .form-control-static {
  height: 76.2px;
  min-height: 51px;
  padding: 22.6px 46.8px;
  font-size: 23px;
  line-height: 1.33333;
}

.has-feedback {
  position: relative;
}

.has-feedback .form-control {
  padding-right: 82.5px;
}

.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 66px;
  height: 66px;
  line-height: 66px;
  text-align: center;
  pointer-events: none;
}

.input-lg + .form-control-feedback,
.input-group-lg > .form-control + .form-control-feedback,
.input-group-lg > .input-group-addon + .form-control-feedback,
.input-group-lg > .input-group-btn > .btn + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 76.2px;
  height: 76.2px;
  line-height: 76.2px;
}

.input-sm + .form-control-feedback,
.input-group-sm > .form-control + .form-control-feedback,
.input-group-sm > .input-group-addon + .form-control-feedback,
.input-group-sm > .input-group-btn > .btn + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 52px;
  height: 52px;
  line-height: 52px;
}

.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}

.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}

.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}

.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}

.has-success .form-control-feedback {
  color: #3c763d;
}

.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}

.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}

.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}

.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}

.has-warning .form-control-feedback {
  color: #8a6d3b;
}

.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}

.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}

.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}

.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}

.has-error .form-control-feedback {
  color: #a94442;
}

.has-feedback label ~ .form-control-feedback {
  top: 33px;
}

.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}

.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: white;
}

@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}

.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 19px;
}

.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 47px;
}

.form-horizontal .form-group {
  margin-left: -15px;
  margin-right: -15px;
}

.form-horizontal .form-group:before,
.form-horizontal .form-group:after {
  content: " ";
  display: table;
}

.form-horizontal .form-group:after {
  clear: both;
}

@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 19px;
  }
}

.form-horizontal .has-feedback .form-control-feedback {
  right: 15px;
}

@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 22.6px;
    font-size: 23px;
  }
}

@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 14px;
    font-size: 16px;
  }
}

.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: 400;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 18px 39px;
  font-size: 18px;
  line-height: 1.55556;
  border-radius: 0px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.btn:focus,
.btn.focus,
.btn:active:focus,
.btn:active.focus,
.btn.active:focus,
.btn.active.focus {
  outline: thin dotted;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}

.btn:hover,
.btn:focus,
.btn.focus {
  color: #fff;
  text-decoration: none;
}

.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}

.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}

a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}

.btn-default {
  color: #fff;
  background-color: #cdcdcd;
  border-color: #cdcdcd;
}

.btn-default:focus,
.btn-default.focus {
  color: #fff;
  background-color: #b3b3b3;
  border-color: #8d8d8d;
}

.btn-default:hover {
  color: #fff;
  background-color: #b3b3b3;
  border-color: #aeaeae;
}

.btn-default:active,
.btn-default.active,
.open > .btn-default.dropdown-toggle {
  color: #fff;
  background-color: #b3b3b3;
  border-color: #aeaeae;
}

.btn-default:active:hover,
.btn-default:active:focus,
.btn-default:active.focus,
.btn-default.active:hover,
.btn-default.active:focus,
.btn-default.active.focus,
.open > .btn-default.dropdown-toggle:hover,
.open > .btn-default.dropdown-toggle:focus,
.open > .btn-default.dropdown-toggle.focus {
  color: #fff;
  background-color: #a2a2a2;
  border-color: #8d8d8d;
}

.btn-default:active,
.btn-default.active,
.open > .btn-default.dropdown-toggle {
  background-image: none;
}

.btn-default.disabled:hover,
.btn-default.disabled:focus,
.btn-default.disabled.focus,
.btn-default[disabled]:hover,
.btn-default[disabled]:focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default:hover,
fieldset[disabled] .btn-default:focus,
fieldset[disabled] .btn-default.focus {
  background-color: #cdcdcd;
  border-color: #cdcdcd;
}

.btn-default .badge {
  color: #cdcdcd;
  background-color: #fff;
}

.btn-primary {
  color: #fff;
  background-color: #e89e00;
  border-color: #e89e00;
}

.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #b57b00;
  border-color: #694700;
}

.btn-primary:hover {
  color: #fff;
  background-color: #b57b00;
  border-color: #ab7400;
}

.btn-primary:active,
.btn-primary.active,
.open > .btn-primary.dropdown-toggle {
  color: #fff;
  background-color: #b57b00;
  border-color: #ab7400;
}

.btn-primary:active:hover,
.btn-primary:active:focus,
.btn-primary:active.focus,
.btn-primary.active:hover,
.btn-primary.active:focus,
.btn-primary.active.focus,
.open > .btn-primary.dropdown-toggle:hover,
.open > .btn-primary.dropdown-toggle:focus,
.open > .btn-primary.dropdown-toggle.focus {
  color: #fff;
  background-color: #916300;
  border-color: #694700;
}

.btn-primary:active,
.btn-primary.active,
.open > .btn-primary.dropdown-toggle {
  background-image: none;
}

.btn-primary.disabled:hover,
.btn-primary.disabled:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled]:hover,
.btn-primary[disabled]:focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary:hover,
fieldset[disabled] .btn-primary:focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #e89e00;
  border-color: #e89e00;
}

.btn-primary .badge {
  color: #e89e00;
  background-color: #fff;
}

.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #5cb85c;
}

.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #2d672d;
}

.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #419641;
}

.btn-success:active,
.btn-success.active,
.open > .btn-success.dropdown-toggle {
  color: #fff;
  background-color: #449d44;
  border-color: #419641;
}

.btn-success:active:hover,
.btn-success:active:focus,
.btn-success:active.focus,
.btn-success.active:hover,
.btn-success.active:focus,
.btn-success.active.focus,
.open > .btn-success.dropdown-toggle:hover,
.open > .btn-success.dropdown-toggle:focus,
.open > .btn-success.dropdown-toggle.focus {
  color: #fff;
  background-color: #398439;
  border-color: #2d672d;
}

.btn-success:active,
.btn-success.active,
.open > .btn-success.dropdown-toggle {
  background-image: none;
}

.btn-success.disabled:hover,
.btn-success.disabled:focus,
.btn-success.disabled.focus,
.btn-success[disabled]:hover,
.btn-success[disabled]:focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success:hover,
fieldset[disabled] .btn-success:focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #5cb85c;
}

.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}

.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #5bc0de;
}

.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1f7e9a;
}

.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #2aabd2;
}

.btn-info:active,
.btn-info.active,
.open > .btn-info.dropdown-toggle {
  color: #fff;
  background-color: #31b0d5;
  border-color: #2aabd2;
}

.btn-info:active:hover,
.btn-info:active:focus,
.btn-info:active.focus,
.btn-info.active:hover,
.btn-info.active:focus,
.btn-info.active.focus,
.open > .btn-info.dropdown-toggle:hover,
.open > .btn-info.dropdown-toggle:focus,
.open > .btn-info.dropdown-toggle.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1f7e9a;
}

.btn-info:active,
.btn-info.active,
.open > .btn-info.dropdown-toggle {
  background-image: none;
}

.btn-info.disabled:hover,
.btn-info.disabled:focus,
.btn-info.disabled.focus,
.btn-info[disabled]:hover,
.btn-info[disabled]:focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info:hover,
fieldset[disabled] .btn-info:focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #5bc0de;
}

.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}

.btn-warning {
  color: #fff;
  background-color: #ffb822;
  border-color: #ffb822;
}

.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #eea200;
  border-color: #a26e00;
}

.btn-warning:hover {
  color: #fff;
  background-color: #eea200;
  border-color: #e49b00;
}

.btn-warning:active,
.btn-warning.active,
.open > .btn-warning.dropdown-toggle {
  color: #fff;
  background-color: #eea200;
  border-color: #e49b00;
}

.btn-warning:active:hover,
.btn-warning:active:focus,
.btn-warning:active.focus,
.btn-warning.active:hover,
.btn-warning.active:focus,
.btn-warning.active.focus,
.open > .btn-warning.dropdown-toggle:hover,
.open > .btn-warning.dropdown-toggle:focus,
.open > .btn-warning.dropdown-toggle.focus {
  color: #fff;
  background-color: #ca8900;
  border-color: #a26e00;
}

.btn-warning:active,
.btn-warning.active,
.open > .btn-warning.dropdown-toggle {
  background-image: none;
}

.btn-warning.disabled:hover,
.btn-warning.disabled:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled]:hover,
.btn-warning[disabled]:focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning:hover,
fieldset[disabled] .btn-warning:focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #ffb822;
  border-color: #ffb822;
}

.btn-warning .badge {
  color: #ffb822;
  background-color: #fff;
}

.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d9534f;
}

.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #8b211e;
}

.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #c12e2a;
}

.btn-danger:active,
.btn-danger.active,
.open > .btn-danger.dropdown-toggle {
  color: #fff;
  background-color: #c9302c;
  border-color: #c12e2a;
}

.btn-danger:active:hover,
.btn-danger:active:focus,
.btn-danger:active.focus,
.btn-danger.active:hover,
.btn-danger.active:focus,
.btn-danger.active.focus,
.open > .btn-danger.dropdown-toggle:hover,
.open > .btn-danger.dropdown-toggle:focus,
.open > .btn-danger.dropdown-toggle.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #8b211e;
}

.btn-danger:active,
.btn-danger.active,
.open > .btn-danger.dropdown-toggle {
  background-image: none;
}

.btn-danger.disabled:hover,
.btn-danger.disabled:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled]:hover,
.btn-danger[disabled]:focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger:hover,
fieldset[disabled] .btn-danger:focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d9534f;
}

.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}

.btn-link {
  color: #e89e00;
  font-weight: normal;
  border-radius: 0;
}

.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}

.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}

.btn-link:hover,
.btn-link:focus {
  color: #e89e00;
  text-decoration: none;
  background-color: transparent;
}

.btn-link[disabled]:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:hover,
fieldset[disabled] .btn-link:focus {
  color: white;
  text-decoration: none;
}

.btn-lg, .btn-group-lg > .btn {
  padding: 21.6px 46.8px;
  font-size: 23px;
  line-height: 1.33333;
  border-radius: 6px;
}

.btn-sm, .btn-group-sm > .btn {
  padding: 13px 37px;
  font-size: 16px;
  line-height: 1.5;
  border-radius: 3px;
}

.btn-xs, .btn-group-xs > .btn {
  padding: 12px 30px;
  font-size: 16px;
  line-height: 1.5;
  border-radius: 3px;
}

.btn-block {
  display: block;
  width: 100%;
}

.btn-block + .btn-block {
  margin-top: 5px;
}

input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}

.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 15px;
  padding-right: 15px;
}

.container:before,
.container:after {
  content: " ";
  display: table;
}

.container:after {
  clear: both;
}

@media (min-width: 768px) {
  .container {
    width: 750px;
  }
}

@media (min-width: 992px) {
  .container {
    width: 970px;
  }
}

@media (min-width: 1200px) {
  .container {
    width: 1170px;
  }
}

.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 15px;
  padding-right: 15px;
}

.container-fluid:before,
.container-fluid:after {
  content: " ";
  display: table;
}

.container-fluid:after {
  clear: both;
}

.row {
  margin-left: -15px;
  margin-right: -15px;
}

.row:before,
.row:after {
  content: " ";
  display: table;
}

.row:after {
  clear: both;
}

.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 15px;
  padding-right: 15px;
}

.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}

.col-xs-1 {
  width: 8.33333%;
}

.col-xs-2 {
  width: 16.66667%;
}

.col-xs-3 {
  width: 25%;
}

.col-xs-4 {
  width: 33.33333%;
}

.col-xs-5 {
  width: 41.66667%;
}

.col-xs-6 {
  width: 50%;
}

.col-xs-7 {
  width: 58.33333%;
}

.col-xs-8 {
  width: 66.66667%;
}

.col-xs-9 {
  width: 75%;
}

.col-xs-10 {
  width: 83.33333%;
}

.col-xs-11 {
  width: 91.66667%;
}

.col-xs-12 {
  width: 100%;
}

.col-xs-pull-0 {
  right: auto;
}

.col-xs-pull-1 {
  right: 8.33333%;
}

.col-xs-pull-2 {
  right: 16.66667%;
}

.col-xs-pull-3 {
  right: 25%;
}

.col-xs-pull-4 {
  right: 33.33333%;
}

.col-xs-pull-5 {
  right: 41.66667%;
}

.col-xs-pull-6 {
  right: 50%;
}

.col-xs-pull-7 {
  right: 58.33333%;
}

.col-xs-pull-8 {
  right: 66.66667%;
}

.col-xs-pull-9 {
  right: 75%;
}

.col-xs-pull-10 {
  right: 83.33333%;
}

.col-xs-pull-11 {
  right: 91.66667%;
}

.col-xs-pull-12 {
  right: 100%;
}

.col-xs-push-0 {
  left: auto;
}

.col-xs-push-1 {
  left: 8.33333%;
}

.col-xs-push-2 {
  left: 16.66667%;
}

.col-xs-push-3 {
  left: 25%;
}

.col-xs-push-4 {
  left: 33.33333%;
}

.col-xs-push-5 {
  left: 41.66667%;
}

.col-xs-push-6 {
  left: 50%;
}

.col-xs-push-7 {
  left: 58.33333%;
}

.col-xs-push-8 {
  left: 66.66667%;
}

.col-xs-push-9 {
  left: 75%;
}

.col-xs-push-10 {
  left: 83.33333%;
}

.col-xs-push-11 {
  left: 91.66667%;
}

.col-xs-push-12 {
  left: 100%;
}

.col-xs-offset-0 {
  margin-left: 0%;
}

.col-xs-offset-1 {
  margin-left: 8.33333%;
}

.col-xs-offset-2 {
  margin-left: 16.66667%;
}

.col-xs-offset-3 {
  margin-left: 25%;
}

.col-xs-offset-4 {
  margin-left: 33.33333%;
}

.col-xs-offset-5 {
  margin-left: 41.66667%;
}

.col-xs-offset-6 {
  margin-left: 50%;
}

.col-xs-offset-7 {
  margin-left: 58.33333%;
}

.col-xs-offset-8 {
  margin-left: 66.66667%;
}

.col-xs-offset-9 {
  margin-left: 75%;
}

.col-xs-offset-10 {
  margin-left: 83.33333%;
}

.col-xs-offset-11 {
  margin-left: 91.66667%;
}

.col-xs-offset-12 {
  margin-left: 100%;
}

@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-1 {
    width: 8.33333%;
  }
  .col-sm-2 {
    width: 16.66667%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-4 {
    width: 33.33333%;
  }
  .col-sm-5 {
    width: 41.66667%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-7 {
    width: 58.33333%;
  }
  .col-sm-8 {
    width: 66.66667%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-10 {
    width: 83.33333%;
  }
  .col-sm-11 {
    width: 91.66667%;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-pull-1 {
    right: 8.33333%;
  }
  .col-sm-pull-2 {
    right: 16.66667%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-4 {
    right: 33.33333%;
  }
  .col-sm-pull-5 {
    right: 41.66667%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-7 {
    right: 58.33333%;
  }
  .col-sm-pull-8 {
    right: 66.66667%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-10 {
    right: 83.33333%;
  }
  .col-sm-pull-11 {
    right: 91.66667%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-push-1 {
    left: 8.33333%;
  }
  .col-sm-push-2 {
    left: 16.66667%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-4 {
    left: 33.33333%;
  }
  .col-sm-push-5 {
    left: 41.66667%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-7 {
    left: 58.33333%;
  }
  .col-sm-push-8 {
    left: 66.66667%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-10 {
    left: 83.33333%;
  }
  .col-sm-push-11 {
    left: 91.66667%;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66667%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66667%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66667%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66667%;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
}

@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-1 {
    width: 8.33333%;
  }
  .col-md-2 {
    width: 16.66667%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33333%;
  }
  .col-md-5 {
    width: 41.66667%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33333%;
  }
  .col-md-8 {
    width: 66.66667%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-10 {
    width: 83.33333%;
  }
  .col-md-11 {
    width: 91.66667%;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-pull-1 {
    right: 8.33333%;
  }
  .col-md-pull-2 {
    right: 16.66667%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-4 {
    right: 33.33333%;
  }
  .col-md-pull-5 {
    right: 41.66667%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-7 {
    right: 58.33333%;
  }
  .col-md-pull-8 {
    right: 66.66667%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-10 {
    right: 83.33333%;
  }
  .col-md-pull-11 {
    right: 91.66667%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-push-1 {
    left: 8.33333%;
  }
  .col-md-push-2 {
    left: 16.66667%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-4 {
    left: 33.33333%;
  }
  .col-md-push-5 {
    left: 41.66667%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-7 {
    left: 58.33333%;
  }
  .col-md-push-8 {
    left: 66.66667%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-10 {
    left: 83.33333%;
  }
  .col-md-push-11 {
    left: 91.66667%;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333%;
  }
  .col-md-offset-2 {
    margin-left: 16.66667%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333%;
  }
  .col-md-offset-5 {
    margin-left: 41.66667%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333%;
  }
  .col-md-offset-8 {
    margin-left: 66.66667%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333%;
  }
  .col-md-offset-11 {
    margin-left: 91.66667%;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
}

@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-1 {
    width: 8.33333%;
  }
  .col-lg-2 {
    width: 16.66667%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33333%;
  }
  .col-lg-5 {
    width: 41.66667%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33333%;
  }
  .col-lg-8 {
    width: 66.66667%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-10 {
    width: 83.33333%;
  }
  .col-lg-11 {
    width: 91.66667%;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-pull-1 {
    right: 8.33333%;
  }
  .col-lg-pull-2 {
    right: 16.66667%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-4 {
    right: 33.33333%;
  }
  .col-lg-pull-5 {
    right: 41.66667%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-7 {
    right: 58.33333%;
  }
  .col-lg-pull-8 {
    right: 66.66667%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-10 {
    right: 83.33333%;
  }
  .col-lg-pull-11 {
    right: 91.66667%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-push-1 {
    left: 8.33333%;
  }
  .col-lg-push-2 {
    left: 16.66667%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-4 {
    left: 33.33333%;
  }
  .col-lg-push-5 {
    left: 41.66667%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-7 {
    left: 58.33333%;
  }
  .col-lg-push-8 {
    left: 66.66667%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-10 {
    left: 83.33333%;
  }
  .col-lg-push-11 {
    left: 91.66667%;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66667%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66667%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66667%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66667%;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
}

.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}

.fade.in {
  opacity: 1;
}

.collapse {
  display: none;
}

.collapse.in {
  display: block;
}

tr.collapse.in {
  display: table-row;
}

tbody.collapse.in {
  display: table-row-group;
}

.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}

.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}

.dropup,
.dropdown {
  position: relative;
}

.dropdown-toggle:focus {
  outline: 0;
}

.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 18px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 0px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}

.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}

.dropdown-menu .divider {
  height: 1px;
  margin: 13px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}

.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.55556;
  color: white;
  white-space: nowrap;
}

.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #f2f2f2;
  background-color: #f5f5f5;
}

.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: white;
  text-decoration: none;
  outline: 0;
  background-color: #e89e00;
}

.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: white;
}

.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}

.open > .dropdown-menu {
  display: block;
}

.open > a {
  outline: 0;
}

.dropdown-menu-right {
  left: auto;
  right: 0;
}

.dropdown-menu-left {
  left: 0;
  right: auto;
}

.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 16px;
  line-height: 1.55556;
  color: white;
  white-space: nowrap;
}

.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}

.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}

.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}

.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}

@media (min-width: 768px) {
  .navbar-right .dropdown-menu {
    right: 0;
    left: auto;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}

.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}

.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}

.btn-group > .btn:hover,
.btn-group > .btn:focus,
.btn-group > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn:hover,
.btn-group-vertical > .btn:focus,
.btn-group-vertical > .btn:active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}

.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}

.btn-toolbar {
  margin-left: -5px;
}

.btn-toolbar:before,
.btn-toolbar:after {
  content: " ";
  display: table;
}

.btn-toolbar:after {
  clear: both;
}

.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}

.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}

.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}

.btn-group > .btn:first-child {
  margin-left: 0;
}

.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}

.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}

.btn-group > .btn-group {
  float: left;
}

.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}

.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}

.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}

.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}

.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}

.btn-group > .btn-lg + .dropdown-toggle, .btn-group-lg.btn-group > .btn + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}

.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}

.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}

.btn .caret {
  margin-left: 0;
}

.btn-lg .caret, .btn-group-lg > .btn .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}

.dropup .btn-lg .caret, .dropup .btn-group-lg > .btn .caret {
  border-width: 0 5px 5px;
}

.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}

.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after {
  content: " ";
  display: table;
}

.btn-group-vertical > .btn-group:after {
  clear: both;
}

.btn-group-vertical > .btn-group > .btn {
  float: none;
}

.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}

.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}

.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}

.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 0px;
  border-bottom-left-radius: 0px;
}

.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}

.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}

.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}

.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}

.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}

.btn-group-justified > .btn-group .btn {
  width: 100%;
}

.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}

[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}

.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}

.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}

.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}

.input-group .form-control:focus {
  z-index: 3;
}

.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}

.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}

.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}

.input-group-addon {
  padding: 18px 39px;
  font-size: 18px;
  font-weight: normal;
  line-height: 1;
  color: white;
  text-align: center;
  background-color: white;
  border: 1px solid #ccc;
  border-radius: 0px;
}

.input-group-addon.input-sm, .input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .input-group-addon.btn {
  padding: 13px 37px;
  font-size: 16px;
  border-radius: 3px;
}

.input-group-addon.input-lg, .input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .input-group-addon.btn {
  padding: 21.6px 46.8px;
  font-size: 23px;
  border-radius: 6px;
}

.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}

.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}

.input-group-addon:first-child {
  border-right: 0;
}

.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}

.input-group-addon:last-child {
  border-left: 0;
}

.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}

.input-group-btn > .btn {
  position: relative;
}

.input-group-btn > .btn + .btn {
  margin-left: -1px;
}

.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}

.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}

.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}

.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}

.nav:before,
.nav:after {
  content: " ";
  display: table;
}

.nav:after {
  clear: both;
}

.nav > li {
  position: relative;
  display: block;
}

.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}

.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: white;
}

.nav > li.disabled > a {
  color: white;
}

.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: white;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}

.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: white;
  border-color: #e89e00;
}

.nav .nav-divider {
  height: 1px;
  margin: 13px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}

.nav > li > a > img {
  max-width: none;
}

.nav-tabs {
  border-bottom: 1px solid #ddd;
}

.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}

.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.55556;
  border: 1px solid transparent;
  border-radius: 0px 0px 0 0;
}

.nav-tabs > li > a:hover {
  border-color: white white #ddd;
}

.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: white;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}

.nav-pills > li {
  float: left;
}

.nav-pills > li > a {
  border-radius: 0px;
}

.nav-pills > li + li {
  margin-left: 2px;
}

.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: white;
  background-color: #e89e00;
}

.nav-stacked > li {
  float: none;
}

.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}

.nav-justified, .nav-tabs.nav-justified {
  width: 100%;
}

.nav-justified > li, .nav-tabs.nav-justified > li {
  float: none;
}

.nav-justified > li > a, .nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}

.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}

@media (min-width: 768px) {
  .nav-justified > li, .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a, .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}

.nav-tabs-justified, .nav-tabs.nav-justified {
  border-bottom: 0;
}

.nav-tabs-justified > li > a, .nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 0px;
}

.nav-tabs-justified > .active > a,
.nav-tabs.nav-justified > .active > a, .nav-tabs-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:hover, .nav-tabs-justified > .active > a:focus, .nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}

@media (min-width: 768px) {
  .nav-tabs-justified > li > a, .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 0px 0px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs.nav-justified > .active > a, .nav-tabs-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:hover, .nav-tabs-justified > .active > a:focus, .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}

.tab-content > .tab-pane {
  display: none;
}

.tab-content > .active {
  display: block;
}

.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}

.navbar {
  position: relative;
  min-height: 50px;
  margin-bottom: 28px;
  border: 1px solid transparent;
}

.navbar:before,
.navbar:after {
  content: " ";
  display: table;
}

.navbar:after {
  clear: both;
}

@media (min-width: 768px) {
  .navbar {
    border-radius: 0px;
  }
}

.navbar-header:before,
.navbar-header:after {
  content: " ";
  display: table;
}

.navbar-header:after {
  clear: both;
}

@media (min-width: 768px) {
  .navbar-header {
    float: left;
  }
}

.navbar-collapse {
  overflow-x: visible;
  padding-right: 15px;
  padding-left: 15px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}

.navbar-collapse:before,
.navbar-collapse:after {
  content: " ";
  display: table;
}

.navbar-collapse:after {
  clear: both;
}

.navbar-collapse.in {
  overflow-y: auto;
}

@media (min-width: 768px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}

.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}

@media (max-device-width: 480px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}

.container > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-header,
.container-fluid > .navbar-collapse {
  margin-right: -15px;
  margin-left: -15px;
}

@media (min-width: 768px) {
  .container > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-header,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}

.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}

@media (min-width: 768px) {
  .navbar-static-top {
    border-radius: 0;
  }
}

.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}

@media (min-width: 768px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}

.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}

.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}

.navbar-brand {
  float: left;
  padding: 11px 15px;
  font-size: 23px;
  line-height: 28px;
  height: 50px;
}

.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}

.navbar-brand > img {
  display: block;
}

@media (min-width: 768px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: -15px;
  }
}

.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 15px;
  padding: 9px 10px;
  margin-top: 8px;
  margin-bottom: 8px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 0px;
}

.navbar-toggle:focus {
  outline: 0;
}

.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}

.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}

@media (min-width: 768px) {
  .navbar-toggle {
    display: none;
  }
}

.navbar-nav {
  margin: 5.5px -15px;
}

.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 28px;
}

@media (max-width: 767px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 28px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}

@media (min-width: 768px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 11px;
    padding-bottom: 11px;
  }
}

.navbar-form {
  margin-left: -15px;
  margin-right: -15px;
  padding: 10px 15px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -8px;
  margin-bottom: -8px;
}

@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}

@media (max-width: 767px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}

@media (min-width: 768px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}

.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}

.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}

.navbar-btn {
  margin-top: -8px;
  margin-bottom: -8px;
}

.navbar-btn.btn-sm, .btn-group-sm > .navbar-btn.btn {
  margin-top: -1px;
  margin-bottom: -1px;
}

.navbar-btn.btn-xs, .btn-group-xs > .navbar-btn.btn {
  margin-top: 14px;
  margin-bottom: 14px;
}

.navbar-text {
  margin-top: 11px;
  margin-bottom: 11px;
}

@media (min-width: 768px) {
  .navbar-text {
    float: left;
    margin-left: 15px;
    margin-right: 15px;
  }
}

@media (min-width: 768px) {
  .navbar-left {
    float: left !important;
  }
  .navbar-right {
    float: right !important;
    margin-right: -15px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}

.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}

.navbar-default .navbar-brand {
  color: #777;
}

.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}

.navbar-default .navbar-text {
  color: #777;
}

.navbar-default .navbar-nav > li > a {
  color: #777;
}

.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}

.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}

.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}

.navbar-default .navbar-toggle {
  border-color: #ddd;
}

.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}

.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}

.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}

.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}

@media (max-width: 767px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}

.navbar-default .navbar-link {
  color: #777;
}

.navbar-default .navbar-link:hover {
  color: #333;
}

.navbar-default .btn-link {
  color: #777;
}

.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}

.navbar-default .btn-link[disabled]:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:hover,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}

.navbar-inverse {
  background-color: #222;
  border-color: #090909;
}

.navbar-inverse .navbar-brand {
  color: white;
}

.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}

.navbar-inverse .navbar-text {
  color: white;
}

.navbar-inverse .navbar-nav > li > a {
  color: white;
}

.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}

.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #090909;
}

.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}

.navbar-inverse .navbar-toggle {
  border-color: #333;
}

.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}

.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}

.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}

.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #090909;
  color: #fff;
}

@media (max-width: 767px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #090909;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #090909;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: white;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #090909;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}

.navbar-inverse .navbar-link {
  color: white;
}

.navbar-inverse .navbar-link:hover {
  color: #fff;
}

.navbar-inverse .btn-link {
  color: white;
}

.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}

.navbar-inverse .btn-link[disabled]:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:hover,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}

.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 28px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 0px;
}

.breadcrumb > li {
  display: inline-block;
}

.breadcrumb > li + li:before {
  content: "/ ";
  padding: 0 5px;
  color: #ccc;
}

.breadcrumb > .active {
  color: white;
}

.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 28px 0;
  border-radius: 0px;
}

.pagination > li {
  display: inline;
}

.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 18px 39px;
  line-height: 1.55556;
  text-decoration: none;
  color: #e89e00;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}

.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 0px;
  border-top-left-radius: 0px;
}

.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 0px;
  border-top-right-radius: 0px;
}

.pagination > li > a:hover,
.pagination > li > a:focus,
.pagination > li > span:hover,
.pagination > li > span:focus {
  z-index: 2;
  color: #e89e00;
  background-color: white;
  border-color: #ddd;
}

.pagination > .active > a,
.pagination > .active > a:hover,
.pagination > .active > a:focus,
.pagination > .active > span,
.pagination > .active > span:hover,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #e89e00;
  border-color: #e89e00;
  cursor: default;
}

.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: white;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}

.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 21.6px 46.8px;
  font-size: 23px;
  line-height: 1.33333;
}

.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 6px;
  border-top-left-radius: 6px;
}

.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 6px;
  border-top-right-radius: 6px;
}

.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 13px 37px;
  font-size: 16px;
  line-height: 1.5;
}

.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}

.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}

.pager {
  padding-left: 0;
  margin: 28px 0;
  list-style: none;
  text-align: center;
}

.pager:before,
.pager:after {
  content: " ";
  display: table;
}

.pager:after {
  clear: both;
}

.pager li {
  display: inline;
}

.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}

.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: white;
}

.pager .next > a,
.pager .next > span {
  float: right;
}

.pager .previous > a,
.pager .previous > span {
  float: left;
}

.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: white;
  background-color: #fff;
  cursor: not-allowed;
}

.label {
  display: inline;
  padding: 0.2em 0.6em 0.3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}

.label:empty {
  display: none;
}

.btn .label {
  position: relative;
  top: -1px;
}

a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}

.label-default {
  background-color: white;
}

.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #e6e6e6;
}

.label-primary {
  background-color: #e89e00;
}

.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #b57b00;
}

.label-success {
  background-color: #5cb85c;
}

.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}

.label-info {
  background-color: #5bc0de;
}

.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}

.label-warning {
  background-color: #ffb822;
}

.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #eea200;
}

.label-danger {
  background-color: #d9534f;
}

.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}

.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 16px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: white;
  border-radius: 10px;
}

.badge:empty {
  display: none;
}

.btn .badge {
  position: relative;
  top: -1px;
}

.btn-xs .badge,
.btn-group-xs > .btn .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}

.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #e89e00;
  background-color: #fff;
}

.list-group-item > .badge {
  float: right;
}

.list-group-item > .badge + .badge {
  margin-right: 5px;
}

.nav-pills > li > a > .badge {
  margin-left: 3px;
}

a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}

.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: white;
}

.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}

.jumbotron p {
  margin-bottom: 15px;
  font-size: 27px;
  font-weight: 200;
}

.jumbotron > hr {
  border-top-color: #e6e6e6;
}

.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 6px;
  padding-left: 15px;
  padding-right: 15px;
}

.jumbotron .container {
  max-width: 100%;
}

@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 81px;
  }
}

.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 28px;
  line-height: 1.55556;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 0px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}

.thumbnail > img,
.thumbnail a > img {
  display: block;
  max-width: 100%;
  height: auto;
  margin-left: auto;
  margin-right: auto;
}

.thumbnail .caption {
  padding: 9px;
  color: #cdcdcd;
}

a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #e89e00;
}

.alert {
  padding: 15px;
  margin-bottom: 28px;
  border: 1px solid transparent;
  border-radius: 0px;
}

.alert h4 {
  margin-top: 0;
  color: inherit;
}

.alert .alert-link {
  font-weight: bold;
}

.alert > p,
.alert > ul {
  margin-bottom: 0;
}

.alert > p + p {
  margin-top: 5px;
}

.alert-dismissable, .alert-dismissible {
  padding-right: 35px;
}

.alert-dismissable .close, .alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}

.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}

.alert-success hr {
  border-top-color: #c9e2b3;
}

.alert-success .alert-link {
  color: #2b542c;
}

.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}

.alert-info hr {
  border-top-color: #a6e1ec;
}

.alert-info .alert-link {
  color: #245269;
}

.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}

.alert-warning hr {
  border-top-color: #f7e1b5;
}

.alert-warning .alert-link {
  color: #66512c;
}

.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}

.alert-danger hr {
  border-top-color: #e4b9c0;
}

.alert-danger .alert-link {
  color: #843534;
}

@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}

@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}

.progress {
  overflow: hidden;
  height: 28px;
  margin-bottom: 28px;
  background-color: #f5f5f5;
  border-radius: 0px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}

.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 16px;
  line-height: 28px;
  color: #fff;
  text-align: center;
  background-color: #e89e00;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}

.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}

.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}

.progress-bar-success {
  background-color: #5cb85c;
}

.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}

.progress-bar-info {
  background-color: #5bc0de;
}

.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}

.progress-bar-warning {
  background-color: #ffb822;
}

.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}

.progress-bar-danger {
  background-color: #d9534f;
}

.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}

.media {
  margin-top: 15px;
}

.media:first-child {
  margin-top: 0;
}

.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}

.media-body {
  width: 10000px;
}

.media-object {
  display: block;
}

.media-object.img-thumbnail {
  max-width: none;
}

.media-right,
.media > .pull-right {
  padding-left: 10px;
}

.media-left,
.media > .pull-left {
  padding-right: 10px;
}

.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}

.media-middle {
  vertical-align: middle;
}

.media-bottom {
  vertical-align: bottom;
}

.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}

.media-list {
  padding-left: 0;
  list-style: none;
}

.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}

.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}

.list-group-item:first-child {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}

.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 0px;
  border-bottom-left-radius: 0px;
}

a.list-group-item,
button.list-group-item {
  color: #555;
}

a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}

a.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:hover,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}

button.list-group-item {
  width: 100%;
  text-align: left;
}

.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: white;
  color: white;
  cursor: not-allowed;
}

.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}

.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: white;
}

.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: white;
  background-color: #e89e00;
  border-color: #e89e00;
}

.list-group-item.active .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}

.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #ffe7b5;
}

.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}

a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}

a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}

a.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:hover,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}

a.list-group-item-success.active,
a.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active,
button.list-group-item-success.active:hover,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}

.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}

a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}

a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}

a.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:hover,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}

a.list-group-item-info.active,
a.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active,
button.list-group-item-info.active:hover,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}

.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}

a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}

a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}

a.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:hover,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}

a.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active,
button.list-group-item-warning.active:hover,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}

.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}

a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}

a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}

a.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:hover,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}

a.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active,
button.list-group-item-danger.active:hover,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}

.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}

.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}

.panel {
  margin-bottom: 28px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 0px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}

.panel-body {
  padding: 15px;
}

.panel-body:before,
.panel-body:after {
  content: " ";
  display: table;
}

.panel-body:after {
  clear: both;
}

.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: -1px;
  border-top-left-radius: -1px;
}

.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}

.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 21px;
  color: inherit;
}

.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}

.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: -1px;
  border-bottom-left-radius: -1px;
}

.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}

.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}

.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: -1px;
  border-top-left-radius: -1px;
}

.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: -1px;
  border-bottom-left-radius: -1px;
}

.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}

.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}

.list-group + .panel-footer {
  border-top-width: 0;
}

.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}

.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}

.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: -1px;
  border-top-left-radius: -1px;
}

.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: -1px;
  border-top-right-radius: -1px;
}

.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: -1px;
}

.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: -1px;
}

.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: -1px;
  border-bottom-left-radius: -1px;
}

.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: -1px;
  border-bottom-right-radius: -1px;
}

.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: -1px;
}

.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: -1px;
}

.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}

.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}

.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}

.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}

.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}

.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}

.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}

.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}

.panel-group {
  margin-bottom: 28px;
}

.panel-group .panel {
  margin-bottom: 0;
  border-radius: 0px;
}

.panel-group .panel + .panel {
  margin-top: 5px;
}

.panel-group .panel-heading {
  border-bottom: 0;
}

.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}

.panel-group .panel-footer {
  border-top: 0;
}

.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}

.panel-default {
  border-color: #ddd;
}

.panel-default > .panel-heading {
  color: white;
  background-color: #f5f5f5;
  border-color: #ddd;
}

.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}

.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: white;
}

.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}

.panel-primary {
  border-color: #e89e00;
}

.panel-primary > .panel-heading {
  color: #fff;
  background-color: #e89e00;
  border-color: #e89e00;
}

.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #e89e00;
}

.panel-primary > .panel-heading .badge {
  color: #e89e00;
  background-color: #fff;
}

.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #e89e00;
}

.panel-success {
  border-color: #d6e9c6;
}

.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}

.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}

.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}

.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}

.panel-info {
  border-color: #bce8f1;
}

.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}

.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}

.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}

.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}

.panel-warning {
  border-color: #faebcc;
}

.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}

.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}

.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}

.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}

.panel-danger {
  border-color: #ebccd1;
}

.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}

.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}

.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}

.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}

.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}

.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}

.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}

.embed-responsive-4by3 {
  padding-bottom: 75%;
}

.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 0px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}

.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}

.well-lg {
  padding: 24px;
  border-radius: 6px;
}

.well-sm {
  padding: 9px;
  border-radius: 3px;
}

.close {
  float: right;
  font-size: 27px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}

.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}

button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}

@font-face {
  font-family: 'Glyphicons Halflings';
  src: url("../fonts/glyphicons-halflings-regular.eot");
  src: url("../fonts/glyphicons-halflings-regular.eot?#iefix") format("embedded-opentype"), url("../fonts/glyphicons-halflings-regular.woff2") format("woff2"), url("../fonts/glyphicons-halflings-regular.woff") format("woff"), url("../fonts/glyphicons-halflings-regular.ttf") format("truetype"), url("../fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular") format("svg");
}

.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.glyphicon-asterisk:before {
  content: "\002a";
}

.glyphicon-plus:before {
  content: "\002b";
}

.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}

.glyphicon-minus:before {
  content: "\2212";
}

.glyphicon-cloud:before {
  content: "\2601";
}

.glyphicon-envelope:before {
  content: "\2709";
}

.glyphicon-pencil:before {
  content: "\270f";
}

.glyphicon-glass:before {
  content: "\e001";
}

.glyphicon-music:before {
  content: "\e002";
}

.glyphicon-search:before {
  content: "\e003";
}

.glyphicon-heart:before {
  content: "\e005";
}

.glyphicon-star:before {
  content: "\e006";
}

.glyphicon-star-empty:before {
  content: "\e007";
}

.glyphicon-user:before {
  content: "\e008";
}

.glyphicon-film:before {
  content: "\e009";
}

.glyphicon-th-large:before {
  content: "\e010";
}

.glyphicon-th:before {
  content: "\e011";
}

.glyphicon-th-list:before {
  content: "\e012";
}

.glyphicon-ok:before {
  content: "\e013";
}

.glyphicon-remove:before {
  content: "\e014";
}

.glyphicon-zoom-in:before {
  content: "\e015";
}

.glyphicon-zoom-out:before {
  content: "\e016";
}

.glyphicon-off:before {
  content: "\e017";
}

.glyphicon-signal:before {
  content: "\e018";
}

.glyphicon-cog:before {
  content: "\e019";
}

.glyphicon-trash:before {
  content: "\e020";
}

.glyphicon-home:before {
  content: "\e021";
}

.glyphicon-file:before {
  content: "\e022";
}

.glyphicon-time:before {
  content: "\e023";
}

.glyphicon-road:before {
  content: "\e024";
}

.glyphicon-download-alt:before {
  content: "\e025";
}

.glyphicon-download:before {
  content: "\e026";
}

.glyphicon-upload:before {
  content: "\e027";
}

.glyphicon-inbox:before {
  content: "\e028";
}

.glyphicon-play-circle:before {
  content: "\e029";
}

.glyphicon-repeat:before {
  content: "\e030";
}

.glyphicon-refresh:before {
  content: "\e031";
}

.glyphicon-list-alt:before {
  content: "\e032";
}

.glyphicon-lock:before {
  content: "\e033";
}

.glyphicon-flag:before {
  content: "\e034";
}

.glyphicon-headphones:before {
  content: "\e035";
}

.glyphicon-volume-off:before {
  content: "\e036";
}

.glyphicon-volume-down:before {
  content: "\e037";
}

.glyphicon-volume-up:before {
  content: "\e038";
}

.glyphicon-qrcode:before {
  content: "\e039";
}

.glyphicon-barcode:before {
  content: "\e040";
}

.glyphicon-tag:before {
  content: "\e041";
}

.glyphicon-tags:before {
  content: "\e042";
}

.glyphicon-book:before {
  content: "\e043";
}

.glyphicon-bookmark:before {
  content: "\e044";
}

.glyphicon-print:before {
  content: "\e045";
}

.glyphicon-camera:before {
  content: "\e046";
}

.glyphicon-font:before {
  content: "\e047";
}

.glyphicon-bold:before {
  content: "\e048";
}

.glyphicon-italic:before {
  content: "\e049";
}

.glyphicon-text-height:before {
  content: "\e050";
}

.glyphicon-text-width:before {
  content: "\e051";
}

.glyphicon-align-left:before {
  content: "\e052";
}

.glyphicon-align-center:before {
  content: "\e053";
}

.glyphicon-align-right:before {
  content: "\e054";
}

.glyphicon-align-justify:before {
  content: "\e055";
}

.glyphicon-list:before {
  content: "\e056";
}

.glyphicon-indent-left:before {
  content: "\e057";
}

.glyphicon-indent-right:before {
  content: "\e058";
}

.glyphicon-facetime-video:before {
  content: "\e059";
}

.glyphicon-picture:before {
  content: "\e060";
}

.glyphicon-map-marker:before {
  content: "\e062";
}

.glyphicon-adjust:before {
  content: "\e063";
}

.glyphicon-tint:before {
  content: "\e064";
}

.glyphicon-edit:before {
  content: "\e065";
}

.glyphicon-share:before {
  content: "\e066";
}

.glyphicon-check:before {
  content: "\e067";
}

.glyphicon-move:before {
  content: "\e068";
}

.glyphicon-step-backward:before {
  content: "\e069";
}

.glyphicon-fast-backward:before {
  content: "\e070";
}

.glyphicon-backward:before {
  content: "\e071";
}

.glyphicon-play:before {
  content: "\e072";
}

.glyphicon-pause:before {
  content: "\e073";
}

.glyphicon-stop:before {
  content: "\e074";
}

.glyphicon-forward:before {
  content: "\e075";
}

.glyphicon-fast-forward:before {
  content: "\e076";
}

.glyphicon-step-forward:before {
  content: "\e077";
}

.glyphicon-eject:before {
  content: "\e078";
}

.glyphicon-chevron-left:before {
  content: "\e079";
}

.glyphicon-chevron-right:before {
  content: "\e080";
}

.glyphicon-plus-sign:before {
  content: "\e081";
}

.glyphicon-minus-sign:before {
  content: "\e082";
}

.glyphicon-remove-sign:before {
  content: "\e083";
}

.glyphicon-ok-sign:before {
  content: "\e084";
}

.glyphicon-question-sign:before {
  content: "\e085";
}

.glyphicon-info-sign:before {
  content: "\e086";
}

.glyphicon-screenshot:before {
  content: "\e087";
}

.glyphicon-remove-circle:before {
  content: "\e088";
}

.glyphicon-ok-circle:before {
  content: "\e089";
}

.glyphicon-ban-circle:before {
  content: "\e090";
}

.glyphicon-arrow-left:before {
  content: "\e091";
}

.glyphicon-arrow-right:before {
  content: "\e092";
}

.glyphicon-arrow-up:before {
  content: "\e093";
}

.glyphicon-arrow-down:before {
  content: "\e094";
}

.glyphicon-share-alt:before {
  content: "\e095";
}

.glyphicon-resize-full:before {
  content: "\e096";
}

.glyphicon-resize-small:before {
  content: "\e097";
}

.glyphicon-exclamation-sign:before {
  content: "\e101";
}

.glyphicon-gift:before {
  content: "\e102";
}

.glyphicon-leaf:before {
  content: "\e103";
}

.glyphicon-fire:before {
  content: "\e104";
}

.glyphicon-eye-open:before {
  content: "\e105";
}

.glyphicon-eye-close:before {
  content: "\e106";
}

.glyphicon-warning-sign:before {
  content: "\e107";
}

.glyphicon-plane:before {
  content: "\e108";
}

.glyphicon-calendar:before {
  content: "\e109";
}

.glyphicon-random:before {
  content: "\e110";
}

.glyphicon-comment:before {
  content: "\e111";
}

.glyphicon-magnet:before {
  content: "\e112";
}

.glyphicon-chevron-up:before {
  content: "\e113";
}

.glyphicon-chevron-down:before {
  content: "\e114";
}

.glyphicon-retweet:before {
  content: "\e115";
}

.glyphicon-shopping-cart:before {
  content: "\e116";
}

.glyphicon-folder-close:before {
  content: "\e117";
}

.glyphicon-folder-open:before {
  content: "\e118";
}

.glyphicon-resize-vertical:before {
  content: "\e119";
}

.glyphicon-resize-horizontal:before {
  content: "\e120";
}

.glyphicon-hdd:before {
  content: "\e121";
}

.glyphicon-bullhorn:before {
  content: "\e122";
}

.glyphicon-bell:before {
  content: "\e123";
}

.glyphicon-certificate:before {
  content: "\e124";
}

.glyphicon-thumbs-up:before {
  content: "\e125";
}

.glyphicon-thumbs-down:before {
  content: "\e126";
}

.glyphicon-hand-right:before {
  content: "\e127";
}

.glyphicon-hand-left:before {
  content: "\e128";
}

.glyphicon-hand-up:before {
  content: "\e129";
}

.glyphicon-hand-down:before {
  content: "\e130";
}

.glyphicon-circle-arrow-right:before {
  content: "\e131";
}

.glyphicon-circle-arrow-left:before {
  content: "\e132";
}

.glyphicon-circle-arrow-up:before {
  content: "\e133";
}

.glyphicon-circle-arrow-down:before {
  content: "\e134";
}

.glyphicon-globe:before {
  content: "\e135";
}

.glyphicon-wrench:before {
  content: "\e136";
}

.glyphicon-tasks:before {
  content: "\e137";
}

.glyphicon-filter:before {
  content: "\e138";
}

.glyphicon-briefcase:before {
  content: "\e139";
}

.glyphicon-fullscreen:before {
  content: "\e140";
}

.glyphicon-dashboard:before {
  content: "\e141";
}

.glyphicon-paperclip:before {
  content: "\e142";
}

.glyphicon-heart-empty:before {
  content: "\e143";
}

.glyphicon-link:before {
  content: "\e144";
}

.glyphicon-phone:before {
  content: "\e145";
}

.glyphicon-pushpin:before {
  content: "\e146";
}

.glyphicon-usd:before {
  content: "\e148";
}

.glyphicon-gbp:before {
  content: "\e149";
}

.glyphicon-sort:before {
  content: "\e150";
}

.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}

.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}

.glyphicon-sort-by-order:before {
  content: "\e153";
}

.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}

.glyphicon-sort-by-attributes:before {
  content: "\e155";
}

.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}

.glyphicon-unchecked:before {
  content: "\e157";
}

.glyphicon-expand:before {
  content: "\e158";
}

.glyphicon-collapse-down:before {
  content: "\e159";
}

.glyphicon-collapse-up:before {
  content: "\e160";
}

.glyphicon-log-in:before {
  content: "\e161";
}

.glyphicon-flash:before {
  content: "\e162";
}

.glyphicon-log-out:before {
  content: "\e163";
}

.glyphicon-new-window:before {
  content: "\e164";
}

.glyphicon-record:before {
  content: "\e165";
}

.glyphicon-save:before {
  content: "\e166";
}

.glyphicon-open:before {
  content: "\e167";
}

.glyphicon-saved:before {
  content: "\e168";
}

.glyphicon-import:before {
  content: "\e169";
}

.glyphicon-export:before {
  content: "\e170";
}

.glyphicon-send:before {
  content: "\e171";
}

.glyphicon-floppy-disk:before {
  content: "\e172";
}

.glyphicon-floppy-saved:before {
  content: "\e173";
}

.glyphicon-floppy-remove:before {
  content: "\e174";
}

.glyphicon-floppy-save:before {
  content: "\e175";
}

.glyphicon-floppy-open:before {
  content: "\e176";
}

.glyphicon-credit-card:before {
  content: "\e177";
}

.glyphicon-transfer:before {
  content: "\e178";
}

.glyphicon-cutlery:before {
  content: "\e179";
}

.glyphicon-header:before {
  content: "\e180";
}

.glyphicon-compressed:before {
  content: "\e181";
}

.glyphicon-earphone:before {
  content: "\e182";
}

.glyphicon-phone-alt:before {
  content: "\e183";
}

.glyphicon-tower:before {
  content: "\e184";
}

.glyphicon-stats:before {
  content: "\e185";
}

.glyphicon-sd-video:before {
  content: "\e186";
}

.glyphicon-hd-video:before {
  content: "\e187";
}

.glyphicon-subtitles:before {
  content: "\e188";
}

.glyphicon-sound-stereo:before {
  content: "\e189";
}

.glyphicon-sound-dolby:before {
  content: "\e190";
}

.glyphicon-sound-5-1:before {
  content: "\e191";
}

.glyphicon-sound-6-1:before {
  content: "\e192";
}

.glyphicon-sound-7-1:before {
  content: "\e193";
}

.glyphicon-copyright-mark:before {
  content: "\e194";
}

.glyphicon-registration-mark:before {
  content: "\e195";
}

.glyphicon-cloud-download:before {
  content: "\e197";
}

.glyphicon-cloud-upload:before {
  content: "\e198";
}

.glyphicon-tree-conifer:before {
  content: "\e199";
}

.glyphicon-tree-deciduous:before {
  content: "\e200";
}

.glyphicon-cd:before {
  content: "\e201";
}

.glyphicon-save-file:before {
  content: "\e202";
}

.glyphicon-open-file:before {
  content: "\e203";
}

.glyphicon-level-up:before {
  content: "\e204";
}

.glyphicon-copy:before {
  content: "\e205";
}

.glyphicon-paste:before {
  content: "\e206";
}

.glyphicon-alert:before {
  content: "\e209";
}

.glyphicon-equalizer:before {
  content: "\e210";
}

.glyphicon-king:before {
  content: "\e211";
}

.glyphicon-queen:before {
  content: "\e212";
}

.glyphicon-pawn:before {
  content: "\e213";
}

.glyphicon-bishop:before {
  content: "\e214";
}

.glyphicon-knight:before {
  content: "\e215";
}

.glyphicon-baby-formula:before {
  content: "\e216";
}

.glyphicon-tent:before {
  content: "\26fa";
}

.glyphicon-blackboard:before {
  content: "\e218";
}

.glyphicon-bed:before {
  content: "\e219";
}

.glyphicon-apple:before {
  content: "\f8ff";
}

.glyphicon-erase:before {
  content: "\e221";
}

.glyphicon-hourglass:before {
  content: "\231b";
}

.glyphicon-lamp:before {
  content: "\e223";
}

.glyphicon-duplicate:before {
  content: "\e224";
}

.glyphicon-piggy-bank:before {
  content: "\e225";
}

.glyphicon-scissors:before {
  content: "\e226";
}

.glyphicon-bitcoin:before {
  content: "\e227";
}

.glyphicon-btc:before {
  content: "\e227";
}

.glyphicon-xbt:before {
  content: "\e227";
}

.glyphicon-yen:before {
  content: "\00a5";
}

.glyphicon-jpy:before {
  content: "\00a5";
}

.glyphicon-ruble:before {
  content: "\20bd";
}

.glyphicon-rub:before {
  content: "\20bd";
}

.glyphicon-scale:before {
  content: "\e230";
}

.glyphicon-ice-lolly:before {
  content: "\e231";
}

.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}

.glyphicon-education:before {
  content: "\e233";
}

.glyphicon-option-horizontal:before {
  content: "\e234";
}

.glyphicon-option-vertical:before {
  content: "\e235";
}

.glyphicon-menu-hamburger:before {
  content: "\e236";
}

.glyphicon-modal-window:before {
  content: "\e237";
}

.glyphicon-oil:before {
  content: "\e238";
}

.glyphicon-grain:before {
  content: "\e239";
}

.glyphicon-sunglasses:before {
  content: "\e240";
}

.glyphicon-text-size:before {
  content: "\e241";
}

.glyphicon-text-color:before {
  content: "\e242";
}

.glyphicon-text-background:before {
  content: "\e243";
}

.glyphicon-object-align-top:before {
  content: "\e244";
}

.glyphicon-object-align-bottom:before {
  content: "\e245";
}

.glyphicon-object-align-horizontal:before {
  content: "\e246";
}

.glyphicon-object-align-left:before {
  content: "\e247";
}

.glyphicon-object-align-vertical:before {
  content: "\e248";
}

.glyphicon-object-align-right:before {
  content: "\e249";
}

.glyphicon-triangle-right:before {
  content: "\e250";
}

.glyphicon-triangle-left:before {
  content: "\e251";
}

.glyphicon-triangle-bottom:before {
  content: "\e252";
}

.glyphicon-triangle-top:before {
  content: "\e253";
}

.glyphicon-console:before {
  content: "\e254";
}

.glyphicon-superscript:before {
  content: "\e255";
}

.glyphicon-subscript:before {
  content: "\e256";
}

.glyphicon-menu-left:before {
  content: "\e257";
}

.glyphicon-menu-right:before {
  content: "\e258";
}

.glyphicon-menu-down:before {
  content: "\e259";
}

.glyphicon-menu-up:before {
  content: "\e260";
}

.modal-open {
  overflow: hidden;
}

.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}

.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}

.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}

.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}

.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}

.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 6px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}

.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}

.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}

.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}

.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}

.modal-header:before,
.modal-header:after {
  content: " ";
  display: table;
}

.modal-header:after {
  clear: both;
}

.modal-header .close {
  margin-top: -2px;
}

.modal-title {
  margin: 0;
  line-height: 1.55556;
}

.modal-body {
  position: relative;
  padding: 15px;
}

.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}

.modal-footer:before,
.modal-footer:after {
  content: " ";
  display: table;
}

.modal-footer:after {
  clear: both;
}

.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}

.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}

.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}

.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}

@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}

@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}

.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Roboto", sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.55556;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 16px;
  opacity: 0;
  filter: alpha(opacity=0);
}

.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}

.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}

.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}

.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}

.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}

.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 0px;
}

.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}

.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}

.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}

.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}

.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}

.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}

.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}

.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}

.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}

.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Roboto", sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.55556;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 18px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 6px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}

.popover.top {
  margin-top: -10px;
}

.popover.right {
  margin-left: 10px;
}

.popover.bottom {
  margin-top: 10px;
}

.popover.left {
  margin-left: -10px;
}

.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 18px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 5px 5px 0 0;
}

.popover-content {
  padding: 9px 14px;
}

.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}

.popover > .arrow {
  border-width: 11px;
}

.popover > .arrow:after {
  border-width: 10px;
  content: "";
}

.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}

.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}

.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}

.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}

.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}

.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}

.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}

.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}

.carousel {
  position: relative;
}

.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}

.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}

.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
  line-height: 1;
}

@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}

.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}

.carousel-inner > .active {
  left: 0;
}

.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}

.carousel-inner > .next {
  left: 100%;
}

.carousel-inner > .prev {
  left: -100%;
}

.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}

.carousel-inner > .active.left {
  left: -100%;
}

.carousel-inner > .active.right {
  left: 100%;
}

.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: transparent;
}

.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}

.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}

.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}

.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}

.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}

.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}

.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}

.carousel-control .icon-prev:before {
  content: '\2039';
}

.carousel-control .icon-next:before {
  content: '\203a';
}

.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}

.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: transparent;
}

.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}

.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}

.carousel-caption .btn {
  text-shadow: none;
}

@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}

.clearfix:before,
.clearfix:after {
  content: " ";
  display: table;
}

.clearfix:after {
  clear: both;
}

.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}

.pull-right {
  float: right !important;
}

.pull-left {
  float: left !important;
}

.hide {
  display: none !important;
}

.show {
  display: block !important;
}

.invisible {
  visibility: hidden;
}

.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}

.hidden {
  display: none !important;
}

.affix {
  position: fixed;
}

@-ms-viewport {
  width: device-width;
}

.visible-xs {
  display: none !important;
}

.visible-sm {
  display: none !important;
}

.visible-md {
  display: none !important;
}

.visible-lg {
  display: none !important;
}

.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}

@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}

@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}

@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}

@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}

@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}

@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}

@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}

@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}

@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}

@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}

@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}

@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}

@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}

@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}

@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}

.visible-print {
  display: none !important;
}

@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}

.visible-print-block {
  display: none !important;
}

@media print {
  .visible-print-block {
    display: block !important;
  }
}

.visible-print-inline {
  display: none !important;
}

@media print {
  .visible-print-inline {
    display: inline !important;
  }
}

.visible-print-inline-block {
  display: none !important;
}

@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}

@media print {
  .hidden-print {
    display: none !important;
  }
}

/*
 * Bootstrap Toolkit
 */
.shell {
  margin-right: auto;
  margin-left: auto;
  padding-left: 15px;
  padding-right: 15px;
  min-width: 300px;
  max-width: 480px;
}

@media (min-width: 768px) {
  .shell {
    max-width: 750px;
  }
}

@media (min-width: 992px) {
  .shell {
    max-width: 970px;
  }
}

@media (min-width: 1200px) {
  .shell {
    max-width: 1200px;
  }
}

@media (min-width: 1800px) {
  .shell.shell-wide {
    max-width: 1800px;
  }
}

.range {
  margin-left: -15px;
  margin-right: -15px;
}

[class*="cell-"] {
  padding-left: 15px;
  padding-right: 15px;
}

html.lt-ie-10 * + .range,
* + .range {
  margin-top: 60px;
}

html.lt-ie-10 * + [class*='cell-'],
* + [class*='cell-'],
html.lt-ie-10 * + .range-sm,
* + .range-sm {
  margin-top: 30px;
}

html.lt-ie-10 * + .range-lg,
* + .range-lg {
  margin-top: 90px;
}

html.lt-ie-10 .range-condensed,
.range-condensed {
  margin-left: 0;
  margin-right: 0;
}

html.lt-ie-10 .range-condensed > [class*='cell'],
.range-condensed > [class*='cell'] {
  padding-left: 0;
  padding-right: 0;
}

html.lt-ie-10 .range-condensed > * + [class*='cell'],
.range-condensed > * + [class*='cell'] {
  margin-top: 0;
}

@media (min-width: 480px) {
  .range {
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -ms-flex: 0 1 auto;
    -webkit-flex: 0 1 auto;
    flex: 0 1 auto;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
  .range > [class*='cell'] {
    -ms-flex: 0 0 auto;
    -webkit-flex: 0 0 auto;
    flex: 0 0 auto;
    -webkit-flex-basis: 100%;
    -ms-flex-preferred-size: 100%;
    flex-basis: 100%;
    max-width: 100%;
  }
}

@media (min-width: 480px) {
  * + [class*="cell-xs-"] {
    margin-top: 0;
  }
  .range-xs-center {
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
  .range-xs-left {
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }
  .range-xs-right {
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;
  }
  .range-xs-justify {
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
  }
  .range-xs-around {
    -webkit-justify-content: space-around;
    -ms-flex-pack: distribute;
    justify-content: space-around;
  }
  .range-xs-top {
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }
  .range-xs {
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
  }
  .range-xs-reverse {
    -webkit-flex-direction: row-reverse;
    -ms-flex-direction: row-reverse;
    flex-direction: row-reverse;
  }
  .range-xs-middle {
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }
  .range-xs-bottom {
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
  }
  .cell-xs-top {
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
  }
  .cell-xs-middle {
    -webkit-align-self: center;
    -ms-flex-item-align: center;
    align-self: center;
  }
  .cell-xs-bottom {
    -webkit-align-self: flex-end;
    -ms-flex-item-align: end;
    align-self: flex-end;
  }
  .range > .cell-xs-preffix-0 {
    margin-left: 0%;
  }
  .range > .cell-xs-1 {
    -webkit-flex-basis: 8.33333%;
    -ms-flex-preferred-size: 8.33333%;
    flex-basis: 8.33333%;
    max-width: 8.33333%;
  }
  .range > .cell-xs-preffix-1 {
    margin-left: 8.33333%;
  }
  .range > .cell-xs-push-1 {
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
  }
  .range > .cell-xs-2 {
    -webkit-flex-basis: 16.66667%;
    -ms-flex-preferred-size: 16.66667%;
    flex-basis: 16.66667%;
    max-width: 16.66667%;
  }
  .range > .cell-xs-preffix-2 {
    margin-left: 16.66667%;
  }
  .range > .cell-xs-push-2 {
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
  }
  .range > .cell-xs-3 {
    -webkit-flex-basis: 25%;
    -ms-flex-preferred-size: 25%;
    flex-basis: 25%;
    max-width: 25%;
  }
  .range > .cell-xs-preffix-3 {
    margin-left: 25%;
  }
  .range > .cell-xs-push-3 {
    -webkit-order: 3;
    -ms-flex-order: 3;
    order: 3;
  }
  .range > .cell-xs-4 {
    -webkit-flex-basis: 33.33333%;
    -ms-flex-preferred-size: 33.33333%;
    flex-basis: 33.33333%;
    max-width: 33.33333%;
  }
  .range > .cell-xs-preffix-4 {
    margin-left: 33.33333%;
  }
  .range > .cell-xs-push-4 {
    -webkit-order: 4;
    -ms-flex-order: 4;
    order: 4;
  }
  .range > .cell-xs-5 {
    -webkit-flex-basis: 41.66667%;
    -ms-flex-preferred-size: 41.66667%;
    flex-basis: 41.66667%;
    max-width: 41.66667%;
  }
  .range > .cell-xs-preffix-5 {
    margin-left: 41.66667%;
  }
  .range > .cell-xs-push-5 {
    -webkit-order: 5;
    -ms-flex-order: 5;
    order: 5;
  }
  .range > .cell-xs-6 {
    -webkit-flex-basis: 50%;
    -ms-flex-preferred-size: 50%;
    flex-basis: 50%;
    max-width: 50%;
  }
  .range > .cell-xs-preffix-6 {
    margin-left: 50%;
  }
  .range > .cell-xs-push-6 {
    -webkit-order: 6;
    -ms-flex-order: 6;
    order: 6;
  }
  .range > .cell-xs-7 {
    -webkit-flex-basis: 58.33333%;
    -ms-flex-preferred-size: 58.33333%;
    flex-basis: 58.33333%;
    max-width: 58.33333%;
  }
  .range > .cell-xs-preffix-7 {
    margin-left: 58.33333%;
  }
  .range > .cell-xs-push-7 {
    -webkit-order: 7;
    -ms-flex-order: 7;
    order: 7;
  }
  .range > .cell-xs-8 {
    -webkit-flex-basis: 66.66667%;
    -ms-flex-preferred-size: 66.66667%;
    flex-basis: 66.66667%;
    max-width: 66.66667%;
  }
  .range > .cell-xs-preffix-8 {
    margin-left: 66.66667%;
  }
  .range > .cell-xs-push-8 {
    -webkit-order: 8;
    -ms-flex-order: 8;
    order: 8;
  }
  .range > .cell-xs-9 {
    -webkit-flex-basis: 75%;
    -ms-flex-preferred-size: 75%;
    flex-basis: 75%;
    max-width: 75%;
  }
  .range > .cell-xs-preffix-9 {
    margin-left: 75%;
  }
  .range > .cell-xs-push-9 {
    -webkit-order: 9;
    -ms-flex-order: 9;
    order: 9;
  }
  .range > .cell-xs-10 {
    -webkit-flex-basis: 83.33333%;
    -ms-flex-preferred-size: 83.33333%;
    flex-basis: 83.33333%;
    max-width: 83.33333%;
  }
  .range > .cell-xs-preffix-10 {
    margin-left: 83.33333%;
  }
  .range > .cell-xs-push-10 {
    -webkit-order: 10;
    -ms-flex-order: 10;
    order: 10;
  }
  .range > .cell-xs-11 {
    -webkit-flex-basis: 91.66667%;
    -ms-flex-preferred-size: 91.66667%;
    flex-basis: 91.66667%;
    max-width: 91.66667%;
  }
  .range > .cell-xs-preffix-11 {
    margin-left: 91.66667%;
  }
  .range > .cell-xs-push-11 {
    -webkit-order: 11;
    -ms-flex-order: 11;
    order: 11;
  }
  .range > .cell-xs-12 {
    -webkit-flex-basis: 100%;
    -ms-flex-preferred-size: 100%;
    flex-basis: 100%;
    max-width: 100%;
  }
  .range > .cell-xs-preffix-12 {
    margin-left: 100%;
  }
  .range > .cell-xs-push-12 {
    -webkit-order: 12;
    -ms-flex-order: 12;
    order: 12;
  }
  .range > .cell-xs-1-5 {
    -webkit-flex-basis: 20%;
    -ms-flex-preferred-size: 20%;
    flex-basis: 20%;
    max-width: 20%;
  }
}

@media (min-width: 768px) {
  * + [class*="cell-sm-"] {
    margin-top: 0;
  }
  .range-sm-center {
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
  .range-sm-left {
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }
  .range-sm-right {
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;
  }
  .range-sm-justify {
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
  }
  .range-sm-around {
    -webkit-justify-content: space-around;
    -ms-flex-pack: distribute;
    justify-content: space-around;
  }
  .range-sm-top {
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }
  .range-sm {
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
  }
  .range-sm-reverse {
    -webkit-flex-direction: row-reverse;
    -ms-flex-direction: row-reverse;
    flex-direction: row-reverse;
  }
  .range-sm-middle {
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }
  .range-sm-bottom {
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
  }
  .cell-sm-top {
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
  }
  .cell-sm-middle {
    -webkit-align-self: center;
    -ms-flex-item-align: center;
    align-self: center;
  }
  .cell-sm-bottom {
    -webkit-align-self: flex-end;
    -ms-flex-item-align: end;
    align-self: flex-end;
  }
  .range > .cell-sm-preffix-0 {
    margin-left: 0%;
  }
  .range > .cell-sm-1 {
    -webkit-flex-basis: 8.33333%;
    -ms-flex-preferred-size: 8.33333%;
    flex-basis: 8.33333%;
    max-width: 8.33333%;
  }
  .range > .cell-sm-preffix-1 {
    margin-left: 8.33333%;
  }
  .range > .cell-sm-push-1 {
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
  }
  .range > .cell-sm-2 {
    -webkit-flex-basis: 16.66667%;
    -ms-flex-preferred-size: 16.66667%;
    flex-basis: 16.66667%;
    max-width: 16.66667%;
  }
  .range > .cell-sm-preffix-2 {
    margin-left: 16.66667%;
  }
  .range > .cell-sm-push-2 {
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
  }
  .range > .cell-sm-3 {
    -webkit-flex-basis: 25%;
    -ms-flex-preferred-size: 25%;
    flex-basis: 25%;
    max-width: 25%;
  }
  .range > .cell-sm-preffix-3 {
    margin-left: 25%;
  }
  .range > .cell-sm-push-3 {
    -webkit-order: 3;
    -ms-flex-order: 3;
    order: 3;
  }
  .range > .cell-sm-4 {
    -webkit-flex-basis: 33.33333%;
    -ms-flex-preferred-size: 33.33333%;
    flex-basis: 33.33333%;
    max-width: 33.33333%;
  }
  .range > .cell-sm-preffix-4 {
    margin-left: 33.33333%;
  }
  .range > .cell-sm-push-4 {
    -webkit-order: 4;
    -ms-flex-order: 4;
    order: 4;
  }
  .range > .cell-sm-5 {
    -webkit-flex-basis: 41.66667%;
    -ms-flex-preferred-size: 41.66667%;
    flex-basis: 41.66667%;
    max-width: 41.66667%;
  }
  .range > .cell-sm-preffix-5 {
    margin-left: 41.66667%;
  }
  .range > .cell-sm-push-5 {
    -webkit-order: 5;
    -ms-flex-order: 5;
    order: 5;
  }
  .range > .cell-sm-6 {
    -webkit-flex-basis: 50%;
    -ms-flex-preferred-size: 50%;
    flex-basis: 50%;
    max-width: 50%;
  }
  .range > .cell-sm-preffix-6 {
    margin-left: 50%;
  }
  .range > .cell-sm-push-6 {
    -webkit-order: 6;
    -ms-flex-order: 6;
    order: 6;
  }
  .range > .cell-sm-7 {
    -webkit-flex-basis: 58.33333%;
    -ms-flex-preferred-size: 58.33333%;
    flex-basis: 58.33333%;
    max-width: 58.33333%;
  }
  .range > .cell-sm-preffix-7 {
    margin-left: 58.33333%;
  }
  .range > .cell-sm-push-7 {
    -webkit-order: 7;
    -ms-flex-order: 7;
    order: 7;
  }
  .range > .cell-sm-8 {
    -webkit-flex-basis: 66.66667%;
    -ms-flex-preferred-size: 66.66667%;
    flex-basis: 66.66667%;
    max-width: 66.66667%;
  }
  .range > .cell-sm-preffix-8 {
    margin-left: 66.66667%;
  }
  .range > .cell-sm-push-8 {
    -webkit-order: 8;
    -ms-flex-order: 8;
    order: 8;
  }
  .range > .cell-sm-9 {
    -webkit-flex-basis: 75%;
    -ms-flex-preferred-size: 75%;
    flex-basis: 75%;
    max-width: 75%;
  }
  .range > .cell-sm-preffix-9 {
    margin-left: 75%;
  }
  .range > .cell-sm-push-9 {
    -webkit-order: 9;
    -ms-flex-order: 9;
    order: 9;
  }
  .range > .cell-sm-10 {
    -webkit-flex-basis: 83.33333%;
    -ms-flex-preferred-size: 83.33333%;
    flex-basis: 83.33333%;
    max-width: 83.33333%;
  }
  .range > .cell-sm-preffix-10 {
    margin-left: 83.33333%;
  }
  .range > .cell-sm-push-10 {
    -webkit-order: 10;
    -ms-flex-order: 10;
    order: 10;
  }
  .range > .cell-sm-11 {
    -webkit-flex-basis: 91.66667%;
    -ms-flex-preferred-size: 91.66667%;
    flex-basis: 91.66667%;
    max-width: 91.66667%;
  }
  .range > .cell-sm-preffix-11 {
    margin-left: 91.66667%;
  }
  .range > .cell-sm-push-11 {
    -webkit-order: 11;
    -ms-flex-order: 11;
    order: 11;
  }
  .range > .cell-sm-12 {
    -webkit-flex-basis: 100%;
    -ms-flex-preferred-size: 100%;
    flex-basis: 100%;
    max-width: 100%;
  }
  .range > .cell-sm-preffix-12 {
    margin-left: 100%;
  }
  .range > .cell-sm-push-12 {
    -webkit-order: 12;
    -ms-flex-order: 12;
    order: 12;
  }
  .range > .cell-sm-1-5 {
    -webkit-flex-basis: 20%;
    -ms-flex-preferred-size: 20%;
    flex-basis: 20%;
    max-width: 20%;
  }
}

@media (min-width: 992px) {
  * + [class*="cell-md-"] {
    margin-top: 0;
  }
  .range-md-center {
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
  .range-md-left {
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }
  .range-md-right {
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;
  }
  .range-md-justify {
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
  }
  .range-md-around {
    -webkit-justify-content: space-around;
    -ms-flex-pack: distribute;
    justify-content: space-around;
  }
  .range-md-top {
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }
  .range-md {
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
  }
  .range-md-reverse {
    -webkit-flex-direction: row-reverse;
    -ms-flex-direction: row-reverse;
    flex-direction: row-reverse;
  }
  .range-md-middle {
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }
  .range-md-bottom {
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
  }
  .cell-md-top {
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
  }
  .cell-md-middle {
    -webkit-align-self: center;
    -ms-flex-item-align: center;
    align-self: center;
  }
  .cell-md-bottom {
    -webkit-align-self: flex-end;
    -ms-flex-item-align: end;
    align-self: flex-end;
  }
  .range > .cell-md-preffix-0 {
    margin-left: 0%;
  }
  .range > .cell-md-1 {
    -webkit-flex-basis: 8.33333%;
    -ms-flex-preferred-size: 8.33333%;
    flex-basis: 8.33333%;
    max-width: 8.33333%;
  }
  .range > .cell-md-preffix-1 {
    margin-left: 8.33333%;
  }
  .range > .cell-md-push-1 {
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
  }
  .range > .cell-md-2 {
    -webkit-flex-basis: 16.66667%;
    -ms-flex-preferred-size: 16.66667%;
    flex-basis: 16.66667%;
    max-width: 16.66667%;
  }
  .range > .cell-md-preffix-2 {
    margin-left: 16.66667%;
  }
  .range > .cell-md-push-2 {
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
  }
  .range > .cell-md-3 {
    -webkit-flex-basis: 25%;
    -ms-flex-preferred-size: 25%;
    flex-basis: 25%;
    max-width: 25%;
  }
  .range > .cell-md-preffix-3 {
    margin-left: 25%;
  }
  .range > .cell-md-push-3 {
    -webkit-order: 3;
    -ms-flex-order: 3;
    order: 3;
  }
  .range > .cell-md-4 {
    -webkit-flex-basis: 33.33333%;
    -ms-flex-preferred-size: 33.33333%;
    flex-basis: 33.33333%;
    max-width: 33.33333%;
  }
  .range > .cell-md-preffix-4 {
    margin-left: 33.33333%;
  }
  .range > .cell-md-push-4 {
    -webkit-order: 4;
    -ms-flex-order: 4;
    order: 4;
  }
  .range > .cell-md-5 {
    -webkit-flex-basis: 41.66667%;
    -ms-flex-preferred-size: 41.66667%;
    flex-basis: 41.66667%;
    max-width: 41.66667%;
  }
  .range > .cell-md-preffix-5 {
    margin-left: 41.66667%;
  }
  .range > .cell-md-push-5 {
    -webkit-order: 5;
    -ms-flex-order: 5;
    order: 5;
  }
  .range > .cell-md-6 {
    -webkit-flex-basis: 50%;
    -ms-flex-preferred-size: 50%;
    flex-basis: 50%;
    max-width: 50%;
  }
  .range > .cell-md-preffix-6 {
    margin-left: 50%;
  }
  .range > .cell-md-push-6 {
    -webkit-order: 6;
    -ms-flex-order: 6;
    order: 6;
  }
  .range > .cell-md-7 {
    -webkit-flex-basis: 58.33333%;
    -ms-flex-preferred-size: 58.33333%;
    flex-basis: 58.33333%;
    max-width: 58.33333%;
  }
  .range > .cell-md-preffix-7 {
    margin-left: 58.33333%;
  }
  .range > .cell-md-push-7 {
    -webkit-order: 7;
    -ms-flex-order: 7;
    order: 7;
  }
  .range > .cell-md-8 {
    -webkit-flex-basis: 66.66667%;
    -ms-flex-preferred-size: 66.66667%;
    flex-basis: 66.66667%;
    max-width: 66.66667%;
  }
  .range > .cell-md-preffix-8 {
    margin-left: 66.66667%;
  }
  .range > .cell-md-push-8 {
    -webkit-order: 8;
    -ms-flex-order: 8;
    order: 8;
  }
  .range > .cell-md-9 {
    -webkit-flex-basis: 75%;
    -ms-flex-preferred-size: 75%;
    flex-basis: 75%;
    max-width: 75%;
  }
  .range > .cell-md-preffix-9 {
    margin-left: 75%;
  }
  .range > .cell-md-push-9 {
    -webkit-order: 9;
    -ms-flex-order: 9;
    order: 9;
  }
  .range > .cell-md-10 {
    -webkit-flex-basis: 83.33333%;
    -ms-flex-preferred-size: 83.33333%;
    flex-basis: 83.33333%;
    max-width: 83.33333%;
  }
  .range > .cell-md-preffix-10 {
    margin-left: 83.33333%;
  }
  .range > .cell-md-push-10 {
    -webkit-order: 10;
    -ms-flex-order: 10;
    order: 10;
  }
  .range > .cell-md-11 {
    -webkit-flex-basis: 91.66667%;
    -ms-flex-preferred-size: 91.66667%;
    flex-basis: 91.66667%;
    max-width: 91.66667%;
  }
  .range > .cell-md-preffix-11 {
    margin-left: 91.66667%;
  }
  .range > .cell-md-push-11 {
    -webkit-order: 11;
    -ms-flex-order: 11;
    order: 11;
  }
  .range > .cell-md-12 {
    -webkit-flex-basis: 100%;
    -ms-flex-preferred-size: 100%;
    flex-basis: 100%;
    max-width: 100%;
  }
  .range > .cell-md-preffix-12 {
    margin-left: 100%;
  }
  .range > .cell-md-push-12 {
    -webkit-order: 12;
    -ms-flex-order: 12;
    order: 12;
  }
  .range > .cell-md-1-5 {
    -webkit-flex-basis: 20%;
    -ms-flex-preferred-size: 20%;
    flex-basis: 20%;
    max-width: 20%;
  }
}

@media (min-width: 1200px) {
  * + [class*="cell-lg-"] {
    margin-top: 0;
  }
  .range-lg-center {
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
  .range-lg-left {
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }
  .range-lg-right {
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;
  }
  .range-lg-justify {
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
  }
  .range-lg-around {
    -webkit-justify-content: space-around;
    -ms-flex-pack: distribute;
    justify-content: space-around;
  }
  .range-lg-top {
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }
  .range-lg {
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
  }
  .range-lg-reverse {
    -webkit-flex-direction: row-reverse;
    -ms-flex-direction: row-reverse;
    flex-direction: row-reverse;
  }
  .range-lg-middle {
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }
  .range-lg-bottom {
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
  }
  .cell-lg-top {
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
  }
  .cell-lg-middle {
    -webkit-align-self: center;
    -ms-flex-item-align: center;
    align-self: center;
  }
  .cell-lg-bottom {
    -webkit-align-self: flex-end;
    -ms-flex-item-align: end;
    align-self: flex-end;
  }
  .range > .cell-lg-preffix-0 {
    margin-left: 0%;
  }
  .range > .cell-lg-1 {
    -webkit-flex-basis: 8.33333%;
    -ms-flex-preferred-size: 8.33333%;
    flex-basis: 8.33333%;
    max-width: 8.33333%;
  }
  .range > .cell-lg-preffix-1 {
    margin-left: 8.33333%;
  }
  .range > .cell-lg-push-1 {
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
  }
  .range > .cell-lg-2 {
    -webkit-flex-basis: 16.66667%;
    -ms-flex-preferred-size: 16.66667%;
    flex-basis: 16.66667%;
    max-width: 16.66667%;
  }
  .range > .cell-lg-preffix-2 {
    margin-left: 16.66667%;
  }
  .range > .cell-lg-push-2 {
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
  }
  .range > .cell-lg-3 {
    -webkit-flex-basis: 25%;
    -ms-flex-preferred-size: 25%;
    flex-basis: 25%;
    max-width: 25%;
  }
  .range > .cell-lg-preffix-3 {
    margin-left: 25%;
  }
  .range > .cell-lg-push-3 {
    -webkit-order: 3;
    -ms-flex-order: 3;
    order: 3;
  }
  .range > .cell-lg-4 {
    -webkit-flex-basis: 33.33333%;
    -ms-flex-preferred-size: 33.33333%;
    flex-basis: 33.33333%;
    max-width: 33.33333%;
  }
  .range > .cell-lg-preffix-4 {
    margin-left: 33.33333%;
  }
  .range > .cell-lg-push-4 {
    -webkit-order: 4;
    -ms-flex-order: 4;
    order: 4;
  }
  .range > .cell-lg-5 {
    -webkit-flex-basis: 41.66667%;
    -ms-flex-preferred-size: 41.66667%;
    flex-basis: 41.66667%;
    max-width: 41.66667%;
  }
  .range > .cell-lg-preffix-5 {
    margin-left: 41.66667%;
  }
  .range > .cell-lg-push-5 {
    -webkit-order: 5;
    -ms-flex-order: 5;
    order: 5;
  }
  .range > .cell-lg-6 {
    -webkit-flex-basis: 50%;
    -ms-flex-preferred-size: 50%;
    flex-basis: 50%;
    max-width: 50%;
  }
  .range > .cell-lg-preffix-6 {
    margin-left: 50%;
  }
  .range > .cell-lg-push-6 {
    -webkit-order: 6;
    -ms-flex-order: 6;
    order: 6;
  }
  .range > .cell-lg-7 {
    -webkit-flex-basis: 58.33333%;
    -ms-flex-preferred-size: 58.33333%;
    flex-basis: 58.33333%;
    max-width: 58.33333%;
  }
  .range > .cell-lg-preffix-7 {
    margin-left: 58.33333%;
  }
  .range > .cell-lg-push-7 {
    -webkit-order: 7;
    -ms-flex-order: 7;
    order: 7;
  }
  .range > .cell-lg-8 {
    -webkit-flex-basis: 66.66667%;
    -ms-flex-preferred-size: 66.66667%;
    flex-basis: 66.66667%;
    max-width: 66.66667%;
  }
  .range > .cell-lg-preffix-8 {
    margin-left: 66.66667%;
  }
  .range > .cell-lg-push-8 {
    -webkit-order: 8;
    -ms-flex-order: 8;
    order: 8;
  }
  .range > .cell-lg-9 {
    -webkit-flex-basis: 75%;
    -ms-flex-preferred-size: 75%;
    flex-basis: 75%;
    max-width: 75%;
  }
  .range > .cell-lg-preffix-9 {
    margin-left: 75%;
  }
  .range > .cell-lg-push-9 {
    -webkit-order: 9;
    -ms-flex-order: 9;
    order: 9;
  }
  .range > .cell-lg-10 {
    -webkit-flex-basis: 83.33333%;
    -ms-flex-preferred-size: 83.33333%;
    flex-basis: 83.33333%;
    max-width: 83.33333%;
  }
  .range > .cell-lg-preffix-10 {
    margin-left: 83.33333%;
  }
  .range > .cell-lg-push-10 {
    -webkit-order: 10;
    -ms-flex-order: 10;
    order: 10;
  }
  .range > .cell-lg-11 {
    -webkit-flex-basis: 91.66667%;
    -ms-flex-preferred-size: 91.66667%;
    flex-basis: 91.66667%;
    max-width: 91.66667%;
  }
  .range > .cell-lg-preffix-11 {
    margin-left: 91.66667%;
  }
  .range > .cell-lg-push-11 {
    -webkit-order: 11;
    -ms-flex-order: 11;
    order: 11;
  }
  .range > .cell-lg-12 {
    -webkit-flex-basis: 100%;
    -ms-flex-preferred-size: 100%;
    flex-basis: 100%;
    max-width: 100%;
  }
  .range > .cell-lg-preffix-12 {
    margin-left: 100%;
  }
  .range > .cell-lg-push-12 {
    -webkit-order: 12;
    -ms-flex-order: 12;
    order: 12;
  }
  .range > .cell-lg-1-5 {
    -webkit-flex-basis: 20%;
    -ms-flex-preferred-size: 20%;
    flex-basis: 20%;
    max-width: 20%;
  }
}

@media (min-width: 1800px) {
  * + [class*="cell-xl-"] {
    margin-top: 0;
  }
  .range-xl-center {
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
  .range-xl-left {
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }
  .range-xl-right {
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;
  }
  .range-xl-justify {
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
  }
  .range-xl-around {
    -webkit-justify-content: space-around;
    -ms-flex-pack: distribute;
    justify-content: space-around;
  }
  .range-xl-top {
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }
  .range-xl {
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
  }
  .range-xl-reverse {
    -webkit-flex-direction: row-reverse;
    -ms-flex-direction: row-reverse;
    flex-direction: row-reverse;
  }
  .range-xl-middle {
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }
  .range-xl-bottom {
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
  }
  .cell-xl-top {
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
  }
  .cell-xl-middle {
    -webkit-align-self: center;
    -ms-flex-item-align: center;
    align-self: center;
  }
  .cell-xl-bottom {
    -webkit-align-self: flex-end;
    -ms-flex-item-align: end;
    align-self: flex-end;
  }
  .range > .cell-xl-preffix-0 {
    margin-left: 0%;
  }
  .range > .cell-xl-1 {
    -webkit-flex-basis: 8.33333%;
    -ms-flex-preferred-size: 8.33333%;
    flex-basis: 8.33333%;
    max-width: 8.33333%;
  }
  .range > .cell-xl-preffix-1 {
    margin-left: 8.33333%;
  }
  .range > .cell-xl-push-1 {
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
  }
  .range > .cell-xl-2 {
    -webkit-flex-basis: 16.66667%;
    -ms-flex-preferred-size: 16.66667%;
    flex-basis: 16.66667%;
    max-width: 16.66667%;
  }
  .range > .cell-xl-preffix-2 {
    margin-left: 16.66667%;
  }
  .range > .cell-xl-push-2 {
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
  }
  .range > .cell-xl-3 {
    -webkit-flex-basis: 25%;
    -ms-flex-preferred-size: 25%;
    flex-basis: 25%;
    max-width: 25%;
  }
  .range > .cell-xl-preffix-3 {
    margin-left: 25%;
  }
  .range > .cell-xl-push-3 {
    -webkit-order: 3;
    -ms-flex-order: 3;
    order: 3;
  }
  .range > .cell-xl-4 {
    -webkit-flex-basis: 33.33333%;
    -ms-flex-preferred-size: 33.33333%;
    flex-basis: 33.33333%;
    max-width: 33.33333%;
  }
  .range > .cell-xl-preffix-4 {
    margin-left: 33.33333%;
  }
  .range > .cell-xl-push-4 {
    -webkit-order: 4;
    -ms-flex-order: 4;
    order: 4;
  }
  .range > .cell-xl-5 {
    -webkit-flex-basis: 41.66667%;
    -ms-flex-preferred-size: 41.66667%;
    flex-basis: 41.66667%;
    max-width: 41.66667%;
  }
  .range > .cell-xl-preffix-5 {
    margin-left: 41.66667%;
  }
  .range > .cell-xl-push-5 {
    -webkit-order: 5;
    -ms-flex-order: 5;
    order: 5;
  }
  .range > .cell-xl-6 {
    -webkit-flex-basis: 50%;
    -ms-flex-preferred-size: 50%;
    flex-basis: 50%;
    max-width: 50%;
  }
  .range > .cell-xl-preffix-6 {
    margin-left: 50%;
  }
  .range > .cell-xl-push-6 {
    -webkit-order: 6;
    -ms-flex-order: 6;
    order: 6;
  }
  .range > .cell-xl-7 {
    -webkit-flex-basis: 58.33333%;
    -ms-flex-preferred-size: 58.33333%;
    flex-basis: 58.33333%;
    max-width: 58.33333%;
  }
  .range > .cell-xl-preffix-7 {
    margin-left: 58.33333%;
  }
  .range > .cell-xl-push-7 {
    -webkit-order: 7;
    -ms-flex-order: 7;
    order: 7;
  }
  .range > .cell-xl-8 {
    -webkit-flex-basis: 66.66667%;
    -ms-flex-preferred-size: 66.66667%;
    flex-basis: 66.66667%;
    max-width: 66.66667%;
  }
  .range > .cell-xl-preffix-8 {
    margin-left: 66.66667%;
  }
  .range > .cell-xl-push-8 {
    -webkit-order: 8;
    -ms-flex-order: 8;
    order: 8;
  }
  .range > .cell-xl-9 {
    -webkit-flex-basis: 75%;
    -ms-flex-preferred-size: 75%;
    flex-basis: 75%;
    max-width: 75%;
  }
  .range > .cell-xl-preffix-9 {
    margin-left: 75%;
  }
  .range > .cell-xl-push-9 {
    -webkit-order: 9;
    -ms-flex-order: 9;
    order: 9;
  }
  .range > .cell-xl-10 {
    -webkit-flex-basis: 83.33333%;
    -ms-flex-preferred-size: 83.33333%;
    flex-basis: 83.33333%;
    max-width: 83.33333%;
  }
  .range > .cell-xl-preffix-10 {
    margin-left: 83.33333%;
  }
  .range > .cell-xl-push-10 {
    -webkit-order: 10;
    -ms-flex-order: 10;
    order: 10;
  }
  .range > .cell-xl-11 {
    -webkit-flex-basis: 91.66667%;
    -ms-flex-preferred-size: 91.66667%;
    flex-basis: 91.66667%;
    max-width: 91.66667%;
  }
  .range > .cell-xl-preffix-11 {
    margin-left: 91.66667%;
  }
  .range > .cell-xl-push-11 {
    -webkit-order: 11;
    -ms-flex-order: 11;
    order: 11;
  }
  .range > .cell-xl-12 {
    -webkit-flex-basis: 100%;
    -ms-flex-preferred-size: 100%;
    flex-basis: 100%;
    max-width: 100%;
  }
  .range > .cell-xl-preffix-12 {
    margin-left: 100%;
  }
  .range > .cell-xl-push-12 {
    -webkit-order: 12;
    -ms-flex-order: 12;
    order: 12;
  }
  .range > .cell-xl-1-5 {
    -webkit-flex-basis: 20%;
    -ms-flex-preferred-size: 20%;
    flex-basis: 20%;
    max-width: 20%;
  }
}

html.lt-ie-10 .range > .cell-xs-1 {
  margin-left: auto;
  margin-right: auto;
  max-width: 8.33333%;
}

html.lt-ie-10 .range > .cell-xs-2 {
  margin-left: auto;
  margin-right: auto;
  max-width: 16.66667%;
}

html.lt-ie-10 .range > .cell-xs-3 {
  margin-left: auto;
  margin-right: auto;
  max-width: 25%;
}

html.lt-ie-10 .range > .cell-xs-4 {
  margin-left: auto;
  margin-right: auto;
  max-width: 33.33333%;
}

html.lt-ie-10 .range > .cell-xs-5 {
  margin-left: auto;
  margin-right: auto;
  max-width: 41.66667%;
}

html.lt-ie-10 .range > .cell-xs-6 {
  margin-left: auto;
  margin-right: auto;
  max-width: 50%;
}

html.lt-ie-10 .range > .cell-xs-7 {
  margin-left: auto;
  margin-right: auto;
  max-width: 58.33333%;
}

html.lt-ie-10 .range > .cell-xs-8 {
  margin-left: auto;
  margin-right: auto;
  max-width: 66.66667%;
}

html.lt-ie-10 .range > .cell-xs-9 {
  margin-left: auto;
  margin-right: auto;
  max-width: 75%;
}

html.lt-ie-10 .range > .cell-xs-10 {
  margin-left: auto;
  margin-right: auto;
  max-width: 83.33333%;
}

html.lt-ie-10 .range > .cell-xs-11 {
  margin-left: auto;
  margin-right: auto;
  max-width: 91.66667%;
}

html.lt-ie-10 .range > .cell-xs-12 {
  margin-left: auto;
  margin-right: auto;
  max-width: 100%;
}

html.lt-ie-10 .range > .cell-xs-1-5 {
  margin-left: auto;
  margin-right: auto;
  max-width: 20%;
}

html.lt-ie-10 .range > .cell-sm-1 {
  margin-left: auto;
  margin-right: auto;
  max-width: 8.33333%;
}

html.lt-ie-10 .range > .cell-sm-2 {
  margin-left: auto;
  margin-right: auto;
  max-width: 16.66667%;
}

html.lt-ie-10 .range > .cell-sm-3 {
  margin-left: auto;
  margin-right: auto;
  max-width: 25%;
}

html.lt-ie-10 .range > .cell-sm-4 {
  margin-left: auto;
  margin-right: auto;
  max-width: 33.33333%;
}

html.lt-ie-10 .range > .cell-sm-5 {
  margin-left: auto;
  margin-right: auto;
  max-width: 41.66667%;
}

html.lt-ie-10 .range > .cell-sm-6 {
  margin-left: auto;
  margin-right: auto;
  max-width: 50%;
}

html.lt-ie-10 .range > .cell-sm-7 {
  margin-left: auto;
  margin-right: auto;
  max-width: 58.33333%;
}

html.lt-ie-10 .range > .cell-sm-8 {
  margin-left: auto;
  margin-right: auto;
  max-width: 66.66667%;
}

html.lt-ie-10 .range > .cell-sm-9 {
  margin-left: auto;
  margin-right: auto;
  max-width: 75%;
}

html.lt-ie-10 .range > .cell-sm-10 {
  margin-left: auto;
  margin-right: auto;
  max-width: 83.33333%;
}

html.lt-ie-10 .range > .cell-sm-11 {
  margin-left: auto;
  margin-right: auto;
  max-width: 91.66667%;
}

html.lt-ie-10 .range > .cell-sm-12 {
  margin-left: auto;
  margin-right: auto;
  max-width: 100%;
}

html.lt-ie-10 .range > .cell-sm-1-5 {
  margin-left: auto;
  margin-right: auto;
  max-width: 20%;
}

html.lt-ie-10 .range > .cell-md-1 {
  margin-left: auto;
  margin-right: auto;
  max-width: 8.33333%;
}

html.lt-ie-10 .range > .cell-md-2 {
  margin-left: auto;
  margin-right: auto;
  max-width: 16.66667%;
}

html.lt-ie-10 .range > .cell-md-3 {
  margin-left: auto;
  margin-right: auto;
  max-width: 25%;
}

html.lt-ie-10 .range > .cell-md-4 {
  margin-left: auto;
  margin-right: auto;
  max-width: 33.33333%;
}

html.lt-ie-10 .range > .cell-md-5 {
  margin-left: auto;
  margin-right: auto;
  max-width: 41.66667%;
}

html.lt-ie-10 .range > .cell-md-6 {
  margin-left: auto;
  margin-right: auto;
  max-width: 50%;
}

html.lt-ie-10 .range > .cell-md-7 {
  margin-left: auto;
  margin-right: auto;
  max-width: 58.33333%;
}

html.lt-ie-10 .range > .cell-md-8 {
  margin-left: auto;
  margin-right: auto;
  max-width: 66.66667%;
}

html.lt-ie-10 .range > .cell-md-9 {
  margin-left: auto;
  margin-right: auto;
  max-width: 75%;
}

html.lt-ie-10 .range > .cell-md-10 {
  margin-left: auto;
  margin-right: auto;
  max-width: 83.33333%;
}

html.lt-ie-10 .range > .cell-md-11 {
  margin-left: auto;
  margin-right: auto;
  max-width: 91.66667%;
}

html.lt-ie-10 .range > .cell-md-12 {
  margin-left: auto;
  margin-right: auto;
  max-width: 100%;
}

html.lt-ie-10 .range > .cell-md-1-5 {
  margin-left: auto;
  margin-right: auto;
  max-width: 20%;
}

html.lt-ie-10 .range > .cell-lg-1 {
  margin-left: auto;
  margin-right: auto;
  max-width: 8.33333%;
}

html.lt-ie-10 .range > .cell-lg-2 {
  margin-left: auto;
  margin-right: auto;
  max-width: 16.66667%;
}

html.lt-ie-10 .range > .cell-lg-3 {
  margin-left: auto;
  margin-right: auto;
  max-width: 25%;
}

html.lt-ie-10 .range > .cell-lg-4 {
  margin-left: auto;
  margin-right: auto;
  max-width: 33.33333%;
}

html.lt-ie-10 .range > .cell-lg-5 {
  margin-left: auto;
  margin-right: auto;
  max-width: 41.66667%;
}

html.lt-ie-10 .range > .cell-lg-6 {
  margin-left: auto;
  margin-right: auto;
  max-width: 50%;
}

html.lt-ie-10 .range > .cell-lg-7 {
  margin-left: auto;
  margin-right: auto;
  max-width: 58.33333%;
}

html.lt-ie-10 .range > .cell-lg-8 {
  margin-left: auto;
  margin-right: auto;
  max-width: 66.66667%;
}

html.lt-ie-10 .range > .cell-lg-9 {
  margin-left: auto;
  margin-right: auto;
  max-width: 75%;
}

html.lt-ie-10 .range > .cell-lg-10 {
  margin-left: auto;
  margin-right: auto;
  max-width: 83.33333%;
}

html.lt-ie-10 .range > .cell-lg-11 {
  margin-left: auto;
  margin-right: auto;
  max-width: 91.66667%;
}

html.lt-ie-10 .range > .cell-lg-12 {
  margin-left: auto;
  margin-right: auto;
  max-width: 100%;
}

html.lt-ie-10 .range > .cell-lg-1-5 {
  margin-left: auto;
  margin-right: auto;
  max-width: 20%;
}

html.lt-ie-10 .range > [class*="cell-xs-preffix-"],
html.lt-ie-10 .range > [class*="cell-sm-preffix-"],
html.lt-ie-10 .range > [class*="cell-md-preffix-"],
html.lt-ie-10 .range > [class*="cell-lg-preffix-"] {
  margin-left: auto;
}

.text-normal {
  white-space: normal;
}

@media (min-width: 480px) {
  .text-xs-left {
    text-align: left;
  }
  .text-xs-center {
    text-align: center;
  }
  .text-xs-right {
    text-align: right;
  }
  .text-xs-justify {
    text-align: justify;
  }
  .text-xs-nowrap {
    white-space: nowrap;
  }
  .text-xs-normal {
    white-space: normal;
  }
}

@media (min-width: 768px) {
  .text-sm-left {
    text-align: left;
  }
  .text-sm-center {
    text-align: center;
  }
  .text-sm-right {
    text-align: right;
  }
  .text-sm-justify {
    text-align: justify;
  }
  .text-sm-nowrap {
    white-space: nowrap;
  }
  .text-sm-normal {
    white-space: normal;
  }
}

@media (min-width: 992px) {
  .text-md-left {
    text-align: left;
  }
  .text-md-center {
    text-align: center;
  }
  .text-md-right {
    text-align: right;
  }
  .text-md-justify {
    text-align: justify;
  }
  .text-md-nowrap {
    white-space: nowrap;
  }
  .text-md-normal {
    white-space: normal;
  }
}

@media (min-width: 1200px) {
  .text-lg-left {
    text-align: left;
  }
  .text-lg-center {
    text-align: center;
  }
  .text-lg-right {
    text-align: right;
  }
  .text-lg-justify {
    text-align: justify;
  }
  .text-lg-nowrap {
    white-space: nowrap;
  }
  .text-lg-normal {
    white-space: normal;
  }
}

@media (min-width: 1800px) {
  .text-xl-left {
    text-align: left;
  }
  .text-xl-center {
    text-align: center;
  }
  .text-xl-right {
    text-align: right;
  }
  .text-xl-justify {
    text-align: justify;
  }
  .text-xl-nowrap {
    white-space: nowrap;
  }
  .text-xl-normal {
    white-space: normal;
  }
}

.pull-base {
  float: none;
}

@media (min-width: 480px) {
  .pull-xs-left {
    float: left;
  }
  .pull-xs-base {
    float: none;
  }
  .pull-xs-right {
    float: right;
  }
}

@media (min-width: 768px) {
  .pull-sm-left {
    float: left;
  }
  .pull-sm-base {
    float: none;
  }
  .pull-sm-right {
    float: right;
  }
}

@media (min-width: 992px) {
  .pull-md-left {
    float: left;
  }
  .pull-md-base {
    float: none;
  }
  .pull-md-right {
    float: right;
  }
}

@media (min-width: 1200px) {
  .pull-lg-left {
    float: left;
  }
  .pull-lg-base {
    float: none;
  }
  .pull-lg-right {
    float: right;
  }
}

@media (min-width: 1800px) {
  .pull-xl-left {
    float: left;
  }
  .pull-xl-base {
    float: none;
  }
  .pull-xl-right {
    float: right;
  }
}

.visible-block {
  display: block !important;
}

.visible-inline-block {
  display: inline-block !important;
}

.visible-inline {
  display: inline !important;
}

.visible-flex {
  display: -ms-flexbox !important;
  display: -webkit-flex !important;
  display: flex !important;
}

.hidden {
  display: none !important;
}

@media (min-width: 480px) and (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
  .visible-xs-inline-block {
    display: inline-block !important;
  }
  .visible-xs-inline {
    display: inline !important;
  }
  .visible-xs-flex {
    display: -ms-flexbox !important;
    display: -webkit-flex !important;
    display: flex !important;
  }
  .hidden-xs {
    display: none !important;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
  .visible-sm-inline-block {
    display: inline-block !important;
  }
  .visible-sm-inline {
    display: inline !important;
  }
  .visible-sm-flex {
    display: -ms-flexbox !important;
    display: -webkit-flex !important;
    display: flex !important;
  }
  .hidden-sm {
    display: none !important;
  }
}

@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
  .visible-md-inline-block {
    display: inline-block !important;
  }
  .visible-md-inline {
    display: inline !important;
  }
  .visible-md-flex {
    display: -ms-flexbox !important;
    display: -webkit-flex !important;
    display: flex !important;
  }
  .hidden-md {
    display: none !important;
  }
}

@media (min-width: 1200px) and (max-width: 1799px) {
  .visible-lg-block {
    display: block !important;
  }
  .visible-lg-inline-block {
    display: inline-block !important;
  }
  .visible-lg-inline {
    display: inline !important;
  }
  .visible-lg-flex {
    display: -ms-flexbox !important;
    display: -webkit-flex !important;
    display: flex !important;
  }
  .hidden-lg {
    display: none !important;
  }
}

@media (min-width: 1800px) {
  .visible-xl-block {
    display: block !important;
  }
  .visible-xl-inline-block {
    display: inline-block !important;
  }
  .visible-xl-inline {
    display: inline !important;
  }
  .visible-xl-flex {
    display: -ms-flexbox !important;
    display: -webkit-flex !important;
    display: flex !important;
  }
  .hidden-xl {
    display: none !important;
  }
}

.btn {
  font-weight: 700;
  font-family: "Cinzel", serif;
  z-index: 1;
}

.btn:focus,
.btn.focus,
.btn:active:focus,
.btn:active.focus,
.btn.active:focus,
.btn.active.focus {
  outline: none;
  background: #e89e00;
}

.btn-primary {
  color: #fff;
  position: relative;
  overflow: hidden;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

.btn-primary:after {
  content: '';
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 0 0 0 0;
  border-color: #ffb822 transparent transparent transparent;
  position: absolute;
  top: 0;
  left: 0;
  -webkit-transition: 0.5s;
  transition: 0.5s;
  z-index: -1;
}

.btn-primary:focus, .btn-primary:active {
  background-color: #e89e00;
}

.btn-primary:hover {
  box-shadow: 0 0 10px 2px #e89e00;
  background-color: transparent;
  color: #fff;
}

.btn-primary:hover:after {
  border-width: 330px 330px 0 0;
}

.btn-xs, .btn-group-xs > .btn {
  font-size: 20px;
  border-radius: 4px;
}

.btn-sm, .btn-group-sm > .btn {
  text-transform: uppercase;
  font-size: 20px;
  border-radius: 4px;
}

.icon:before {
  position: relative;
  display: inline-block;
  font-weight: 400;
  font-style: normal;
  speak: none;
  text-transform: none;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.icon-default {
  color: #7e7e7e;
  transition: .3s;
}

.icon-default:hover {
  color: #e89e00;
}

.icon-xs {
  font-size: 36px;
}

.icon-sm {
  font-size: 60px;
}

/**
 * Title: Glypho Flaticon Pack
 * Author: Bogdan Rosu
 * Source: http://www.flaticon.com/packs/glypho
 * License:  CC BY 3.0 (http://creativecommons.org/licenses/by/3.0/)
 */
@font-face {
  font-family: "fl-glypho";
  src: url("../fonts/fl-glypho.eot");
  src: url("../fonts/fl-glypho.eot#iefix") format("embedded-opentype"), url("../fonts/fl-glypho.woff") format("woff"), url("../fonts/fl-glypho.ttf") format("truetype"), url("../fonts/fl-glypho.svg") format("svg");
  font-weight: normal;
  font-style: normal;
}

.fl-glypho-ico,
[class^="fl-glypho-"]:before, [class*=" fl-glypho-"]:before,
[class^="fl-glypho-"]:after, [class*=" fl-glypho-"]:after {
  font-family: 'fl-glypho';
  font-size: inherit;
  font-weight: 400;
  font-style: normal;
}

.fl-glypho-armchair4:before {
  content: "\e000";
}

.fl-glypho-behance13:before {
  content: "\e001";
}

.fl-glypho-bell70:before {
  content: "\e002";
}

.fl-glypho-briefcase69:before {
  content: "\e003";
}

.fl-glypho-camera119:before {
  content: "\e004";
}

.fl-glypho-camera120:before {
  content: "\e005";
}

.fl-glypho-chart55:before {
  content: "\e006";
}

.fl-glypho-chat118:before {
  content: "\e007";
}

.fl-glypho-checkbox6:before {
  content: "\e008";
}

.fl-glypho-chronometer:before {
  content: "\e009";
}

.fl-glypho-clipboard:before {
  content: "\e00a";
}

.fl-glypho-coffee128:before {
  content: "\e00b";
}

.fl-glypho-compact disc5:before {
  content: "\e00c";
}

.fl-glypho-directional-sign10:before {
  content: "\e00d";
}

.fl-glypho-document6:before {
  content: "\e00e";
}

.fl-glypho-downloading:before {
  content: "\e00f";
}

.fl-glypho-dribbble:before {
  content: "\e010";
}

.fl-glypho-eye127:before {
  content: "\e011";
}

.fl-glypho-facebook2:before {
  content: "\e012";
}

.fl-glypho-flag97:before {
  content: "\e013";
}

.fl-glypho-flask:before {
  content: "\e014";
}

.fl-glypho-folded-map:before {
  content: "\e015";
}

.fl-glypho-globe35:before {
  content: "\e016";
}

.fl-glypho-google-plus:before {
  content: "\e017";
}

.fl-glypho-happy-mac:before {
  content: "\e018";
}

.fl-glypho-heart-rate:before {
  content: "\e019";
}

.fl-glypho-hearts34:before {
  content: "\e01a";
}

.fl-glypho-house180:before {
  content: "\e01b";
}

.fl-glypho-inbox39:before {
  content: "\e01c";
}

.fl-glypho-inbox40:before {
  content: "\e01d";
}

.fl-glypho-instagram19:before {
  content: "\e01e";
}

.fl-glypho-jar21:before {
  content: "\e01f";
}

.fl-glypho-laptop130:before {
  content: "\e020";
}

.fl-glypho-layers:before {
  content: "\e021";
}

.fl-glypho-light-bulb4:before {
  content: "\e022";
}

.fl-glypho-lightning31:before {
  content: "\e023";
}

.fl-glypho-linkedin:before {
  content: "\e024";
}

.fl-glypho-microphone3:before {
  content: "\e025";
}

.fl-glypho-notebook91:before {
  content: "\e026";
}

.fl-glypho-nut4:before {
  content: "\e027";
}

.fl-glypho-pin66:before {
  content: "\e028";
}

.fl-glypho-plug:before {
  content: "\e029";
}

.fl-glypho-power5:before {
  content: "\e02a";
}

.fl-glypho-present33:before {
  content: "\e02b";
}

.fl-glypho-presentation22:before {
  content: "\e02c";
}

.fl-glypho-purse10:before {
  content: "\e02d";
}

.fl-glypho-pyre:before {
  content: "\e02e";
}

.fl-glypho-quaver3:before {
  content: "\e02f";
}

.fl-glypho-rocket77:before {
  content: "\e030";
}

.fl-glypho-screen84:before {
  content: "\e031";
}

.fl-glypho-share46:before {
  content: "\e032";
}

.fl-glypho-shopping-cart7:before {
  content: "\e033";
}

.fl-glypho-speech-bubble20:before {
  content: "\e034";
}

.fl-glypho-star207:before {
  content: "\e035";
}

.fl-glypho-switch33:before {
  content: "\e036";
}

.fl-glypho-telephone120:before {
  content: "\e037";
}

.fl-glypho-timer42:before {
  content: "\e038";
}

.fl-glypho-truck69:before {
  content: "\e039";
}

.fl-glypho-tumblr1:before {
  content: "\e03a";
}

.fl-glypho-twitter:before {
  content: "\e03b";
}

.fl-glypho-umbrella1:before {
  content: "\e03c";
}

.fl-glypho-uploading2:before {
  content: "\e03d";
}

.fl-glypho-user7:before {
  content: "\e03e";
}

.fl-glypho-video-player:before {
  content: "\e03f";
}

@font-face {
  font-family: 'Restaurant Regular';
  src: url("../fonts/Restaurant-Regular.eot?87209526");
  src: url("../fonts/Restaurant-Regular.eot?87209526#iefix") format("embedded-opentype"), url("../fonts/Restaurant-Regular.woff?87209526") format("woff"), url("../fonts/Restaurant-Regular.ttf?87209526") format("truetype"), url("../fonts/Restaurant-Regular.svg?87209526#mercury") format("svg");
  font-weight: normal;
  font-style: normal;
}

/* Chrome hack: SVG is rendered more smooth in Windozze. 100% magic, uncomment if you need it. */
/* Note, that will break hinting! In other OS-es font will be not as sharp as it could be */
/*
@media screen and (-webkit-min-device-pixel-ratio:0) {
  @font-face {
    font-family: 'mercury';
    src: url('../font/mercury.svg?87209526#mercury') format('svg');
  }
}
*/
[class^="restaurant-icon-"]:before,
[class*="restaurant-icon-"]:before,
.restaurant-ico {
  font-family: "Restaurant Regular";
  font-weight: 400;
  font-style: normal;
  font-size: inherit;
  text-transform: none;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.restaurant-icon-01:before {
  content: '\e800';
}

.restaurant-icon-02:before {
  content: '\e801';
}

.restaurant-icon-03:before {
  content: '\e802';
}

.restaurant-icon-04:before {
  content: '\e803';
}

.restaurant-icon-05:before {
  content: '\e804';
}

.restaurant-icon-06:before {
  content: '\e805';
}

.restaurant-icon-08:before {
  content: '\e806';
}

.restaurant-icon-07:before {
  content: '\e807';
}

.restaurant-icon-09:before {
  content: '\e808';
}

.restaurant-icon-10:before {
  content: '\e809';
}

.restaurant-icon-11:before {
  content: '\e80a';
}

.restaurant-icon-12:before {
  content: '\e80b';
}

.restaurant-icon-13:before {
  content: '\e80c';
}

.restaurant-icon-14:before {
  content: '\e80d';
}

.restaurant-icon-15:before {
  content: '\e80e';
}

.restaurant-icon-16:before {
  content: '\e80f';
}

.restaurant-icon-17:before {
  content: '\e810';
}

.restaurant-icon-18:before {
  content: '\e811';
}

.restaurant-icon-19:before {
  content: '\e812';
}

.restaurant-icon-20:before {
  content: '\e813';
}

.restaurant-icon-36:before {
  content: '\e814';
}

.restaurant-icon-35:before {
  content: '\e815';
}

.restaurant-icon-34:before {
  content: '\e816';
}

.restaurant-icon-33:before {
  content: '\e817';
}

.restaurant-icon-32:before {
  content: '\e818';
}

.restaurant-icon-31:before {
  content: '\e819';
}

.restaurant-icon-30:before {
  content: '\e81a';
}

.restaurant-icon-29:before {
  content: '\e81b';
}

.restaurant-icon-28:before {
  content: '\e81c';
}

.restaurant-icon-27:before {
  content: '\e81d';
}

.restaurant-icon-26:before {
  content: '\e81e';
}

.restaurant-icon-25:before {
  content: '\e81f';
}

.restaurant-icon-24:before {
  content: '\e820';
}

.restaurant-icon-23:before {
  content: '\e821';
}

.restaurant-icon-22:before {
  content: '\e822';
}

.restaurant-icon-21:before {
  content: '\e823';
}

@font-face {
  font-family: 'FontAwesome';
  src: url("../fonts/fontawesome-webfont.eot?v=4.5.0");
  src: url("../fonts/fontawesome-webfont.eot?#iefix&v=4.5.0") format("embedded-opentype"), url("../fonts/fontawesome-webfont.woff2?v=4.5.0") format("woff2"), url("../fonts/fontawesome-webfont.woff?v=4.5.0") format("woff"), url("../fonts/fontawesome-webfont.ttf?v=4.5.0") format("truetype"), url("../fonts/fontawesome-webfont.svg?v=4.5.0#fontawesomeregular") format("svg");
  font-weight: normal;
  font-style: normal;
}

.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}

.fa-2x {
  font-size: 2em;
}

.fa-3x {
  font-size: 3em;
}

.fa-4x {
  font-size: 4em;
}

.fa-5x {
  font-size: 5em;
}

.fa-fw {
  width: 1.28571429em;
  text-align: center;
}

.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}

.fa-ul > li {
  position: relative;
}

.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}

.fa-li.fa-lg {
  left: -1.85714286em;
}

.fa-border {
  padding: 0.2em 0.25em 0.15em;
  border: solid 0.08em #eeeeee;
  border-radius: .1em;
}

.fa-pull-left {
  float: left;
}

.fa-pull-right {
  float: right;
}

.fa.fa-pull-left {
  margin-right: .3em;
}

.fa.fa-pull-right {
  margin-left: .3em;
}

/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}

.pull-left {
  float: left;
}

.fa.pull-left {
  margin-right: .3em;
}

.fa.pull-right {
  margin-left: .3em;
}

.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}

.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}

@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}

@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}

.fa-rotate-90 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}

.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}

.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}

.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}

.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}

:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}

.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}

.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}

.fa-stack-1x {
  line-height: inherit;
}

.fa-stack-2x {
  font-size: 2em;
}

.fa-inverse {
  color: #ffffff;
}

/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}

.fa-music:before {
  content: "\f001";
}

.fa-search:before {
  content: "\f002";
}

.fa-envelope-o:before {
  content: "\f003";
}

.fa-heart:before {
  content: "\f004";
}

.fa-star:before {
  content: "\f005";
}

.fa-star-o:before {
  content: "\f006";
}

.fa-user:before {
  content: "\f007";
}

.fa-film:before {
  content: "\f008";
}

.fa-th-large:before {
  content: "\f009";
}

.fa-th:before {
  content: "\f00a";
}

.fa-th-list:before {
  content: "\f00b";
}

.fa-check:before {
  content: "\f00c";
}

.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}

.fa-search-plus:before {
  content: "\f00e";
}

.fa-search-minus:before {
  content: "\f010";
}

.fa-power-off:before {
  content: "\f011";
}

.fa-signal:before {
  content: "\f012";
}

.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}

.fa-trash-o:before {
  content: "\f014";
}

.fa-home:before {
  content: "\f015";
}

.fa-file-o:before {
  content: "\f016";
}

.fa-clock-o:before {
  content: "\f017";
}

.fa-road:before {
  content: "\f018";
}

.fa-download:before {
  content: "\f019";
}

.fa-arrow-circle-o-down:before {
  content: "\f01a";
}

.fa-arrow-circle-o-up:before {
  content: "\f01b";
}

.fa-inbox:before {
  content: "\f01c";
}

.fa-play-circle-o:before {
  content: "\f01d";
}

.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}

.fa-refresh:before {
  content: "\f021";
}

.fa-list-alt:before {
  content: "\f022";
}

.fa-lock:before {
  content: "\f023";
}

.fa-flag:before {
  content: "\f024";
}

.fa-headphones:before {
  content: "\f025";
}

.fa-volume-off:before {
  content: "\f026";
}

.fa-volume-down:before {
  content: "\f027";
}

.fa-volume-up:before {
  content: "\f028";
}

.fa-qrcode:before {
  content: "\f029";
}

.fa-barcode:before {
  content: "\f02a";
}

.fa-tag:before {
  content: "\f02b";
}

.fa-tags:before {
  content: "\f02c";
}

.fa-book:before {
  content: "\f02d";
}

.fa-bookmark:before {
  content: "\f02e";
}

.fa-print:before {
  content: "\f02f";
}

.fa-camera:before {
  content: "\f030";
}

.fa-font:before {
  content: "\f031";
}

.fa-bold:before {
  content: "\f032";
}

.fa-italic:before {
  content: "\f033";
}

.fa-text-height:before {
  content: "\f034";
}

.fa-text-width:before {
  content: "\f035";
}

.fa-align-left:before {
  content: "\f036";
}

.fa-align-center:before {
  content: "\f037";
}

.fa-align-right:before {
  content: "\f038";
}

.fa-align-justify:before {
  content: "\f039";
}

.fa-list:before {
  content: "\f03a";
}

.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}

.fa-indent:before {
  content: "\f03c";
}

.fa-video-camera:before {
  content: "\f03d";
}

.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}

.fa-pencil:before {
  content: "\f040";
}

.fa-map-marker:before {
  content: "\f041";
}

.fa-adjust:before {
  content: "\f042";
}

.fa-tint:before {
  content: "\f043";
}

.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}

.fa-share-square-o:before {
  content: "\f045";
}

.fa-check-square-o:before {
  content: "\f046";
}

.fa-arrows:before {
  content: "\f047";
}

.fa-step-backward:before {
  content: "\f048";
}

.fa-fast-backward:before {
  content: "\f049";
}

.fa-backward:before {
  content: "\f04a";
}

.fa-play:before {
  content: "\f04b";
}

.fa-pause:before {
  content: "\f04c";
}

.fa-stop:before {
  content: "\f04d";
}

.fa-forward:before {
  content: "\f04e";
}

.fa-fast-forward:before {
  content: "\f050";
}

.fa-step-forward:before {
  content: "\f051";
}

.fa-eject:before {
  content: "\f052";
}

.fa-chevron-left:before {
  content: "\f053";
}

.fa-chevron-right:before {
  content: "\f054";
}

.fa-plus-circle:before {
  content: "\f055";
}

.fa-minus-circle:before {
  content: "\f056";
}

.fa-times-circle:before {
  content: "\f057";
}

.fa-check-circle:before {
  content: "\f058";
}

.fa-question-circle:before {
  content: "\f059";
}

.fa-info-circle:before {
  content: "\f05a";
}

.fa-crosshairs:before {
  content: "\f05b";
}

.fa-times-circle-o:before {
  content: "\f05c";
}

.fa-check-circle-o:before {
  content: "\f05d";
}

.fa-ban:before {
  content: "\f05e";
}

.fa-arrow-left:before {
  content: "\f060";
}

.fa-arrow-right:before {
  content: "\f061";
}

.fa-arrow-up:before {
  content: "\f062";
}

.fa-arrow-down:before {
  content: "\f063";
}

.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}

.fa-expand:before {
  content: "\f065";
}

.fa-compress:before {
  content: "\f066";
}

.fa-plus:before {
  content: "\f067";
}

.fa-minus:before {
  content: "\f068";
}

.fa-asterisk:before {
  content: "\f069";
}

.fa-exclamation-circle:before {
  content: "\f06a";
}

.fa-gift:before {
  content: "\f06b";
}

.fa-leaf:before {
  content: "\f06c";
}

.fa-fire:before {
  content: "\f06d";
}

.fa-eye:before {
  content: "\f06e";
}

.fa-eye-slash:before {
  content: "\f070";
}

.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}

.fa-plane:before {
  content: "\f072";
}

.fa-calendar:before {
  content: "\f073";
}

.fa-random:before {
  content: "\f074";
}

.fa-comment:before {
  content: "\f075";
}

.fa-magnet:before {
  content: "\f076";
}

.fa-chevron-up:before {
  content: "\f077";
}

.fa-chevron-down:before {
  content: "\f078";
}

.fa-retweet:before {
  content: "\f079";
}

.fa-shopping-cart:before {
  content: "\f07a";
}

.fa-folder:before {
  content: "\f07b";
}

.fa-folder-open:before {
  content: "\f07c";
}

.fa-arrows-v:before {
  content: "\f07d";
}

.fa-arrows-h:before {
  content: "\f07e";
}

.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}

.fa-twitter-square:before {
  content: "\f081";
}

.fa-facebook-square:before {
  content: "\f082";
}

.fa-camera-retro:before {
  content: "\f083";
}

.fa-key:before {
  content: "\f084";
}

.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}

.fa-comments:before {
  content: "\f086";
}

.fa-thumbs-o-up:before {
  content: "\f087";
}

.fa-thumbs-o-down:before {
  content: "\f088";
}

.fa-star-half:before {
  content: "\f089";
}

.fa-heart-o:before {
  content: "\f08a";
}

.fa-sign-out:before {
  content: "\f08b";
}

.fa-linkedin-square:before {
  content: "\f08c";
}

.fa-thumb-tack:before {
  content: "\f08d";
}

.fa-external-link:before {
  content: "\f08e";
}

.fa-sign-in:before {
  content: "\f090";
}

.fa-trophy:before {
  content: "\f091";
}

.fa-github-square:before {
  content: "\f092";
}

.fa-upload:before {
  content: "\f093";
}

.fa-lemon-o:before {
  content: "\f094";
}

.fa-phone:before {
  content: "\f095";
}

.fa-square-o:before {
  content: "\f096";
}

.fa-bookmark-o:before {
  content: "\f097";
}

.fa-phone-square:before {
  content: "\f098";
}

.fa-twitter:before {
  content: "\f099";
}

.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}

.fa-github:before {
  content: "\f09b";
}

.fa-unlock:before {
  content: "\f09c";
}

.fa-credit-card:before {
  content: "\f09d";
}

.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}

.fa-hdd-o:before {
  content: "\f0a0";
}

.fa-bullhorn:before {
  content: "\f0a1";
}

.fa-bell:before {
  content: "\f0f3";
}

.fa-certificate:before {
  content: "\f0a3";
}

.fa-hand-o-right:before {
  content: "\f0a4";
}

.fa-hand-o-left:before {
  content: "\f0a5";
}

.fa-hand-o-up:before {
  content: "\f0a6";
}

.fa-hand-o-down:before {
  content: "\f0a7";
}

.fa-arrow-circle-left:before {
  content: "\f0a8";
}

.fa-arrow-circle-right:before {
  content: "\f0a9";
}

.fa-arrow-circle-up:before {
  content: "\f0aa";
}

.fa-arrow-circle-down:before {
  content: "\f0ab";
}

.fa-globe:before {
  content: "\f0ac";
}

.fa-wrench:before {
  content: "\f0ad";
}

.fa-tasks:before {
  content: "\f0ae";
}

.fa-filter:before {
  content: "\f0b0";
}

.fa-briefcase:before {
  content: "\f0b1";
}

.fa-arrows-alt:before {
  content: "\f0b2";
}

.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}

.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}

.fa-cloud:before {
  content: "\f0c2";
}

.fa-flask:before {
  content: "\f0c3";
}

.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}

.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}

.fa-paperclip:before {
  content: "\f0c6";
}

.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}

.fa-square:before {
  content: "\f0c8";
}

.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}

.fa-list-ul:before {
  content: "\f0ca";
}

.fa-list-ol:before {
  content: "\f0cb";
}

.fa-strikethrough:before {
  content: "\f0cc";
}

.fa-underline:before {
  content: "\f0cd";
}

.fa-table:before {
  content: "\f0ce";
}

.fa-magic:before {
  content: "\f0d0";
}

.fa-truck:before {
  content: "\f0d1";
}

.fa-pinterest:before {
  content: "\f0d2";
}

.fa-pinterest-square:before {
  content: "\f0d3";
}

.fa-google-plus-square:before {
  content: "\f0d4";
}

.fa-google-plus:before {
  content: "\f0d5";
}

.fa-money:before {
  content: "\f0d6";
}

.fa-caret-down:before {
  content: "\f0d7";
}

.fa-caret-up:before {
  content: "\f0d8";
}

.fa-caret-left:before {
  content: "\f0d9";
}

.fa-caret-right:before {
  content: "\f0da";
}

.fa-columns:before {
  content: "\f0db";
}

.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}

.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}

.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}

.fa-envelope:before {
  content: "\f0e0";
}

.fa-linkedin:before {
  content: "\f0e1";
}

.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}

.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}

.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}

.fa-comment-o:before {
  content: "\f0e5";
}

.fa-comments-o:before {
  content: "\f0e6";
}

.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}

.fa-sitemap:before {
  content: "\f0e8";
}

.fa-umbrella:before {
  content: "\f0e9";
}

.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}

.fa-lightbulb-o:before {
  content: "\f0eb";
}

.fa-exchange:before {
  content: "\f0ec";
}

.fa-cloud-download:before {
  content: "\f0ed";
}

.fa-cloud-upload:before {
  content: "\f0ee";
}

.fa-user-md:before {
  content: "\f0f0";
}

.fa-stethoscope:before {
  content: "\f0f1";
}

.fa-suitcase:before {
  content: "\f0f2";
}

.fa-bell-o:before {
  content: "\f0a2";
}

.fa-coffee:before {
  content: "\f0f4";
}

.fa-cutlery:before {
  content: "\f0f5";
}

.fa-file-text-o:before {
  content: "\f0f6";
}

.fa-building-o:before {
  content: "\f0f7";
}

.fa-hospital-o:before {
  content: "\f0f8";
}

.fa-ambulance:before {
  content: "\f0f9";
}

.fa-medkit:before {
  content: "\f0fa";
}

.fa-fighter-jet:before {
  content: "\f0fb";
}

.fa-beer:before {
  content: "\f0fc";
}

.fa-h-square:before {
  content: "\f0fd";
}

.fa-plus-square:before {
  content: "\f0fe";
}

.fa-angle-double-left:before {
  content: "\f100";
}

.fa-angle-double-right:before {
  content: "\f101";
}

.fa-angle-double-up:before {
  content: "\f102";
}

.fa-angle-double-down:before {
  content: "\f103";
}

.fa-angle-left:before {
  content: "\f104";
}

.fa-angle-right:before {
  content: "\f105";
}

.fa-angle-up:before {
  content: "\f106";
}

.fa-angle-down:before {
  content: "\f107";
}

.fa-desktop:before {
  content: "\f108";
}

.fa-laptop:before {
  content: "\f109";
}

.fa-tablet:before {
  content: "\f10a";
}

.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}

.fa-circle-o:before {
  content: "\f10c";
}

.fa-quote-left:before {
  content: "\f10d";
}

.fa-quote-right:before {
  content: "\f10e";
}

.fa-spinner:before {
  content: "\f110";
}

.fa-circle:before {
  content: "\f111";
}

.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}

.fa-github-alt:before {
  content: "\f113";
}

.fa-folder-o:before {
  content: "\f114";
}

.fa-folder-open-o:before {
  content: "\f115";
}

.fa-smile-o:before {
  content: "\f118";
}

.fa-frown-o:before {
  content: "\f119";
}

.fa-meh-o:before {
  content: "\f11a";
}

.fa-gamepad:before {
  content: "\f11b";
}

.fa-keyboard-o:before {
  content: "\f11c";
}

.fa-flag-o:before {
  content: "\f11d";
}

.fa-flag-checkered:before {
  content: "\f11e";
}

.fa-terminal:before {
  content: "\f120";
}

.fa-code:before {
  content: "\f121";
}

.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}

.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}

.fa-location-arrow:before {
  content: "\f124";
}

.fa-crop:before {
  content: "\f125";
}

.fa-code-fork:before {
  content: "\f126";
}

.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}

.fa-question:before {
  content: "\f128";
}

.fa-info:before {
  content: "\f129";
}

.fa-exclamation:before {
  content: "\f12a";
}

.fa-superscript:before {
  content: "\f12b";
}

.fa-subscript:before {
  content: "\f12c";
}

.fa-eraser:before {
  content: "\f12d";
}

.fa-puzzle-piece:before {
  content: "\f12e";
}

.fa-microphone:before {
  content: "\f130";
}

.fa-microphone-slash:before {
  content: "\f131";
}

.fa-shield:before {
  content: "\f132";
}

.fa-calendar-o:before {
  content: "\f133";
}

.fa-fire-extinguisher:before {
  content: "\f134";
}

.fa-rocket:before {
  content: "\f135";
}

.fa-maxcdn:before {
  content: "\f136";
}

.fa-chevron-circle-left:before {
  content: "\f137";
}

.fa-chevron-circle-right:before {
  content: "\f138";
}

.fa-chevron-circle-up:before {
  content: "\f139";
}

.fa-chevron-circle-down:before {
  content: "\f13a";
}

.fa-html5:before {
  content: "\f13b";
}

.fa-css3:before {
  content: "\f13c";
}

.fa-anchor:before {
  content: "\f13d";
}

.fa-unlock-alt:before {
  content: "\f13e";
}

.fa-bullseye:before {
  content: "\f140";
}

.fa-ellipsis-h:before {
  content: "\f141";
}

.fa-ellipsis-v:before {
  content: "\f142";
}

.fa-rss-square:before {
  content: "\f143";
}

.fa-play-circle:before {
  content: "\f144";
}

.fa-ticket:before {
  content: "\f145";
}

.fa-minus-square:before {
  content: "\f146";
}

.fa-minus-square-o:before {
  content: "\f147";
}

.fa-level-up:before {
  content: "\f148";
}

.fa-level-down:before {
  content: "\f149";
}

.fa-check-square:before {
  content: "\f14a";
}

.fa-pencil-square:before {
  content: "\f14b";
}

.fa-external-link-square:before {
  content: "\f14c";
}

.fa-share-square:before {
  content: "\f14d";
}

.fa-compass:before {
  content: "\f14e";
}

.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}

.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}

.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}

.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}

.fa-gbp:before {
  content: "\f154";
}

.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}

.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}

.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}

.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}

.fa-won:before,
.fa-krw:before {
  content: "\f159";
}

.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}

.fa-file:before {
  content: "\f15b";
}

.fa-file-text:before {
  content: "\f15c";
}

.fa-sort-alpha-asc:before {
  content: "\f15d";
}

.fa-sort-alpha-desc:before {
  content: "\f15e";
}

.fa-sort-amount-asc:before {
  content: "\f160";
}

.fa-sort-amount-desc:before {
  content: "\f161";
}

.fa-sort-numeric-asc:before {
  content: "\f162";
}

.fa-sort-numeric-desc:before {
  content: "\f163";
}

.fa-thumbs-up:before {
  content: "\f164";
}

.fa-thumbs-down:before {
  content: "\f165";
}

.fa-youtube-square:before {
  content: "\f166";
}

.fa-youtube:before {
  content: "\f167";
}

.fa-xing:before {
  content: "\f168";
}

.fa-xing-square:before {
  content: "\f169";
}

.fa-youtube-play:before {
  content: "\f16a";
}

.fa-dropbox:before {
  content: "\f16b";
}

.fa-stack-overflow:before {
  content: "\f16c";
}

.fa-instagram:before {
  content: "\f16d";
}

.fa-flickr:before {
  content: "\f16e";
}

.fa-adn:before {
  content: "\f170";
}

.fa-bitbucket:before {
  content: "\f171";
}

.fa-bitbucket-square:before {
  content: "\f172";
}

.fa-tumblr:before {
  content: "\f173";
}

.fa-tumblr-square:before {
  content: "\f174";
}

.fa-long-arrow-down:before {
  content: "\f175";
}

.fa-long-arrow-up:before {
  content: "\f176";
}

.fa-long-arrow-left:before {
  content: "\f177";
}

.fa-long-arrow-right:before {
  content: "\f178";
}

.fa-apple:before {
  content: "\f179";
}

.fa-windows:before {
  content: "\f17a";
}

.fa-android:before {
  content: "\f17b";
}

.fa-linux:before {
  content: "\f17c";
}

.fa-dribbble:before {
  content: "\f17d";
}

.fa-skype:before {
  content: "\f17e";
}

.fa-foursquare:before {
  content: "\f180";
}

.fa-trello:before {
  content: "\f181";
}

.fa-female:before {
  content: "\f182";
}

.fa-male:before {
  content: "\f183";
}

.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}

.fa-sun-o:before {
  content: "\f185";
}

.fa-moon-o:before {
  content: "\f186";
}

.fa-archive:before {
  content: "\f187";
}

.fa-bug:before {
  content: "\f188";
}

.fa-vk:before {
  content: "\f189";
}

.fa-weibo:before {
  content: "\f18a";
}

.fa-renren:before {
  content: "\f18b";
}

.fa-pagelines:before {
  content: "\f18c";
}

.fa-stack-exchange:before {
  content: "\f18d";
}

.fa-arrow-circle-o-right:before {
  content: "\f18e";
}

.fa-arrow-circle-o-left:before {
  content: "\f190";
}

.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}

.fa-dot-circle-o:before {
  content: "\f192";
}

.fa-wheelchair:before {
  content: "\f193";
}

.fa-vimeo-square:before {
  content: "\f194";
}

.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}

.fa-plus-square-o:before {
  content: "\f196";
}

.fa-space-shuttle:before {
  content: "\f197";
}

.fa-slack:before {
  content: "\f198";
}

.fa-envelope-square:before {
  content: "\f199";
}

.fa-wordpress:before {
  content: "\f19a";
}

.fa-openid:before {
  content: "\f19b";
}

.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}

.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}

.fa-yahoo:before {
  content: "\f19e";
}

.fa-google:before {
  content: "\f1a0";
}

.fa-reddit:before {
  content: "\f1a1";
}

.fa-reddit-square:before {
  content: "\f1a2";
}

.fa-stumbleupon-circle:before {
  content: "\f1a3";
}

.fa-stumbleupon:before {
  content: "\f1a4";
}

.fa-delicious:before {
  content: "\f1a5";
}

.fa-digg:before {
  content: "\f1a6";
}

.fa-pied-piper:before {
  content: "\f1a7";
}

.fa-pied-piper-alt:before {
  content: "\f1a8";
}

.fa-drupal:before {
  content: "\f1a9";
}

.fa-joomla:before {
  content: "\f1aa";
}

.fa-language:before {
  content: "\f1ab";
}

.fa-fax:before {
  content: "\f1ac";
}

.fa-building:before {
  content: "\f1ad";
}

.fa-child:before {
  content: "\f1ae";
}

.fa-paw:before {
  content: "\f1b0";
}

.fa-spoon:before {
  content: "\f1b1";
}

.fa-cube:before {
  content: "\f1b2";
}

.fa-cubes:before {
  content: "\f1b3";
}

.fa-behance:before {
  content: "\f1b4";
}

.fa-behance-square:before {
  content: "\f1b5";
}

.fa-steam:before {
  content: "\f1b6";
}

.fa-steam-square:before {
  content: "\f1b7";
}

.fa-recycle:before {
  content: "\f1b8";
}

.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}

.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}

.fa-tree:before {
  content: "\f1bb";
}

.fa-spotify:before {
  content: "\f1bc";
}

.fa-deviantart:before {
  content: "\f1bd";
}

.fa-soundcloud:before {
  content: "\f1be";
}

.fa-database:before {
  content: "\f1c0";
}

.fa-file-pdf-o:before {
  content: "\f1c1";
}

.fa-file-word-o:before {
  content: "\f1c2";
}

.fa-file-excel-o:before {
  content: "\f1c3";
}

.fa-file-powerpoint-o:before {
  content: "\f1c4";
}

.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}

.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}

.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}

.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}

.fa-file-code-o:before {
  content: "\f1c9";
}

.fa-vine:before {
  content: "\f1ca";
}

.fa-codepen:before {
  content: "\f1cb";
}

.fa-jsfiddle:before {
  content: "\f1cc";
}

.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}

.fa-circle-o-notch:before {
  content: "\f1ce";
}

.fa-ra:before,
.fa-rebel:before {
  content: "\f1d0";
}

.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}

.fa-git-square:before {
  content: "\f1d2";
}

.fa-git:before {
  content: "\f1d3";
}

.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}

.fa-tencent-weibo:before {
  content: "\f1d5";
}

.fa-qq:before {
  content: "\f1d6";
}

.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}

.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}

.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}

.fa-history:before {
  content: "\f1da";
}

.fa-circle-thin:before {
  content: "\f1db";
}

.fa-header:before {
  content: "\f1dc";
}

.fa-paragraph:before {
  content: "\f1dd";
}

.fa-sliders:before {
  content: "\f1de";
}

.fa-share-alt:before {
  content: "\f1e0";
}

.fa-share-alt-square:before {
  content: "\f1e1";
}

.fa-bomb:before {
  content: "\f1e2";
}

.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}

.fa-tty:before {
  content: "\f1e4";
}

.fa-binoculars:before {
  content: "\f1e5";
}

.fa-plug:before {
  content: "\f1e6";
}

.fa-slideshare:before {
  content: "\f1e7";
}

.fa-twitch:before {
  content: "\f1e8";
}

.fa-yelp:before {
  content: "\f1e9";
}

.fa-newspaper-o:before {
  content: "\f1ea";
}

.fa-wifi:before {
  content: "\f1eb";
}

.fa-calculator:before {
  content: "\f1ec";
}

.fa-paypal:before {
  content: "\f1ed";
}

.fa-google-wallet:before {
  content: "\f1ee";
}

.fa-cc-visa:before {
  content: "\f1f0";
}

.fa-cc-mastercard:before {
  content: "\f1f1";
}

.fa-cc-discover:before {
  content: "\f1f2";
}

.fa-cc-amex:before {
  content: "\f1f3";
}

.fa-cc-paypal:before {
  content: "\f1f4";
}

.fa-cc-stripe:before {
  content: "\f1f5";
}

.fa-bell-slash:before {
  content: "\f1f6";
}

.fa-bell-slash-o:before {
  content: "\f1f7";
}

.fa-trash:before {
  content: "\f1f8";
}

.fa-copyright:before {
  content: "\f1f9";
}

.fa-at:before {
  content: "\f1fa";
}

.fa-eyedropper:before {
  content: "\f1fb";
}

.fa-paint-brush:before {
  content: "\f1fc";
}

.fa-birthday-cake:before {
  content: "\f1fd";
}

.fa-area-chart:before {
  content: "\f1fe";
}

.fa-pie-chart:before {
  content: "\f200";
}

.fa-line-chart:before {
  content: "\f201";
}

.fa-lastfm:before {
  content: "\f202";
}

.fa-lastfm-square:before {
  content: "\f203";
}

.fa-toggle-off:before {
  content: "\f204";
}

.fa-toggle-on:before {
  content: "\f205";
}

.fa-bicycle:before {
  content: "\f206";
}

.fa-bus:before {
  content: "\f207";
}

.fa-ioxhost:before {
  content: "\f208";
}

.fa-angellist:before {
  content: "\f209";
}

.fa-cc:before {
  content: "\f20a";
}

.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}

.fa-meanpath:before {
  content: "\f20c";
}

.fa-buysellads:before {
  content: "\f20d";
}

.fa-connectdevelop:before {
  content: "\f20e";
}

.fa-dashcube:before {
  content: "\f210";
}

.fa-forumbee:before {
  content: "\f211";
}

.fa-leanpub:before {
  content: "\f212";
}

.fa-sellsy:before {
  content: "\f213";
}

.fa-shirtsinbulk:before {
  content: "\f214";
}

.fa-simplybuilt:before {
  content: "\f215";
}

.fa-skyatlas:before {
  content: "\f216";
}

.fa-cart-plus:before {
  content: "\f217";
}

.fa-cart-arrow-down:before {
  content: "\f218";
}

.fa-diamond:before {
  content: "\f219";
}

.fa-ship:before {
  content: "\f21a";
}

.fa-user-secret:before {
  content: "\f21b";
}

.fa-motorcycle:before {
  content: "\f21c";
}

.fa-street-view:before {
  content: "\f21d";
}

.fa-heartbeat:before {
  content: "\f21e";
}

.fa-venus:before {
  content: "\f221";
}

.fa-mars:before {
  content: "\f222";
}

.fa-mercury:before {
  content: "\f223";
}

.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}

.fa-transgender-alt:before {
  content: "\f225";
}

.fa-venus-double:before {
  content: "\f226";
}

.fa-mars-double:before {
  content: "\f227";
}

.fa-venus-mars:before {
  content: "\f228";
}

.fa-mars-stroke:before {
  content: "\f229";
}

.fa-mars-stroke-v:before {
  content: "\f22a";
}

.fa-mars-stroke-h:before {
  content: "\f22b";
}

.fa-neuter:before {
  content: "\f22c";
}

.fa-genderless:before {
  content: "\f22d";
}

.fa-facebook-official:before {
  content: "\f230";
}

.fa-pinterest-p:before {
  content: "\f231";
}

.fa-whatsapp:before {
  content: "\f232";
}

.fa-server:before {
  content: "\f233";
}

.fa-user-plus:before {
  content: "\f234";
}

.fa-user-times:before {
  content: "\f235";
}

.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}

.fa-viacoin:before {
  content: "\f237";
}

.fa-train:before {
  content: "\f238";
}

.fa-subway:before {
  content: "\f239";
}

.fa-medium:before {
  content: "\f23a";
}

.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}

.fa-optin-monster:before {
  content: "\f23c";
}

.fa-opencart:before {
  content: "\f23d";
}

.fa-expeditedssl:before {
  content: "\f23e";
}

.fa-battery-4:before,
.fa-battery-full:before {
  content: "\f240";
}

.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}

.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}

.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}

.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}

.fa-mouse-pointer:before {
  content: "\f245";
}

.fa-i-cursor:before {
  content: "\f246";
}

.fa-object-group:before {
  content: "\f247";
}

.fa-object-ungroup:before {
  content: "\f248";
}

.fa-sticky-note:before {
  content: "\f249";
}

.fa-sticky-note-o:before {
  content: "\f24a";
}

.fa-cc-jcb:before {
  content: "\f24b";
}

.fa-cc-diners-club:before {
  content: "\f24c";
}

.fa-clone:before {
  content: "\f24d";
}

.fa-balance-scale:before {
  content: "\f24e";
}

.fa-hourglass-o:before {
  content: "\f250";
}

.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}

.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}

.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}

.fa-hourglass:before {
  content: "\f254";
}

.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}

.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}

.fa-hand-scissors-o:before {
  content: "\f257";
}

.fa-hand-lizard-o:before {
  content: "\f258";
}

.fa-hand-spock-o:before {
  content: "\f259";
}

.fa-hand-pointer-o:before {
  content: "\f25a";
}

.fa-hand-peace-o:before {
  content: "\f25b";
}

.fa-trademark:before {
  content: "\f25c";
}

.fa-registered:before {
  content: "\f25d";
}

.fa-creative-commons:before {
  content: "\f25e";
}

.fa-gg:before {
  content: "\f260";
}

.fa-gg-circle:before {
  content: "\f261";
}

.fa-tripadvisor:before {
  content: "\f262";
}

.fa-odnoklassniki:before {
  content: "\f263";
}

.fa-odnoklassniki-square:before {
  content: "\f264";
}

.fa-get-pocket:before {
  content: "\f265";
}

.fa-wikipedia-w:before {
  content: "\f266";
}

.fa-safari:before {
  content: "\f267";
}

.fa-chrome:before {
  content: "\f268";
}

.fa-firefox:before {
  content: "\f269";
}

.fa-opera:before {
  content: "\f26a";
}

.fa-internet-explorer:before {
  content: "\f26b";
}

.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}

.fa-contao:before {
  content: "\f26d";
}

.fa-500px:before {
  content: "\f26e";
}

.fa-amazon:before {
  content: "\f270";
}

.fa-calendar-plus-o:before {
  content: "\f271";
}

.fa-calendar-minus-o:before {
  content: "\f272";
}

.fa-calendar-times-o:before {
  content: "\f273";
}

.fa-calendar-check-o:before {
  content: "\f274";
}

.fa-industry:before {
  content: "\f275";
}

.fa-map-pin:before {
  content: "\f276";
}

.fa-map-signs:before {
  content: "\f277";
}

.fa-map-o:before {
  content: "\f278";
}

.fa-map:before {
  content: "\f279";
}

.fa-commenting:before {
  content: "\f27a";
}

.fa-commenting-o:before {
  content: "\f27b";
}

.fa-houzz:before {
  content: "\f27c";
}

.fa-vimeo:before {
  content: "\f27d";
}

.fa-black-tie:before {
  content: "\f27e";
}

.fa-fonticons:before {
  content: "\f280";
}

.fa-reddit-alien:before {
  content: "\f281";
}

.fa-edge:before {
  content: "\f282";
}

.fa-credit-card-alt:before {
  content: "\f283";
}

.fa-codiepie:before {
  content: "\f284";
}

.fa-modx:before {
  content: "\f285";
}

.fa-fort-awesome:before {
  content: "\f286";
}

.fa-usb:before {
  content: "\f287";
}

.fa-product-hunt:before {
  content: "\f288";
}

.fa-mixcloud:before {
  content: "\f289";
}

.fa-scribd:before {
  content: "\f28a";
}

.fa-pause-circle:before {
  content: "\f28b";
}

.fa-pause-circle-o:before {
  content: "\f28c";
}

.fa-stop-circle:before {
  content: "\f28d";
}

.fa-stop-circle-o:before {
  content: "\f28e";
}

.fa-shopping-bag:before {
  content: "\f290";
}

.fa-shopping-basket:before {
  content: "\f291";
}

.fa-hashtag:before {
  content: "\f292";
}

.fa-bluetooth:before {
  content: "\f293";
}

.fa-bluetooth-b:before {
  content: "\f294";
}

.fa-percent:before {
  content: "\f295";
}

[class*='fa-']:before {
  font-weight: 400;
  font-family: 'FontAwesome';
}

.thumbnail {
  position: relative;
  margin-bottom: 0;
  border: none;
  padding: 0;
}

.thumbnail > img,
.thumbnail a > img {
  width: 100%;
  height: auto;
}

.thumbnail .caption {
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translateX(-50%) translateY(-50%);
  transform: translateX(-50%) translateY(-50%);
}

@media (min-width: 992px) {
  .thumbnail .caption {
    top: 54px;
    left: 51px;
    -webkit-transform: translateX(0) translateY(0);
    transform: translateX(0) translateY(0);
  }
}

.page {
  overflow: hidden;
}

.page-foot {
  background-color: #000;
  position: relative;
}

.page-foot * {
  color: #cdcdcd;
}

.page-foot a {
  font-weight: 400;
  color: #ffb822;
}

.page-foot a:hover {
  color: #cdcdcd;
}

@media (min-width: 992px) {
  .page-foot section:first-of-type {
    position: absolute;
    bottom: 100%;
    left: 0;
    width: 100%;
    z-index: 4;
  }
}

.page-foot .inset-2 {
  padding: 57px 0 57px;
}

.page-foot address.contact-info {
  margin-bottom: 0;
}

.page-foot .copyright {
  font-size: 20px;
  text-transform: uppercase;
  font-family: "Cinzel", serif;
  font-weight: 700;
}

.page-foot .copyright p + p {
  margin-top: 6px;
}

.section-viewport {
  height: 100vh;
}

.section-xs {
  padding-bottom: 34px;
  padding-top: 56px;
}

@media (min-width: 1200px) {
  .section-xs {
    padding-top: 0;
  }
}

.section-sm {
  padding-top: 50px;
  padding-bottom: 50px;
}

@media (min-width: 992px) {
  .section-sm {
    padding-top: 210px;
    padding-bottom: 210px;
  }
}

.section-md {
  padding-top: 50px;
  padding-bottom: 50px;
}

@media (min-width: 992px) {
  .section-md {
    padding-top: 184px;
    padding-bottom: 150px;
  }
  .section-md-inset-1 {
    padding-bottom: 99px;
  }
}

.section-lg {
  padding-top: 50px;
  padding-bottom: 50px;
}

@media (min-width: 992px) {
  .section-lg {
    padding-top: 149px;
    padding-bottom: 354px;
  }
}

.container .jumbotron {
  padding: 78px 0 40px;
  background-color: transparent;
  font-family: "Cinzel", serif;
  text-transform: uppercase;
  border-radius: 13px;
  letter-spacing: 1.6px;
  margin-bottom: 0;
  color: #fff;
}

@media (min-width: 768px) {
  .container .jumbotron {
    padding: 150px 0 90px;
  }
}

@media (min-width: 1200px) {
  .container .jumbotron {
    padding: 306px 0 187px;
  }
}

.container .jumbotron p.big {
  font-size: 80px;
  line-height: 48px;
  font-weight: 700;
  color: #fff;
}

@media (min-width: 768px) {
  .container .jumbotron p.big {
    font-size: 120px;
  }
}

.container .jumbotron p {
  font-size: 34px;
  line-height: 40px;
}

.container .jumbotron p.big + p {
  margin-top: 52px;
}

.container .jumbotron p + .btn {
  margin-top: 6px;
}

/*Backgrounds*/
.bg-image {
  background-size: auto 100%;
}

@media (min-width: 1200px) {
  .bg-image {
    background-size: cover;
    background-attachment: fixed;
  }
}

.bg-image-2 {
  background-color: transparent;
}

@media (min-width: 992px) {
  .bg-image-2 {
    background-size: cover;
    background-image: url("../images/index-2.jpg");
  }
}

/*Border Radius*/
.border-radius-xs {
  border-radius: 4px;
  overflow: hidden;
}

.border-radius-sm {
  border-radius: 13px;
}

/*Shadows and Gradients*/
@media (min-width: 992px) {
  .container-shadow {
    -webkit-box-shadow: 0px 0px 30px 32px rgba(0, 0, 0, 0.6);
    -moz-box-shadow: 0px 0px 30px 32px rgba(0, 0, 0, 0.6);
    box-shadow: 0px 0px 30px 32px rgba(0, 0, 0, 0.6);
  }
}

.box-shadow {
  -webkit-box-shadow: 0px 0px 20px 10px rgba(0, 0, 0, 0.6);
  -moz-box-shadow: 0px 0px 20px 10px rgba(0, 0, 0, 0.6);
  box-shadow: 0px 0px 20px 10px rgba(0, 0, 0, 0.6);
}

.section-gradient {
  position: relative;
}

.section-gradient:before {
  content: '';
  position: absolute;
  display: inline-block;
  height: 40%;
  width: 100%;
  bottom: 0;
  left: 0;
  background-image: linear-gradient(to top, rgba(0, 0, 0, 0.5), transparent);
  z-index: 1;
}

.section-transparent {
  background-color: rgba(0, 0, 0, 0.48);
}

/*Helpers*/
.p0 {
  padding: 0;
}

.opacity-half {
  opacity: .5;
}

.z-index-2 {
  position: relative;
  z-index: 2;
}

/*Insets*/
@media (min-width: 992px) {
  .inset-3 {
    padding-right: 100px;
  }
}

.list-inline {
  margin: 0;
  padding: 0;
}

.list-inline li {
  display: inline-block;
}

.list-inline li + li {
  margin-left: 10px;
}

p {
  margin: 0;
}

.container + .container {
  margin-top: 10%;
}

* + .list-inline {
  margin-top: 34px;
}

p.big + * {
  margin-top: 6px;
}

* + p {
  margin-top: 46px;
}

p + p {
  margin-top: 28px;
}

p.h3 + p {
  margin-top: 45px;
}

h1 + .h3 {
  margin-top: 9px;
}

* + .range {
  margin-top: 58px;
}

h2 + .range {
  margin-top: 82px;
}

.range + h2 {
  margin-top: 89px;
}

.offset-1 {
  margin-top: 33px;
}

* + .offset-2 {
  margin-top: 30px;
}

@media (min-width: 768px) {
  * + .offset-2 {
    margin-top: 82px;
  }
}

@media (min-width: 992px) {
  .flow-offset-1 [class*="cell-"]:nth-child(n+4) {
    margin-top: 22px;
  }
}

@media (min-width: 768px) and (max-width: 1199px) {
  .flow-offset-2 [class*="cell-"]:nth-child(n+3) {
    margin-top: 30px;
  }
}

a {
  transition: .3s;
}

a:focus,
a:active {
  outline: none;
}

h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  text-transform: uppercase;
  margin: 0;
}

h1, .h1 {
  font-size: 38px;
  line-height: 1.33;
  letter-spacing: 3.2px;
}

@media (min-width: 768px) {
  h1, .h1 {
    font-size: 64px;
    line-height: 1;
  }
}

h2, .h2 {
  font-size: 34px;
  line-height: 1.5;
  letter-spacing: 2.1px;
}

@media (min-width: 768px) {
  h2, .h2 {
    font-size: 42px;
    line-height: 1.14286;
  }
}

h3, .h3 {
  font-size: 30px;
  line-height: 1.5;
  font-weight: 400;
  letter-spacing: 1.8px;
}

@media (min-width: 768px) {
  h3, .h3 {
    font-size: 36px;
    line-height: 1.22222;
  }
}

h4, .h4 {
  font-size: 26px;
}

@media (min-width: 768px) {
  h4, .h4 {
    font-size: 30px;
    line-height: 1.6;
  }
}

h5, .h5 {
  font-size: 22px;
}

@media (min-width: 768px) {
  h5, .h5 {
    font-size: 24px;
    line-height: 1.66667;
  }
}

h6, .h6 {
  font-size: 18px;
  letter-spacing: 1.1px;
}

@media (min-width: 768px) {
  h6, .h6 {
    font-size: 22px;
    line-height: 1.09091;
  }
}

p.big {
  font-size: 26px;
  line-height: 48px;
  letter-spacing: 1.3px;
  text-transform: uppercase;
  color: #ffb822;
  font-family: "Cinzel", serif;
}

.pricing-table {
  border: 1px solid #fff;
  padding: 54px 17px;
  max-width: 370px;
  margin: 0 auto;
}

@media (min-width: 992px) {
  .pricing-table {
    padding: 54px 46px;
  }
}

.pricing-table h6 {
  margin-bottom: 39px;
}

.pricing-table .table-content {
  border-top: 1px dashed #e89e00;
  padding-top: 35px;
  border-collapse: separate;
  width: 100%;
}

.pricing-table .table-content td {
  padding-bottom: 6px;
}

.pricing-table .table-content td:nth-child(2) {
  text-align: right;
  color: #ffb822;
}

.product {
  margin: 0 auto;
  display: block;
  max-width: 370px;
  text-align: center;
  transition: .3s;
  position: relative;
}

.product * {
  color: #e89e00;
}

.product * + h4 {
  margin-top: 15px;
}

.product h4 {
  transition: .3s;
}

.product-inner {
  padding: 25px 0 74px;
  position: relative;
  z-index: 2;
}

.product:before {
  content: '';
  display: inline-block;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: #e89e00;
  transition: .3s;
  opacity: 0;
  z-index: 1;
}

.product span {
  color: #fff;
}

.product:hover {
  -webkit-box-shadow: 0px 0px 9px 3px rgba(232, 158, 0, 0.61);
  -moz-box-shadow: 0px 0px 9px 3px rgba(232, 158, 0, 0.61);
  box-shadow: 0px 0px 9px 3px rgba(232, 158, 0, 0.61);
}

.product:hover * {
  color: #fff;
}

.product:hover:before {
  opacity: 1;
}

.panel {
  border: 1px solid #fff;
  background-color: transparent;
  text-align: center;
  padding: 20px 0 30px;
}

.panel h5 {
  text-transform: capitalize;
  font-weight: 500;
  font-family: "Roboto", sans-serif;
}

.panel p.h5 {
  color: #cdcdcd;
  text-transform: inherit;
  font-family: "Roboto", sans-serif;
  font-weight: 400;
}

/**
 * Title:  Bigmug Line Flaticon Pack
 * Author: Catalin Fertu
 * Source: http://www.flaticon.com/packs/bigmug-line
 * License:  CC BY 3.0 (http://creativecommons.org/licenses/by/3.0/)
 */
@font-face {
  font-family: "fl-bigmug-line";
  src: url("../fonts/fl-bigmug-line.eot");
  src: url("../fonts/fl-bigmug-line.eot#iefix") format("embedded-opentype"), url("../fonts/fl-bigmug-line.woff") format("woff"), url("../fonts/fl-bigmug-line.ttf") format("truetype"), url("../fonts/fl-bigmug-line.svg") format("svg");
  font-weight: normal;
  font-style: normal;
}

.fl-bigmug-line-ico,
[class^="fl-bigmug-line-"]:before, [class*=" fl-bigmug-line-"]:before,
[class^="fl-bigmug-line-"]:after, [class*=" fl-bigmug-line-"]:after {
  font-family: 'fl-bigmug-line';
  font-size: inherit;
  font-weight: 400;
  font-style: normal;
}

.fl-bigmug-line-add137:before {
  content: "\e000";
}

.fl-bigmug-line-add139:before {
  content: "\e001";
}

.fl-bigmug-line-add149:before {
  content: "\e002";
}

.fl-bigmug-line-airplane86:before {
  content: "\e003";
}

.fl-bigmug-line-alarm31:before {
  content: "\e004";
}

.fl-bigmug-line-arrow592:before {
  content: "\e005";
}

.fl-bigmug-line-attach8:before {
  content: "\e006";
}

.fl-bigmug-line-attachment15:before {
  content: "\e007";
}

.fl-bigmug-line-audio46:before {
  content: "\e008";
}

.fl-bigmug-line-back44:before {
  content: "\e009";
}

.fl-bigmug-line-back46:before {
  content: "\e00a";
}

.fl-bigmug-line-big104:before {
  content: "\e00b";
}

.fl-bigmug-line-book188:before {
  content: "\e00c";
}

.fl-bigmug-line-bookmark28:before {
  content: "\e00d";
}

.fl-bigmug-line-bottle34:before {
  content: "\e00e";
}

.fl-bigmug-line-button5:before {
  content: "\e00f";
}

.fl-bigmug-line-buttons5:before {
  content: "\e010";
}

.fl-bigmug-line-cellphone55:before {
  content: "\e011";
}

.fl-bigmug-line-cellular9:before {
  content: "\e012";
}

.fl-bigmug-line-center10:before {
  content: "\e013";
}

.fl-bigmug-line-chat51:before {
  content: "\e014";
}

.fl-bigmug-line-chat55:before {
  content: "\e015";
}

.fl-bigmug-line-checkmark14:before {
  content: "\e016";
}

.fl-bigmug-line-checkmark15:before {
  content: "\e017";
}

.fl-bigmug-line-checkmark16:before {
  content: "\e018";
}

.fl-bigmug-line-circular220:before {
  content: "\e019";
}

.fl-bigmug-line-circular224:before {
  content: "\e01a";
}

.fl-bigmug-line-circular228:before {
  content: "\e01b";
}

.fl-bigmug-line-circular229:before {
  content: "\e01c";
}

.fl-bigmug-line-clipboard68:before {
  content: "\e01d";
}

.fl-bigmug-line-close42:before {
  content: "\e01e";
}

.fl-bigmug-line-cloud255:before {
  content: "\e01f";
}

.fl-bigmug-line-cloud260:before {
  content: "\e020";
}

.fl-bigmug-line-cocktail26:before {
  content: "\e021";
}

.fl-bigmug-line-code30:before {
  content: "\e022";
}

.fl-bigmug-line-collapse5:before {
  content: "\e023";
}

.fl-bigmug-line-comment45:before {
  content: "\e024";
}

.fl-bigmug-line-compass80:before {
  content: "\e025";
}

.fl-bigmug-line-contract5:before {
  content: "\e026";
}

.fl-bigmug-line-copy23:before {
  content: "\e027";
}

.fl-bigmug-line-crescent23:before {
  content: "\e028";
}

.fl-bigmug-line-cropping1:before {
  content: "\e029";
}

.fl-bigmug-line-cross81:before {
  content: "\e02a";
}

.fl-bigmug-line-cross83:before {
  content: "\e02b";
}

.fl-bigmug-line-cube29:before {
  content: "\e02c";
}

.fl-bigmug-line-double97:before {
  content: "\e02d";
}

.fl-bigmug-line-double98:before {
  content: "\e02e";
}

.fl-bigmug-line-double99:before {
  content: "\e02f";
}

.fl-bigmug-line-down55:before {
  content: "\e030";
}

.fl-bigmug-line-down56:before {
  content: "\e031";
}

.fl-bigmug-line-down58:before {
  content: "\e032";
}

.fl-bigmug-line-down59:before {
  content: "\e033";
}

.fl-bigmug-line-down64:before {
  content: "\e034";
}

.fl-bigmug-line-download136:before {
  content: "\e035";
}

.fl-bigmug-line-download142:before {
  content: "\e036";
}

.fl-bigmug-line-download146:before {
  content: "\e037";
}

.fl-bigmug-line-download147:before {
  content: "\e038";
}

.fl-bigmug-line-download148:before {
  content: "\e039";
}

.fl-bigmug-line-electrical17:before {
  content: "\e03a";
}

.fl-bigmug-line-electronic57:before {
  content: "\e03b";
}

.fl-bigmug-line-email64:before {
  content: "\e03c";
}

.fl-bigmug-line-email67:before {
  content: "\e03d";
}

.fl-bigmug-line-equalization3:before {
  content: "\e03e";
}

.fl-bigmug-line-equalizer26:before {
  content: "\e03f";
}

.fl-bigmug-line-event6:before {
  content: "\e040";
}

.fl-bigmug-line-expand25:before {
  content: "\e041";
}

.fl-bigmug-line-expanding2:before {
  content: "\e042";
}

.fl-bigmug-line-fast33:before {
  content: "\e043";
}

.fl-bigmug-line-favourites5:before {
  content: "\e044";
}

.fl-bigmug-line-file68:before {
  content: "\e045";
}

.fl-bigmug-line-file69:before {
  content: "\e046";
}

.fl-bigmug-line-film57:before {
  content: "\e047";
}

.fl-bigmug-line-flag53:before {
  content: "\e048";
}

.fl-bigmug-line-fog10:before {
  content: "\e049";
}

.fl-bigmug-line-foggy3:before {
  content: "\e04a";
}

.fl-bigmug-line-folder173:before {
  content: "\e04b";
}

.fl-bigmug-line-fork34:before {
  content: "\e04c";
}

.fl-bigmug-line-four87:before {
  content: "\e04d";
}

.fl-bigmug-line-full40:before {
  content: "\e04e";
}

.fl-bigmug-line-games32:before {
  content: "\e04f";
}

.fl-bigmug-line-gear30:before {
  content: "\e050";
}

.fl-bigmug-line-giftbox54:before {
  content: "\e051";
}

.fl-bigmug-line-graphical8:before {
  content: "\e052";
}

.fl-bigmug-line-headphones32:before {
  content: "\e053";
}

.fl-bigmug-line-hot67:before {
  content: "\e054";
}

.fl-bigmug-line-images21:before {
  content: "\e055";
}

.fl-bigmug-line-ink12:before {
  content: "\e056";
}

.fl-bigmug-line-label25:before {
  content: "\e057";
}

.fl-bigmug-line-left144:before {
  content: "\e058";
}

.fl-bigmug-line-left145:before {
  content: "\e059";
}

.fl-bigmug-line-left146:before {
  content: "\e05a";
}

.fl-bigmug-line-left148:before {
  content: "\e05b";
}

.fl-bigmug-line-left152:before {
  content: "\e05c";
}

.fl-bigmug-line-left153:before {
  content: "\e05d";
}

.fl-bigmug-line-left158:before {
  content: "\e05e";
}

.fl-bigmug-line-left159:before {
  content: "\e05f";
}

.fl-bigmug-line-like51:before {
  content: "\e060";
}

.fl-bigmug-line-link52:before {
  content: "\e061";
}

.fl-bigmug-line-list63:before {
  content: "\e062";
}

.fl-bigmug-line-list65:before {
  content: "\e063";
}

.fl-bigmug-line-lock64:before {
  content: "\e064";
}

.fl-bigmug-line-login12:before {
  content: "\e065";
}

.fl-bigmug-line-login9:before {
  content: "\e066";
}

.fl-bigmug-line-map87:before {
  content: "\e067";
}

.fl-bigmug-line-megaphone11:before {
  content: "\e068";
}

.fl-bigmug-line-men25:before {
  content: "\e069";
}

.fl-bigmug-line-menu40:before {
  content: "\e06a";
}

.fl-bigmug-line-menu41:before {
  content: "\e06b";
}

.fl-bigmug-line-microphone76:before {
  content: "\e06c";
}

.fl-bigmug-line-microphone77:before {
  content: "\e06d";
}

.fl-bigmug-line-minus79:before {
  content: "\e06e";
}

.fl-bigmug-line-minus80:before {
  content: "\e06f";
}

.fl-bigmug-line-minus83:before {
  content: "\e070";
}

.fl-bigmug-line-minus86:before {
  content: "\e071";
}

.fl-bigmug-line-monitor74:before {
  content: "\e072";
}

.fl-bigmug-line-music218:before {
  content: "\e073";
}

.fl-bigmug-line-music219:before {
  content: "\e074";
}

.fl-bigmug-line-music221:before {
  content: "\e075";
}

.fl-bigmug-line-musical100:before {
  content: "\e076";
}

.fl-bigmug-line-musical98:before {
  content: "\e077";
}

.fl-bigmug-line-mute34:before {
  content: "\e078";
}

.fl-bigmug-line-new83:before {
  content: "\e079";
}

.fl-bigmug-line-nine16:before {
  content: "\e07a";
}

.fl-bigmug-line-note35:before {
  content: "\e07b";
}

.fl-bigmug-line-notebook41:before {
  content: "\e07c";
}

.fl-bigmug-line-notification4:before {
  content: "\e07d";
}

.fl-bigmug-line-notification5:before {
  content: "\e07e";
}

.fl-bigmug-line-opened25:before {
  content: "\e07f";
}

.fl-bigmug-line-oval34:before {
  content: "\e080";
}

.fl-bigmug-line-paintbrush9:before {
  content: "\e081";
}

.fl-bigmug-line-paper122:before {
  content: "\e082";
}

.fl-bigmug-line-pause37:before {
  content: "\e083";
}

.fl-bigmug-line-pencil85:before {
  content: "\e084";
}

.fl-bigmug-line-phone351:before {
  content: "\e085";
}

.fl-bigmug-line-photo181:before {
  content: "\e086";
}

.fl-bigmug-line-pin42:before {
  content: "\e087";
}

.fl-bigmug-line-planetary2:before {
  content: "\e088";
}

.fl-bigmug-line-play83:before {
  content: "\e089";
}

.fl-bigmug-line-portfolio23:before {
  content: "\e08a";
}

.fl-bigmug-line-print34:before {
  content: "\e08b";
}

.fl-bigmug-line-radio46:before {
  content: "\e08c";
}

.fl-bigmug-line-rain30:before {
  content: "\e08d";
}

.fl-bigmug-line-rectangular78:before {
  content: "\e08e";
}

.fl-bigmug-line-recycling10:before {
  content: "\e08f";
}

.fl-bigmug-line-rewind37:before {
  content: "\e090";
}

.fl-bigmug-line-right139:before {
  content: "\e091";
}

.fl-bigmug-line-right141:before {
  content: "\e092";
}

.fl-bigmug-line-right142:before {
  content: "\e093";
}

.fl-bigmug-line-right144:before {
  content: "\e094";
}

.fl-bigmug-line-right148:before {
  content: "\e095";
}

.fl-bigmug-line-right153:before {
  content: "\e096";
}

.fl-bigmug-line-right154:before {
  content: "\e097";
}

.fl-bigmug-line-right156:before {
  content: "\e098";
}

.fl-bigmug-line-rounded51:before {
  content: "\e099";
}

.fl-bigmug-line-sand14:before {
  content: "\e09a";
}

.fl-bigmug-line-save15:before {
  content: "\e09b";
}

.fl-bigmug-line-search74:before {
  content: "\e09c";
}

.fl-bigmug-line-search78:before {
  content: "\e09d";
}

.fl-bigmug-line-share27:before {
  content: "\e09e";
}

.fl-bigmug-line-shopping198:before {
  content: "\e09f";
}

.fl-bigmug-line-shopping199:before {
  content: "\e0a0";
}

.fl-bigmug-line-shopping202:before {
  content: "\e0a1";
}

.fl-bigmug-line-shopping204:before {
  content: "\e0a2";
}

.fl-bigmug-line-shuffle17:before {
  content: "\e0a3";
}

.fl-bigmug-line-sort47:before {
  content: "\e0a4";
}

.fl-bigmug-line-sort48:before {
  content: "\e0a5";
}

.fl-bigmug-line-speaker75:before {
  content: "\e0a6";
}

.fl-bigmug-line-speaker80:before {
  content: "\e0a7";
}

.fl-bigmug-line-speaker81:before {
  content: "\e0a8";
}

.fl-bigmug-line-speaker86:before {
  content: "\e0a9";
}

.fl-bigmug-line-speaker87:before {
  content: "\e0aa";
}

.fl-bigmug-line-speech96:before {
  content: "\e0ab";
}

.fl-bigmug-line-square152:before {
  content: "\e0ac";
}

.fl-bigmug-line-square156:before {
  content: "\e0ad";
}

.fl-bigmug-line-square160:before {
  content: "\e0ae";
}

.fl-bigmug-line-store10:before {
  content: "\e0af";
}

.fl-bigmug-line-sun81:before {
  content: "\e0b0";
}

.fl-bigmug-line-sunrise3:before {
  content: "\e0b1";
}

.fl-bigmug-line-switch23:before {
  content: "\e0b2";
}

.fl-bigmug-line-switch24:before {
  content: "\e0b3";
}

.fl-bigmug-line-tag47:before {
  content: "\e0b4";
}

.fl-bigmug-line-television20:before {
  content: "\e0b5";
}

.fl-bigmug-line-text108:before {
  content: "\e0b6";
}

.fl-bigmug-line-text109:before {
  content: "\e0b7";
}

.fl-bigmug-line-three142:before {
  content: "\e0b8";
}

.fl-bigmug-line-timer35:before {
  content: "\e0b9";
}

.fl-bigmug-line-tool16:before {
  content: "\e0ba";
}

.fl-bigmug-line-triangle33:before {
  content: "\e0bb";
}

.fl-bigmug-line-trophy55:before {
  content: "\e0bc";
}

.fl-bigmug-line-two311:before {
  content: "\e0bd";
}

.fl-bigmug-line-two316:before {
  content: "\e0be";
}

.fl-bigmug-line-two317:before {
  content: "\e0bf";
}

.fl-bigmug-line-two319:before {
  content: "\e0c0";
}

.fl-bigmug-line-two323:before {
  content: "\e0c1";
}

.fl-bigmug-line-unlocked27:before {
  content: "\e0c2";
}

.fl-bigmug-line-up100:before {
  content: "\e0c3";
}

.fl-bigmug-line-up102:before {
  content: "\e0c4";
}

.fl-bigmug-line-up103:before {
  content: "\e0c5";
}

.fl-bigmug-line-up104:before {
  content: "\e0c6";
}

.fl-bigmug-line-up107:before {
  content: "\e0c7";
}

.fl-bigmug-line-up111:before {
  content: "\e0c8";
}

.fl-bigmug-line-up112:before {
  content: "\e0c9";
}

.fl-bigmug-line-up114:before {
  content: "\e0ca";
}

.fl-bigmug-line-up98:before {
  content: "\e0cb";
}

.fl-bigmug-line-up99:before {
  content: "\e0cc";
}

.fl-bigmug-line-upload91:before {
  content: "\e0cd";
}

.fl-bigmug-line-upload92:before {
  content: "\e0ce";
}

.fl-bigmug-line-upper8:before {
  content: "\e0cf";
}

.fl-bigmug-line-user143:before {
  content: "\e0d0";
}

.fl-bigmug-line-user144:before {
  content: "\e0d1";
}

.fl-bigmug-line-video163:before {
  content: "\e0d2";
}

.fl-bigmug-line-wallet26:before {
  content: "\e0d3";
}

.fl-bigmug-line-weather21:before {
  content: "\e0d4";
}

.fl-bigmug-line-weekly14:before {
  content: "\e0d5";
}

.fl-bigmug-line-weekly15:before {
  content: "\e0d6";
}

.fl-bigmug-line-wind24:before {
  content: "\e0d7";
}

.fl-bigmug-line-window50:before {
  content: "\e0d8";
}

.fl-bigmug-line-winds4:before {
  content: "\e0d9";
}

.fl-bigmug-line-wrench66:before {
  content: "\e0da";
}

.fl-bigmug-line-zoom60:before {
  content: "\e0db";
}

/*
 * Custom Plugins
 */
/**
* @subsection   Animate.css
*
* @description  A bunch of cool, fun, and cross-browser animations
*               for you to use.
*
* @author       Daniel Eden
* @link         http://daneden.me/animate
* @license      MIT license - http://opensource.org/licenses/MIT
*/
.animated {
  -webkit-animation-duration: 1s;
  animation-duration: 1s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  opacity: 1;
}

.animated.infinite {
  -webkit-animation-iteration-count: infinite;
  animation-iteration-count: infinite;
}

.animated.hinge {
  -webkit-animation-duration: 2s;
  animation-duration: 2s;
}

html:not(.lt-ie10) .not-animated {
  opacity: 0;
}

/**
* Bounce Keyframes Animation
*/
@-webkit-keyframes bounce {
  0%, 20%, 53%, 80%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  40%, 43% {
    -webkit-transition-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
    transition-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
    -webkit-transform: translate3d(0, -30px, 0);
    transform: translate3d(0, -30px, 0);
  }
  70% {
    -webkit-transition-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
    transition-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
    -webkit-transform: translate3d(0, -15px, 0);
    transform: translate3d(0, -15px, 0);
  }
  90% {
    -webkit-transform: translate3d(0, -4px, 0);
    transform: translate3d(0, -4px, 0);
  }
}

.bounce {
  -webkit-animation-name: bounce;
  animation-name: bounce;
  -webkit-transform-origin: center bottom;
  transform-origin: center bottom;
}

/**
* Flas Keyframes Animation
*/
@-webkit-keyframes flash {
  0%, 50%, 100% {
    opacity: 1;
  }
  25%, 75% {
    opacity: 0;
  }
}

@keyframes flash {
  0%, 50%, 100% {
    opacity: 1;
  }
  25%, 75% {
    opacity: 0;
  }
}

.flash {
  -webkit-animation-name: flash;
  animation-name: flash;
}

/**
* Pulse Keyframes Animation
*
* @author Nick Pettit
* @link https://github.com/nickpettit/glide
*/
@-webkit-keyframes pulse {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
  50% {
    -webkit-transform: scale3d(1.05, 1.05, 1.05);
    transform: scale3d(1.05, 1.05, 1.05);
  }
  100% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

@keyframes pulse {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
  50% {
    -webkit-transform: scale3d(1.05, 1.05, 1.05);
    transform: scale3d(1.05, 1.05, 1.05);
  }
  100% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

.pulse {
  -webkit-animation-name: pulse;
  animation-name: pulse;
}

/**
* RubberBand Keyframes Animation
*/
@-webkit-keyframes rubberBand {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
  30% {
    -webkit-transform: scale3d(1.25, 0.75, 1);
    transform: scale3d(1.25, 0.75, 1);
  }
  40% {
    -webkit-transform: scale3d(0.75, 1.25, 1);
    transform: scale3d(0.75, 1.25, 1);
  }
  50% {
    -webkit-transform: scale3d(1.15, 0.85, 1);
    transform: scale3d(1.15, 0.85, 1);
  }
  65% {
    -webkit-transform: scale3d(0.95, 1.05, 1);
    transform: scale3d(0.95, 1.05, 1);
  }
  75% {
    -webkit-transform: scale3d(1.05, 0.95, 1);
    transform: scale3d(1.05, 0.95, 1);
  }
  100% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

@keyframes rubberBand {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
  30% {
    -webkit-transform: scale3d(1.25, 0.75, 1);
    transform: scale3d(1.25, 0.75, 1);
  }
  40% {
    -webkit-transform: scale3d(0.75, 1.25, 1);
    transform: scale3d(0.75, 1.25, 1);
  }
  50% {
    -webkit-transform: scale3d(1.15, 0.85, 1);
    transform: scale3d(1.15, 0.85, 1);
  }
  65% {
    -webkit-transform: scale3d(0.95, 1.05, 1);
    transform: scale3d(0.95, 1.05, 1);
  }
  75% {
    -webkit-transform: scale3d(1.05, 0.95, 1);
    transform: scale3d(1.05, 0.95, 1);
  }
  100% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

.rubberBand {
  -webkit-animation-name: rubberBand;
  animation-name: rubberBand;
}

/**
* Shake Keyframes Animation
*/
@-webkit-keyframes shake {
  0%, 100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  10%, 30%, 50%, 70%, 90% {
    -webkit-transform: translate3d(-10px, 0, 0);
    transform: translate3d(-10px, 0, 0);
  }
  20%, 40%, 60%, 80% {
    -webkit-transform: translate3d(10px, 0, 0);
    transform: translate3d(10px, 0, 0);
  }
}

@keyframes shake {
  0%, 100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  10%, 30%, 50%, 70%, 90% {
    -webkit-transform: translate3d(-10px, 0, 0);
    transform: translate3d(-10px, 0, 0);
  }
  20%, 40%, 60%, 80% {
    -webkit-transform: translate3d(10px, 0, 0);
    transform: translate3d(10px, 0, 0);
  }
}

.shake {
  -webkit-animation-name: shake;
  animation-name: shake;
}

/**
* Swing Keyframes Animation
*/
@-webkit-keyframes swing {
  20% {
    -webkit-transform: rotate3d(0, 0, 1, 15deg);
    transform: rotate3d(0, 0, 1, 15deg);
  }
  40% {
    -webkit-transform: rotate3d(0, 0, 1, -10deg);
    transform: rotate3d(0, 0, 1, -10deg);
  }
  60% {
    -webkit-transform: rotate3d(0, 0, 1, 5deg);
    transform: rotate3d(0, 0, 1, 5deg);
  }
  80% {
    -webkit-transform: rotate3d(0, 0, 1, -5deg);
    transform: rotate3d(0, 0, 1, -5deg);
  }
  100% {
    -webkit-transform: rotate3d(0, 0, 1, 0deg);
    transform: rotate3d(0, 0, 1, 0deg);
  }
}

@keyframes swing {
  20% {
    -webkit-transform: rotate3d(0, 0, 1, 15deg);
    transform: rotate3d(0, 0, 1, 15deg);
  }
  40% {
    -webkit-transform: rotate3d(0, 0, 1, -10deg);
    transform: rotate3d(0, 0, 1, -10deg);
  }
  60% {
    -webkit-transform: rotate3d(0, 0, 1, 5deg);
    transform: rotate3d(0, 0, 1, 5deg);
  }
  80% {
    -webkit-transform: rotate3d(0, 0, 1, -5deg);
    transform: rotate3d(0, 0, 1, -5deg);
  }
  100% {
    -webkit-transform: rotate3d(0, 0, 1, 0deg);
    transform: rotate3d(0, 0, 1, 0deg);
  }
}

.swing {
  -webkit-transform-origin: top center;
  transform-origin: top center;
  -webkit-animation-name: swing;
  animation-name: swing;
}

/**
* Tada Keyframes Animation
*/
@-webkit-keyframes tada {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
  10%, 20% {
    -webkit-transform: scale3d(0.9, 0.9, 0.9) rotate3d(0, 0, 1, -3deg);
    transform: scale3d(0.9, 0.9, 0.9) rotate3d(0, 0, 1, -3deg);
  }
  30%, 50%, 70%, 90% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, 3deg);
    transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, 3deg);
  }
  40%, 60%, 80% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, -3deg);
    transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, -3deg);
  }
  100% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

@keyframes tada {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
  10%, 20% {
    -webkit-transform: scale3d(0.9, 0.9, 0.9) rotate3d(0, 0, 1, -3deg);
    transform: scale3d(0.9, 0.9, 0.9) rotate3d(0, 0, 1, -3deg);
  }
  30%, 50%, 70%, 90% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, 3deg);
    transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, 3deg);
  }
  40%, 60%, 80% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, -3deg);
    transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, -3deg);
  }
  100% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

.tada {
  -webkit-animation-name: tada;
  animation-name: tada;
}

/**
* Wobble Keyframes Animation
*
* @author Nick Pettit
* @link https://github.com/nickpettit/glide
*/
@-webkit-keyframes wobble {
  0% {
    -webkit-transform: none;
    transform: none;
  }
  15% {
    -webkit-transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
    transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
  }
  30% {
    -webkit-transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
    transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
  }
  45% {
    -webkit-transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
    transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
  }
  60% {
    -webkit-transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
    transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
  }
  75% {
    -webkit-transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
    transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
  }
  100% {
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes wobble {
  0% {
    -webkit-transform: none;
    transform: none;
  }
  15% {
    -webkit-transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
    transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
  }
  30% {
    -webkit-transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
    transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
  }
  45% {
    -webkit-transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
    transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
  }
  60% {
    -webkit-transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
    transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
  }
  75% {
    -webkit-transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
    transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
  }
  100% {
    -webkit-transform: none;
    transform: none;
  }
}

.wobble {
  -webkit-animation-name: wobble;
  animation-name: wobble;
}

/**
* BounceIn Keyframes Animation
*/
@-webkit-keyframes bounceIn {
  0%, 20%, 40%, 60%, 80%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  }
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.3, 0.3, 0.3);
    transform: scale3d(0.3, 0.3, 0.3);
  }
  20% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1);
    transform: scale3d(1.1, 1.1, 1.1);
  }
  40% {
    -webkit-transform: scale3d(0.9, 0.9, 0.9);
    transform: scale3d(0.9, 0.9, 0.9);
  }
  60% {
    opacity: 1;
    -webkit-transform: scale3d(1.03, 1.03, 1.03);
    transform: scale3d(1.03, 1.03, 1.03);
  }
  80% {
    -webkit-transform: scale3d(0.97, 0.97, 0.97);
    transform: scale3d(0.97, 0.97, 0.97);
  }
  100% {
    opacity: 1;
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

@keyframes bounceIn {
  0%, 20%, 40%, 60%, 80%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  }
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.3, 0.3, 0.3);
    transform: scale3d(0.3, 0.3, 0.3);
  }
  20% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1);
    transform: scale3d(1.1, 1.1, 1.1);
  }
  40% {
    -webkit-transform: scale3d(0.9, 0.9, 0.9);
    transform: scale3d(0.9, 0.9, 0.9);
  }
  60% {
    opacity: 1;
    -webkit-transform: scale3d(1.03, 1.03, 1.03);
    transform: scale3d(1.03, 1.03, 1.03);
  }
  80% {
    -webkit-transform: scale3d(0.97, 0.97, 0.97);
    transform: scale3d(0.97, 0.97, 0.97);
  }
  100% {
    opacity: 1;
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

.bounceIn {
  -webkit-animation-name: bounceIn;
  animation-name: bounceIn;
  -webkit-animation-duration: .75s;
  animation-duration: .75s;
}

/**
* BounceInDown Keyframes Animation
*/
@-webkit-keyframes bounceInDown {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  }
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -3000px, 0);
    transform: translate3d(0, -3000px, 0);
  }
  60% {
    opacity: 1;
    -webkit-transform: translate3d(0, 25px, 0);
    transform: translate3d(0, 25px, 0);
  }
  75% {
    -webkit-transform: translate3d(0, -10px, 0);
    transform: translate3d(0, -10px, 0);
  }
  90% {
    -webkit-transform: translate3d(0, 5px, 0);
    transform: translate3d(0, 5px, 0);
  }
  100% {
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes bounceInDown {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  }
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -3000px, 0);
    transform: translate3d(0, -3000px, 0);
  }
  60% {
    opacity: 1;
    -webkit-transform: translate3d(0, 25px, 0);
    transform: translate3d(0, 25px, 0);
  }
  75% {
    -webkit-transform: translate3d(0, -10px, 0);
    transform: translate3d(0, -10px, 0);
  }
  90% {
    -webkit-transform: translate3d(0, 5px, 0);
    transform: translate3d(0, 5px, 0);
  }
  100% {
    -webkit-transform: none;
    transform: none;
  }
}

.bounceInDown {
  -webkit-animation-name: bounceInDown;
  animation-name: bounceInDown;
}

/**
* BounceInLeft Keyframes Animation
*/
@-webkit-keyframes bounceInLeft {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  }
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-3000px, 0, 0);
    transform: translate3d(-3000px, 0, 0);
  }
  60% {
    opacity: 1;
    -webkit-transform: translate3d(25px, 0, 0);
    transform: translate3d(25px, 0, 0);
  }
  75% {
    -webkit-transform: translate3d(-10px, 0, 0);
    transform: translate3d(-10px, 0, 0);
  }
  90% {
    -webkit-transform: translate3d(5px, 0, 0);
    transform: translate3d(5px, 0, 0);
  }
  100% {
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes bounceInLeft {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  }
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-3000px, 0, 0);
    transform: translate3d(-3000px, 0, 0);
  }
  60% {
    opacity: 1;
    -webkit-transform: translate3d(25px, 0, 0);
    transform: translate3d(25px, 0, 0);
  }
  75% {
    -webkit-transform: translate3d(-10px, 0, 0);
    transform: translate3d(-10px, 0, 0);
  }
  90% {
    -webkit-transform: translate3d(5px, 0, 0);
    transform: translate3d(5px, 0, 0);
  }
  100% {
    -webkit-transform: none;
    transform: none;
  }
}

.bounceInLeft {
  -webkit-animation-name: bounceInLeft;
  animation-name: bounceInLeft;
}

/**
* BounceInRight Keyframes Animation
*/
@-webkit-keyframes bounceInRight {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  }
  0% {
    opacity: 0;
    -webkit-transform: translate3d(3000px, 0, 0);
    transform: translate3d(3000px, 0, 0);
  }
  60% {
    opacity: 1;
    -webkit-transform: translate3d(-25px, 0, 0);
    transform: translate3d(-25px, 0, 0);
  }
  75% {
    -webkit-transform: translate3d(10px, 0, 0);
    transform: translate3d(10px, 0, 0);
  }
  90% {
    -webkit-transform: translate3d(-5px, 0, 0);
    transform: translate3d(-5px, 0, 0);
  }
  100% {
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes bounceInRight {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  }
  0% {
    opacity: 0;
    -webkit-transform: translate3d(3000px, 0, 0);
    transform: translate3d(3000px, 0, 0);
  }
  60% {
    opacity: 1;
    -webkit-transform: translate3d(-25px, 0, 0);
    transform: translate3d(-25px, 0, 0);
  }
  75% {
    -webkit-transform: translate3d(10px, 0, 0);
    transform: translate3d(10px, 0, 0);
  }
  90% {
    -webkit-transform: translate3d(-5px, 0, 0);
    transform: translate3d(-5px, 0, 0);
  }
  100% {
    -webkit-transform: none;
    transform: none;
  }
}

.bounceInRight {
  -webkit-animation-name: bounceInRight;
  animation-name: bounceInRight;
}

/**
* BounceInUp Keyframes Animation
*/
@-webkit-keyframes bounceInUp {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  }
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 3000px, 0);
    transform: translate3d(0, 3000px, 0);
  }
  60% {
    opacity: 1;
    -webkit-transform: translate3d(0, -20px, 0);
    transform: translate3d(0, -20px, 0);
  }
  75% {
    -webkit-transform: translate3d(0, 10px, 0);
    transform: translate3d(0, 10px, 0);
  }
  90% {
    -webkit-transform: translate3d(0, -5px, 0);
    transform: translate3d(0, -5px, 0);
  }
  100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
}

@keyframes bounceInUp {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  }
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 3000px, 0);
    transform: translate3d(0, 3000px, 0);
  }
  60% {
    opacity: 1;
    -webkit-transform: translate3d(0, -20px, 0);
    transform: translate3d(0, -20px, 0);
  }
  75% {
    -webkit-transform: translate3d(0, 10px, 0);
    transform: translate3d(0, 10px, 0);
  }
  90% {
    -webkit-transform: translate3d(0, -5px, 0);
    transform: translate3d(0, -5px, 0);
  }
  100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
}

.bounceInUp {
  -webkit-animation-name: bounceInUp;
  animation-name: bounceInUp;
}

/**
* BounceOut Keyframes Animation
*/
@-webkit-keyframes bounceOut {
  20% {
    -webkit-transform: scale3d(0.9, 0.9, 0.9);
    transform: scale3d(0.9, 0.9, 0.9);
  }
  50%, 55% {
    opacity: 1;
    -webkit-transform: scale3d(1.1, 1.1, 1.1);
    transform: scale3d(1.1, 1.1, 1.1);
  }
  100% {
    opacity: 0;
    -webkit-transform: scale3d(0.3, 0.3, 0.3);
    transform: scale3d(0.3, 0.3, 0.3);
  }
}

@keyframes bounceOut {
  20% {
    -webkit-transform: scale3d(0.9, 0.9, 0.9);
    transform: scale3d(0.9, 0.9, 0.9);
  }
  50%, 55% {
    opacity: 1;
    -webkit-transform: scale3d(1.1, 1.1, 1.1);
    transform: scale3d(1.1, 1.1, 1.1);
  }
  100% {
    opacity: 0;
    -webkit-transform: scale3d(0.3, 0.3, 0.3);
    transform: scale3d(0.3, 0.3, 0.3);
  }
}

.bounceOut {
  -webkit-animation-name: bounceOut;
  animation-name: bounceOut;
  -webkit-animation-duration: .75s;
  animation-duration: .75s;
}

/**
* BounceOutDown Keyframes Animation
*/
@-webkit-keyframes bounceOutDown {
  20% {
    -webkit-transform: translate3d(0, 10px, 0);
    transform: translate3d(0, 10px, 0);
  }
  40%, 45% {
    opacity: 1;
    -webkit-transform: translate3d(0, -20px, 0);
    transform: translate3d(0, -20px, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
    transform: translate3d(0, 2000px, 0);
  }
}

@keyframes bounceOutDown {
  20% {
    -webkit-transform: translate3d(0, 10px, 0);
    transform: translate3d(0, 10px, 0);
  }
  40%, 45% {
    opacity: 1;
    -webkit-transform: translate3d(0, -20px, 0);
    transform: translate3d(0, -20px, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
    transform: translate3d(0, 2000px, 0);
  }
}

.bounceOutDown {
  -webkit-animation-name: bounceOutDown;
  animation-name: bounceOutDown;
}

/**
* BounceOutLeft Keyframes Animation
*/
@-webkit-keyframes bounceOutLeft {
  20% {
    opacity: 1;
    -webkit-transform: translate3d(20px, 0, 0);
    transform: translate3d(20px, 0, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
    transform: translate3d(-2000px, 0, 0);
  }
}

@keyframes bounceOutLeft {
  20% {
    opacity: 1;
    -webkit-transform: translate3d(20px, 0, 0);
    transform: translate3d(20px, 0, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
    transform: translate3d(-2000px, 0, 0);
  }
}

.bounceOutLeft {
  -webkit-animation-name: bounceOutLeft;
  animation-name: bounceOutLeft;
}

/**
* BounceOutRight Keyframes Animation
*/
@-webkit-keyframes bounceOutRight {
  20% {
    opacity: 1;
    -webkit-transform: translate3d(-20px, 0, 0);
    transform: translate3d(-20px, 0, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
    transform: translate3d(2000px, 0, 0);
  }
}

@keyframes bounceOutRight {
  20% {
    opacity: 1;
    -webkit-transform: translate3d(-20px, 0, 0);
    transform: translate3d(-20px, 0, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
    transform: translate3d(2000px, 0, 0);
  }
}

.bounceOutRight {
  -webkit-animation-name: bounceOutRight;
  animation-name: bounceOutRight;
}

/**
* BounceOutUp Keyframes Animation
*/
@-webkit-keyframes bounceOutUp {
  20% {
    -webkit-transform: translate3d(0, -10px, 0);
    transform: translate3d(0, -10px, 0);
  }
  40%, 45% {
    opacity: 1;
    -webkit-transform: translate3d(0, 20px, 0);
    transform: translate3d(0, 20px, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
    transform: translate3d(0, -2000px, 0);
  }
}

@keyframes bounceOutUp {
  20% {
    -webkit-transform: translate3d(0, -10px, 0);
    transform: translate3d(0, -10px, 0);
  }
  40%, 45% {
    opacity: 1;
    -webkit-transform: translate3d(0, 20px, 0);
    transform: translate3d(0, 20px, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
    transform: translate3d(0, -2000px, 0);
  }
}

.bounceOutUp {
  -webkit-animation-name: bounceOutUp;
  animation-name: bounceOutUp;
}

/**
* FadeIn Keyframes Animation
*/
@-webkit-keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

.fadeIn {
  -webkit-animation-name: fadeIn;
  animation-name: fadeIn;
}

/**
* FadeInDown Keyframes Animation
*/
@-webkit-keyframes fadeInDown {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -100%, 0);
    transform: translate3d(0, -100%, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes fadeInDown {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -100%, 0);
    transform: translate3d(0, -100%, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

.fadeInDown {
  -webkit-animation-name: fadeInDown;
  animation-name: fadeInDown;
}

/**
* FadeInDownBig Keyframes Animation
*/
@-webkit-keyframes fadeInDownBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
    transform: translate3d(0, -2000px, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes fadeInDownBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
    transform: translate3d(0, -2000px, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

.fadeInDownBig {
  -webkit-animation-name: fadeInDownBig;
  animation-name: fadeInDownBig;
}

/**
* FadeInLeft Keyframes Animation
*/
@-webkit-keyframes fadeInLeft {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes fadeInLeft {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

.fadeInLeft {
  -webkit-animation-name: fadeInLeft;
  animation-name: fadeInLeft;
}

/**
* FadeInLeftBig Keyframes Animation
*/
@-webkit-keyframes fadeInLeftBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
    transform: translate3d(-2000px, 0, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes fadeInLeftBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
    transform: translate3d(-2000px, 0, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

.fadeInLeftBig {
  -webkit-animation-name: fadeInLeftBig;
  animation-name: fadeInLeftBig;
}

/**
* FadeInRight Keyframes Animation
*/
@-webkit-keyframes fadeInRight {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes fadeInRight {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

.fadeInRight {
  -webkit-animation-name: fadeInRight;
  animation-name: fadeInRight;
}

/**
* FadeInRightBig Keyframes Animation
*/
@-webkit-keyframes fadeInRightBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
    transform: translate3d(2000px, 0, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes fadeInRightBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
    transform: translate3d(2000px, 0, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

.fadeInRightBig {
  -webkit-animation-name: fadeInRightBig;
  animation-name: fadeInRightBig;
}

/**
* FadeInUp Keyframes Animation
*/
@-webkit-keyframes fadeInUp {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 100%, 0);
    transform: translate3d(0, 100%, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes fadeInUp {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 100%, 0);
    transform: translate3d(0, 100%, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

.fadeInUp {
  -webkit-animation-name: fadeInUp;
  animation-name: fadeInUp;
}

/**
* FadeInUpBig Keyframes Animation
*/
@-webkit-keyframes fadeInUpBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
    transform: translate3d(0, 2000px, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes fadeInUpBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
    transform: translate3d(0, 2000px, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

.fadeInUpBig {
  -webkit-animation-name: fadeInUpBig;
  animation-name: fadeInUpBig;
}

/**
* FadeOut Keyframes Animation
*/
@-webkit-keyframes fadeOut {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
}

@keyframes fadeOut {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
}

.fadeOut {
  -webkit-animation-name: fadeOut;
  animation-name: fadeOut;
}

/**
* FadeOutDown Keyframes Animation
*/
@-webkit-keyframes fadeOutDown {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 100%, 0);
    transform: translate3d(0, 100%, 0);
  }
}

@keyframes fadeOutDown {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 100%, 0);
    transform: translate3d(0, 100%, 0);
  }
}

.fadeOutDown {
  -webkit-animation-name: fadeOutDown;
  animation-name: fadeOutDown;
}

/**
* FadeOutDownBig Keyframes Animation
*/
@-webkit-keyframes fadeOutDownBig {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
    transform: translate3d(0, 2000px, 0);
  }
}

@keyframes fadeOutDownBig {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
    transform: translate3d(0, 2000px, 0);
  }
}

.fadeOutDownBig {
  -webkit-animation-name: fadeOutDownBig;
  animation-name: fadeOutDownBig;
}

/**
* FadeOutLeft Keyframes Animation
*/
@-webkit-keyframes fadeOutLeft {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
  }
}

@keyframes fadeOutLeft {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
  }
}

.fadeOutLeft {
  -webkit-animation-name: fadeOutLeft;
  animation-name: fadeOutLeft;
}

/**
* FadeOutLeftBig Keyframes Animation
*/
@-webkit-keyframes fadeOutLeftBig {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
    transform: translate3d(-2000px, 0, 0);
  }
}

@keyframes fadeOutLeftBig {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
    transform: translate3d(-2000px, 0, 0);
  }
}

.fadeOutLeftBig {
  -webkit-animation-name: fadeOutLeftBig;
  animation-name: fadeOutLeftBig;
}

/**
* FadeOutRight Keyframes Animation
*/
@-webkit-keyframes fadeOutRight {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
  }
}

@keyframes fadeOutRight {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
  }
}

.fadeOutRight {
  -webkit-animation-name: fadeOutRight;
  animation-name: fadeOutRight;
}

/**
* FadeOutRightBig Keyframes Animation
*/
@-webkit-keyframes fadeOutRightBig {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
    transform: translate3d(2000px, 0, 0);
  }
}

@keyframes fadeOutRightBig {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
    transform: translate3d(2000px, 0, 0);
  }
}

.fadeOutRightBig {
  -webkit-animation-name: fadeOutRightBig;
  animation-name: fadeOutRightBig;
}

/**
* FadeOutUp Keyframes Animation
*/
@-webkit-keyframes fadeOutUp {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -100%, 0);
    transform: translate3d(0, -100%, 0);
  }
}

@keyframes fadeOutUp {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -100%, 0);
    transform: translate3d(0, -100%, 0);
  }
}

.fadeOutUp {
  -webkit-animation-name: fadeOutUp;
  animation-name: fadeOutUp;
}

/**
* FadeOutUpBig Keyframes Animation
*/
@-webkit-keyframes fadeOutUpBig {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
    transform: translate3d(0, -2000px, 0);
  }
}

@keyframes fadeOutUpBig {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
    transform: translate3d(0, -2000px, 0);
  }
}

.fadeOutUpBig {
  -webkit-animation-name: fadeOutUpBig;
  animation-name: fadeOutUpBig;
}

/**
* Flip Keyframes Animation
*/
@-webkit-keyframes flip {
  0% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -360deg);
    transform: perspective(400px) rotate3d(0, 1, 0, -360deg);
    -webkit-animation-timing-function: ease-out;
    animation-timing-function: ease-out;
  }
  40% {
    -webkit-transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -190deg);
    transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -190deg);
    -webkit-animation-timing-function: ease-out;
    animation-timing-function: ease-out;
  }
  50% {
    -webkit-transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -170deg);
    transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -170deg);
    -webkit-animation-timing-function: ease-in;
    animation-timing-function: ease-in;
  }
  80% {
    -webkit-transform: perspective(400px) scale3d(0.95, 0.95, 0.95);
    transform: perspective(400px) scale3d(0.95, 0.95, 0.95);
    -webkit-animation-timing-function: ease-in;
    animation-timing-function: ease-in;
  }
  100% {
    -webkit-transform: perspective(400px);
    transform: perspective(400px);
    -webkit-animation-timing-function: ease-in;
    animation-timing-function: ease-in;
  }
}

@keyframes flip {
  0% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -360deg);
    transform: perspective(400px) rotate3d(0, 1, 0, -360deg);
    -webkit-animation-timing-function: ease-out;
    animation-timing-function: ease-out;
  }
  40% {
    -webkit-transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -190deg);
    transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -190deg);
    -webkit-animation-timing-function: ease-out;
    animation-timing-function: ease-out;
  }
  50% {
    -webkit-transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -170deg);
    transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -170deg);
    -webkit-animation-timing-function: ease-in;
    animation-timing-function: ease-in;
  }
  80% {
    -webkit-transform: perspective(400px) scale3d(0.95, 0.95, 0.95);
    transform: perspective(400px) scale3d(0.95, 0.95, 0.95);
    -webkit-animation-timing-function: ease-in;
    animation-timing-function: ease-in;
  }
  100% {
    -webkit-transform: perspective(400px);
    transform: perspective(400px);
    -webkit-animation-timing-function: ease-in;
    animation-timing-function: ease-in;
  }
}

.animated.flip {
  -webkit-backface-visibility: visible;
  backface-visibility: visible;
  -webkit-animation-name: flip;
  animation-name: flip;
}

/**
* FlipInX Keyframes Animation
*/
@-webkit-keyframes flipInX {
  0% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    -webkit-transition-timing-function: ease-in;
    transition-timing-function: ease-in;
    opacity: 0;
  }
  40% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    -webkit-transition-timing-function: ease-in;
    transition-timing-function: ease-in;
  }
  60% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 10deg);
    transform: perspective(400px) rotate3d(1, 0, 0, 10deg);
    opacity: 1;
  }
  80% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -5deg);
    transform: perspective(400px) rotate3d(1, 0, 0, -5deg);
  }
  100% {
    -webkit-transform: perspective(400px);
    transform: perspective(400px);
  }
}

@keyframes flipInX {
  0% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    -webkit-transition-timing-function: ease-in;
    transition-timing-function: ease-in;
    opacity: 0;
  }
  40% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    -webkit-transition-timing-function: ease-in;
    transition-timing-function: ease-in;
  }
  60% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 10deg);
    transform: perspective(400px) rotate3d(1, 0, 0, 10deg);
    opacity: 1;
  }
  80% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -5deg);
    transform: perspective(400px) rotate3d(1, 0, 0, -5deg);
  }
  100% {
    -webkit-transform: perspective(400px);
    transform: perspective(400px);
  }
}

.flipInX {
  -webkit-backface-visibility: visible !important;
  backface-visibility: visible !important;
  -webkit-animation-name: flipInX;
  animation-name: flipInX;
}

/**
* FlipInY Keyframes Animation
*/
@-webkit-keyframes flipInY {
  0% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    -webkit-transition-timing-function: ease-in;
    transition-timing-function: ease-in;
    opacity: 0;
  }
  40% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -20deg);
    transform: perspective(400px) rotate3d(0, 1, 0, -20deg);
    -webkit-transition-timing-function: ease-in;
    transition-timing-function: ease-in;
  }
  60% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 10deg);
    transform: perspective(400px) rotate3d(0, 1, 0, 10deg);
    opacity: 1;
  }
  80% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -5deg);
    transform: perspective(400px) rotate3d(0, 1, 0, -5deg);
  }
  100% {
    -webkit-transform: perspective(400px);
    transform: perspective(400px);
  }
}

@keyframes flipInY {
  0% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    -webkit-transition-timing-function: ease-in;
    transition-timing-function: ease-in;
    opacity: 0;
  }
  40% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -20deg);
    transform: perspective(400px) rotate3d(0, 1, 0, -20deg);
    -webkit-transition-timing-function: ease-in;
    transition-timing-function: ease-in;
  }
  60% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 10deg);
    transform: perspective(400px) rotate3d(0, 1, 0, 10deg);
    opacity: 1;
  }
  80% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -5deg);
    transform: perspective(400px) rotate3d(0, 1, 0, -5deg);
  }
  100% {
    -webkit-transform: perspective(400px);
    transform: perspective(400px);
  }
}

.flipInY {
  -webkit-backface-visibility: visible !important;
  backface-visibility: visible !important;
  -webkit-animation-name: flipInY;
  animation-name: flipInY;
}

/**
* FlipOutX Keyframes Animation
*/
@-webkit-keyframes flipOutX {
  0% {
    -webkit-transform: perspective(400px);
    transform: perspective(400px);
  }
  30% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    opacity: 1;
  }
  100% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    opacity: 0;
  }
}

@keyframes flipOutX {
  0% {
    -webkit-transform: perspective(400px);
    transform: perspective(400px);
  }
  30% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    opacity: 1;
  }
  100% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    opacity: 0;
  }
}

.flipOutX {
  -webkit-animation-name: flipOutX;
  animation-name: flipOutX;
  -webkit-animation-duration: .75s;
  animation-duration: .75s;
  -webkit-backface-visibility: visible !important;
  backface-visibility: visible !important;
}

/**
* FlipOutY Keyframes Animation
*/
@-webkit-keyframes flipOutY {
  0% {
    -webkit-transform: perspective(400px);
    transform: perspective(400px);
  }
  30% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -15deg);
    transform: perspective(400px) rotate3d(0, 1, 0, -15deg);
    opacity: 1;
  }
  100% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    opacity: 0;
  }
}

@keyframes flipOutY {
  0% {
    -webkit-transform: perspective(400px);
    transform: perspective(400px);
  }
  30% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -15deg);
    transform: perspective(400px) rotate3d(0, 1, 0, -15deg);
    opacity: 1;
  }
  100% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    opacity: 0;
  }
}

.flipOutY {
  -webkit-backface-visibility: visible !important;
  backface-visibility: visible !important;
  -webkit-animation-name: flipOutY;
  animation-name: flipOutY;
  -webkit-animation-duration: .75s;
  animation-duration: .75s;
}

/**
* LightSpeedIn Keyframes Animation
*/
@-webkit-keyframes lightSpeedIn {
  0% {
    -webkit-transform: translate3d(100%, 0, 0) skewX(-30deg);
    transform: translate3d(100%, 0, 0) skewX(-30deg);
    opacity: 0;
  }
  60% {
    -webkit-transform: skewX(20deg);
    transform: skewX(20deg);
    opacity: 1;
  }
  80% {
    -webkit-transform: skewX(-5deg);
    transform: skewX(-5deg);
    opacity: 1;
  }
  100% {
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

@keyframes lightSpeedIn {
  0% {
    -webkit-transform: translate3d(100%, 0, 0) skewX(-30deg);
    transform: translate3d(100%, 0, 0) skewX(-30deg);
    opacity: 0;
  }
  60% {
    -webkit-transform: skewX(20deg);
    transform: skewX(20deg);
    opacity: 1;
  }
  80% {
    -webkit-transform: skewX(-5deg);
    transform: skewX(-5deg);
    opacity: 1;
  }
  100% {
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

.lightSpeedIn {
  -webkit-animation-name: lightSpeedIn;
  animation-name: lightSpeedIn;
  -webkit-animation-timing-function: ease-out;
  animation-timing-function: ease-out;
}

/**
* LightSpeedOut Keyframes Animation
*/
@-webkit-keyframes lightSpeedOut {
  0% {
    opacity: 1;
  }
  100% {
    -webkit-transform: translate3d(100%, 0, 0) skewX(30deg);
    transform: translate3d(100%, 0, 0) skewX(30deg);
    opacity: 0;
  }
}

@keyframes lightSpeedOut {
  0% {
    opacity: 1;
  }
  100% {
    -webkit-transform: translate3d(100%, 0, 0) skewX(30deg);
    transform: translate3d(100%, 0, 0) skewX(30deg);
    opacity: 0;
  }
}

.lightSpeedOut {
  -webkit-animation-name: lightSpeedOut;
  animation-name: lightSpeedOut;
  -webkit-animation-timing-function: ease-in;
  animation-timing-function: ease-in;
}

/**
* RotateIn Keyframes Animation
*/
@-webkit-keyframes rotateIn {
  0% {
    -webkit-transform-origin: center;
    transform-origin: center;
    -webkit-transform: rotate3d(0, 0, 1, -200deg);
    transform: rotate3d(0, 0, 1, -200deg);
    opacity: 0;
  }
  100% {
    -webkit-transform-origin: center;
    transform-origin: center;
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

@keyframes rotateIn {
  0% {
    -webkit-transform-origin: center;
    transform-origin: center;
    -webkit-transform: rotate3d(0, 0, 1, -200deg);
    transform: rotate3d(0, 0, 1, -200deg);
    opacity: 0;
  }
  100% {
    -webkit-transform-origin: center;
    transform-origin: center;
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

.rotateIn {
  -webkit-animation-name: rotateIn;
  animation-name: rotateIn;
}

/**
* RotateInDownLeft Keyframes Animation
*/
@-webkit-keyframes rotateInDownLeft {
  0% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
    transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }
  100% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

@keyframes rotateInDownLeft {
  0% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
    transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }
  100% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

.rotateInDownLeft {
  -webkit-animation-name: rotateInDownLeft;
  animation-name: rotateInDownLeft;
}

/**
* RotateInDownRight Keyframes Animation
*/
@-webkit-keyframes rotateInDownRight {
  0% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
    transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }
  100% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

@keyframes rotateInDownRight {
  0% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
    transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }
  100% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

.rotateInDownRight {
  -webkit-animation-name: rotateInDownRight;
  animation-name: rotateInDownRight;
}

/**
* RotateInUpLeft Keyframes Animation
*/
@-webkit-keyframes rotateInUpLeft {
  0% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
    transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }
  100% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

@keyframes rotateInUpLeft {
  0% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
    transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }
  100% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

.rotateInUpLeft {
  -webkit-animation-name: rotateInUpLeft;
  animation-name: rotateInUpLeft;
}

/**
* RotateInUpRight Keyframes Animation
*/
@-webkit-keyframes rotateInUpRight {
  0% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, -90deg);
    transform: rotate3d(0, 0, 1, -90deg);
    opacity: 0;
  }
  100% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

@keyframes rotateInUpRight {
  0% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, -90deg);
    transform: rotate3d(0, 0, 1, -90deg);
    opacity: 0;
  }
  100% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: none;
    transform: none;
    opacity: 1;
  }
}

.rotateInUpRight {
  -webkit-animation-name: rotateInUpRight;
  animation-name: rotateInUpRight;
}

/**
* RotateOut Keyframes Animation
*/
@-webkit-keyframes rotateOut {
  0% {
    -webkit-transform-origin: center;
    transform-origin: center;
    opacity: 1;
  }
  100% {
    -webkit-transform-origin: center;
    transform-origin: center;
    -webkit-transform: rotate3d(0, 0, 1, 200deg);
    transform: rotate3d(0, 0, 1, 200deg);
    opacity: 0;
  }
}

@keyframes rotateOut {
  0% {
    -webkit-transform-origin: center;
    transform-origin: center;
    opacity: 1;
  }
  100% {
    -webkit-transform-origin: center;
    transform-origin: center;
    -webkit-transform: rotate3d(0, 0, 1, 200deg);
    transform: rotate3d(0, 0, 1, 200deg);
    opacity: 0;
  }
}

.rotateOut {
  -webkit-animation-name: rotateOut;
  animation-name: rotateOut;
}

/**
* RotateOutDownLeft Keyframes Animation
*/
@-webkit-keyframes rotateOutDownLeft {
  0% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    opacity: 1;
  }
  100% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
    transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }
}

@keyframes rotateOutDownLeft {
  0% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    opacity: 1;
  }
  100% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
    transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }
}

.rotateOutDownLeft {
  -webkit-animation-name: rotateOutDownLeft;
  animation-name: rotateOutDownLeft;
}

/**
* RotateOutDownRight Keyframes Animation
*/
@-webkit-keyframes rotateOutDownRight {
  0% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    opacity: 1;
  }
  100% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
    transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }
}

@keyframes rotateOutDownRight {
  0% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    opacity: 1;
  }
  100% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
    transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }
}

.rotateOutDownRight {
  -webkit-animation-name: rotateOutDownRight;
  animation-name: rotateOutDownRight;
}

/**
* RotateOutUpLeft Keyframes Animation
*/
@-webkit-keyframes rotateOutUpLeft {
  0% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    opacity: 1;
  }
  100% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
    transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }
}

@keyframes rotateOutUpLeft {
  0% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    opacity: 1;
  }
  100% {
    -webkit-transform-origin: left bottom;
    transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
    transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }
}

.rotateOutUpLeft {
  -webkit-animation-name: rotateOutUpLeft;
  animation-name: rotateOutUpLeft;
}

/**
* RotateOutUpRight Keyframes Animation
*/
@-webkit-keyframes rotateOutUpRight {
  0% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    opacity: 1;
  }
  100% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, 90deg);
    transform: rotate3d(0, 0, 1, 90deg);
    opacity: 0;
  }
}

@keyframes rotateOutUpRight {
  0% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    opacity: 1;
  }
  100% {
    -webkit-transform-origin: right bottom;
    transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, 90deg);
    transform: rotate3d(0, 0, 1, 90deg);
    opacity: 0;
  }
}

.rotateOutUpRight {
  -webkit-animation-name: rotateOutUpRight;
  animation-name: rotateOutUpRight;
}

/**
* Hinge Keyframes Animation
*/
@-webkit-keyframes hinge {
  0% {
    -webkit-transform-origin: top left;
    transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
    animation-timing-function: ease-in-out;
  }
  20%, 60% {
    -webkit-transform: rotate3d(0, 0, 1, 80deg);
    transform: rotate3d(0, 0, 1, 80deg);
    -webkit-transform-origin: top left;
    transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
    animation-timing-function: ease-in-out;
  }
  40%, 80% {
    -webkit-transform: rotate3d(0, 0, 1, 60deg);
    transform: rotate3d(0, 0, 1, 60deg);
    -webkit-transform-origin: top left;
    transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
    animation-timing-function: ease-in-out;
    opacity: 1;
  }
  100% {
    -webkit-transform: translate3d(0, 700px, 0);
    transform: translate3d(0, 700px, 0);
    opacity: 0;
  }
}

@keyframes hinge {
  0% {
    -webkit-transform-origin: top left;
    transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
    animation-timing-function: ease-in-out;
  }
  20%, 60% {
    -webkit-transform: rotate3d(0, 0, 1, 80deg);
    transform: rotate3d(0, 0, 1, 80deg);
    -webkit-transform-origin: top left;
    transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
    animation-timing-function: ease-in-out;
  }
  40%, 80% {
    -webkit-transform: rotate3d(0, 0, 1, 60deg);
    transform: rotate3d(0, 0, 1, 60deg);
    -webkit-transform-origin: top left;
    transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
    animation-timing-function: ease-in-out;
    opacity: 1;
  }
  100% {
    -webkit-transform: translate3d(0, 700px, 0);
    transform: translate3d(0, 700px, 0);
    opacity: 0;
  }
}

.hinge {
  -webkit-animation-name: hinge;
  animation-name: hinge;
}

/**
* RollIn Keyframes Animation
*
* @author Nick Pettit
* @link https://github.com/nickpettit/glide
*/
@-webkit-keyframes rollIn {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0) rotate3d(0, 0, 1, -120deg);
    transform: translate3d(-100%, 0, 0) rotate3d(0, 0, 1, -120deg);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

@keyframes rollIn {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0) rotate3d(0, 0, 1, -120deg);
    -ms-transform: translate3d(-100%, 0, 0) rotate3d(0, 0, 1, -120deg);
    transform: translate3d(-100%, 0, 0) rotate3d(0, 0, 1, -120deg);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
  }
}

.rollIn {
  -webkit-animation-name: rollIn;
  animation-name: rollIn;
}

/**
* RollOut Keyframes Animation
*
* @author Nick Pettit
* @link https://github.com/nickpettit/glide
*/
@-webkit-keyframes rollOut {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0) rotate3d(0, 0, 1, 120deg);
    transform: translate3d(100%, 0, 0) rotate3d(0, 0, 1, 120deg);
  }
}

@keyframes rollOut {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0) rotate3d(0, 0, 1, 120deg);
    transform: translate3d(100%, 0, 0) rotate3d(0, 0, 1, 120deg);
  }
}

.rollOut {
  -webkit-animation-name: rollOut;
  animation-name: rollOut;
}

/**
* ZoomIn Keyframes Animation
*/
@-webkit-keyframes zoomIn {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.3, 0.3, 0.3);
    transform: scale3d(0.3, 0.3, 0.3);
  }
  50% {
    opacity: 1;
  }
}

@keyframes zoomIn {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.3, 0.3, 0.3);
    transform: scale3d(0.3, 0.3, 0.3);
  }
  50% {
    opacity: 1;
  }
}

.zoomIn {
  -webkit-animation-name: zoomIn;
  animation-name: zoomIn;
}

/**
* ZoomInDown Keyframes Animation
*/
@-webkit-keyframes zoomInDown {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(0, -1000px, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(0, -1000px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  60% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(0, 60px, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(0, 60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

@keyframes zoomInDown {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(0, -1000px, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(0, -1000px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  60% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(0, 60px, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(0, 60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

.zoomInDown {
  -webkit-animation-name: zoomInDown;
  animation-name: zoomInDown;
}

/**
* ZoomInLeft Keyframes Animation
*/
@-webkit-keyframes zoomInLeft {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(-1000px, 0, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(-1000px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  60% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(10px, 0, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(10px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

@keyframes zoomInLeft {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(-1000px, 0, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(-1000px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  60% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(10px, 0, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(10px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

.zoomInLeft {
  -webkit-animation-name: zoomInLeft;
  animation-name: zoomInLeft;
}

/**
* ZoomInRight Keyframes Animation
*/
@-webkit-keyframes zoomInRight {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(1000px, 0, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(1000px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  60% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(-10px, 0, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(-10px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

@keyframes zoomInRight {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(1000px, 0, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(1000px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  60% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(-10px, 0, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(-10px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

.zoomInRight {
  -webkit-animation-name: zoomInRight;
  animation-name: zoomInRight;
}

/**
* ZoomInUp Keyframes Animation
*/
@-webkit-keyframes zoomInUp {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(0, 1000px, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(0, 1000px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  60% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(0, -60px, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(0, -60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

@keyframes zoomInUp {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(0, 1000px, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(0, 1000px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  60% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(0, -60px, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(0, -60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

.zoomInUp {
  -webkit-animation-name: zoomInUp;
  animation-name: zoomInUp;
}

/**
* ZoomOut Keyframes Animation
*/
@-webkit-keyframes zoomOut {
  0% {
    opacity: 1;
  }
  50% {
    opacity: 0;
    -webkit-transform: scale3d(0.3, 0.3, 0.3);
    transform: scale3d(0.3, 0.3, 0.3);
  }
  100% {
    opacity: 0;
  }
}

@keyframes zoomOut {
  0% {
    opacity: 1;
  }
  50% {
    opacity: 0;
    -webkit-transform: scale3d(0.3, 0.3, 0.3);
    transform: scale3d(0.3, 0.3, 0.3);
  }
  100% {
    opacity: 0;
  }
}

.zoomOut {
  -webkit-animation-name: zoomOut;
  animation-name: zoomOut;
}

/**
* ZoomOutDown Keyframes Animation
*/
@-webkit-keyframes zoomOutDown {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(0, -60px, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(0, -60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  100% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(0, 2000px, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(0, 2000px, 0);
    -webkit-transform-origin: center bottom;
    transform-origin: center bottom;
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

@keyframes zoomOutDown {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(0, -60px, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(0, -60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  100% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(0, 2000px, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(0, 2000px, 0);
    -webkit-transform-origin: center bottom;
    transform-origin: center bottom;
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

.zoomOutDown {
  -webkit-animation-name: zoomOutDown;
  animation-name: zoomOutDown;
}

/**
* ZoomOutLeft Keyframes Animation
*/
@-webkit-keyframes zoomOutLeft {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(42px, 0, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(42px, 0, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: scale(0.1) translate3d(-2000px, 0, 0);
    transform: scale(0.1) translate3d(-2000px, 0, 0);
    -webkit-transform-origin: left center;
    transform-origin: left center;
  }
}

@keyframes zoomOutLeft {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(42px, 0, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(42px, 0, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: scale(0.1) translate3d(-2000px, 0, 0);
    transform: scale(0.1) translate3d(-2000px, 0, 0);
    -webkit-transform-origin: left center;
    transform-origin: left center;
  }
}

.zoomOutLeft {
  -webkit-animation-name: zoomOutLeft;
  animation-name: zoomOutLeft;
}

/**
* ZoomOutRight Keyframes Animation
*/
@-webkit-keyframes zoomOutRight {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(-42px, 0, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(-42px, 0, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: scale(0.1) translate3d(2000px, 0, 0);
    transform: scale(0.1) translate3d(2000px, 0, 0);
    -webkit-transform-origin: right center;
    transform-origin: right center;
  }
}

@keyframes zoomOutRight {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(-42px, 0, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(-42px, 0, 0);
  }
  100% {
    opacity: 0;
    -webkit-transform: scale(0.1) translate3d(2000px, 0, 0);
    transform: scale(0.1) translate3d(2000px, 0, 0);
    -webkit-transform-origin: right center;
    transform-origin: right center;
  }
}

.zoomOutRight {
  -webkit-animation-name: zoomOutRight;
  animation-name: zoomOutRight;
}

/**
* ZoomOutUp Keyframes Animation
*/
@-webkit-keyframes zoomOutUp {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(0, 60px, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(0, 60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  100% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(0, -2000px, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(0, -2000px, 0);
    -webkit-transform-origin: center bottom;
    transform-origin: center bottom;
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

@keyframes zoomOutUp {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(0.475, 0.475, 0.475) translate3d(0, 60px, 0);
    transform: scale3d(0.475, 0.475, 0.475) translate3d(0, 60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }
  100% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(0, -2000px, 0);
    transform: scale3d(0.1, 0.1, 0.1) translate3d(0, -2000px, 0);
    -webkit-transform-origin: center bottom;
    transform-origin: center bottom;
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

.zoomOutUp {
  -webkit-animation-name: zoomOutUp;
  animation-name: zoomOutUp;
}

/**
* SlideInDown Keyframes Animation
*/
@-webkit-keyframes slideInDown {
  0% {
    -webkit-transform: translate3d(0, -100%, 0);
    transform: translate3d(0, -100%, 0);
    visibility: visible;
  }
  100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
}

@keyframes slideInDown {
  0% {
    -webkit-transform: translate3d(0, -100%, 0);
    transform: translate3d(0, -100%, 0);
    visibility: visible;
  }
  100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
}

.slideInDown {
  -webkit-animation-name: slideInDown;
  animation-name: slideInDown;
}

/**
* SlideInLeft Keyframes Animation
*/
@-webkit-keyframes slideInLeft {
  0% {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    visibility: visible;
  }
  100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
}

@keyframes slideInLeft {
  0% {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    visibility: visible;
  }
  100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
}

.slideInLeft {
  -webkit-animation-name: slideInLeft;
  animation-name: slideInLeft;
}

/**
* SlideInRight Keyframes Animation
*/
@-webkit-keyframes slideInRight {
  0% {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    visibility: visible;
  }
  100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
}

@keyframes slideInRight {
  0% {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    visibility: visible;
  }
  100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
}

.slideInRight {
  -webkit-animation-name: slideInRight;
  animation-name: slideInRight;
}

/**
* SlideInUp Keyframes Animation
*/
@-webkit-keyframes slideInUp {
  0% {
    -webkit-transform: translate3d(0, 100%, 0);
    transform: translate3d(0, 100%, 0);
    visibility: visible;
  }
  100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
}

@keyframes slideInUp {
  0% {
    -webkit-transform: translate3d(0, 100%, 0);
    transform: translate3d(0, 100%, 0);
    visibility: visible;
  }
  100% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
}

.slideInUp {
  -webkit-animation-name: slideInUp;
  animation-name: slideInUp;
}

/**
* SlideOutDown Keyframes Animation
*/
@-webkit-keyframes slideOutDown {
  0% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  100% {
    visibility: hidden;
    -webkit-transform: translate3d(0, 100%, 0);
    transform: translate3d(0, 100%, 0);
  }
}

@keyframes slideOutDown {
  0% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  100% {
    visibility: hidden;
    -webkit-transform: translate3d(0, 100%, 0);
    transform: translate3d(0, 100%, 0);
  }
}

.slideOutDown {
  -webkit-animation-name: slideOutDown;
  animation-name: slideOutDown;
}

/**
* SlideOutLeft Keyframes Animation
*/
@-webkit-keyframes slideOutLeft {
  0% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  100% {
    visibility: hidden;
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
  }
}

@keyframes slideOutLeft {
  0% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  100% {
    visibility: hidden;
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
  }
}

.slideOutLeft {
  -webkit-animation-name: slideOutLeft;
  animation-name: slideOutLeft;
}

/**
* SlideOutRight Keyframes Animation
*/
@-webkit-keyframes slideOutRight {
  0% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  100% {
    visibility: hidden;
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
  }
}

@keyframes slideOutRight {
  0% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  100% {
    visibility: hidden;
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
  }
}

.slideOutRight {
  -webkit-animation-name: slideOutRight;
  animation-name: slideOutRight;
}

/**
* SlideOutUp Keyframes Animation
*/
@-webkit-keyframes slideOutUp {
  0% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  100% {
    visibility: hidden;
    -webkit-transform: translate3d(0, -100%, 0);
    transform: translate3d(0, -100%, 0);
  }
}

@keyframes slideOutUp {
  0% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  100% {
    visibility: hidden;
    -webkit-transform: translate3d(0, -100%, 0);
    transform: translate3d(0, -100%, 0);
  }
}

.slideOutUp {
  -webkit-animation-name: slideOutUp;
  animation-name: slideOutUp;
}

/*
* @subsection   RD Navbar
*
* @description  Describes style declarations for RD Navbar extension
*
* @author       Evgeniy Gusarov
* @link         https://ua.linkedin.com/pub/evgeniy-gusarov/8a/a40/54a
*/
@-webkit-keyframes rd-navbar-slide-down {
  0% {
    -webkit-transform: translateY(-100%);
    transform: translateY(-100%);
  }
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
}

@keyframes rd-navbar-slide-down {
  0% {
    -webkit-transform: translateY(-100%);
    transform: translateY(-100%);
  }
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
}

@-webkit-keyframes rd-navbar-slide-up {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
  100% {
    -webkit-transform: translateY(-100%);
    transform: translateY(-100%);
  }
}

@keyframes rd-navbar-slide-up {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
  100% {
    -webkit-transform: translateY(-100%);
    transform: translateY(-100%);
  }
}

/*
* @subsection General Styles
*/
.rd-navbar-wrap, .rd-navbar-static .rd-navbar-dropdown,
.rd-navbar-static .rd-navbar-megamenu, .rd-navbar-fullwidth .rd-navbar-dropdown,
.rd-navbar-fullwidth .rd-navbar-megamenu, .rd-navbar-fixed .rd-navbar-nav-wrap, .rd-navbar-fixed .rd-navbar-submenu, .rd-navbar-fixed .rd-navbar-search .form-group {
  transition: 0.3s all cubic-bezier(0.785, 0.135, 0.15, 0.86);
}

.rd-navbar, .rd-navbar.rd-navbar--is-clone {
  display: none;
}

.rd-navbar-fixed,
.rd-navbar-static,
.rd-navbar-fullwidth,
.rd-navbar-sidebar {
  display: block;
}

.rd-navbar--no-transition, .rd-navbar--no-transition * {
  transition: none !important;
}

.rd-navbar-wrap .contact-info {
  display: none;
}

@media (min-width: 1200px) {
  .rd-navbar-wrap .contact-info {
    display: inline-block;
  }
}

.rd-navbar-wrap .rd-navbar-brand {
  display: inline-block;
  float: left;
}

.rd-navbar-wrap .rd-navbar-brand > * {
  display: inline-block;
  vertical-align: middle;
}

.rd-navbar-wrap .rd-navbar-brand > a {
  position: relative;
  font-family: "Cinzel", serif;
  text-transform: uppercase;
  font-size: 32px;
  line-height: 48px;
  font-weight: 400;
  letter-spacing: 1.6px;
}

.rd-navbar-wrap .rd-navbar-brand > a:before {
  position: absolute;
  bottom: 29px;
  right: 37px;
  content: url("../images/logo.png");
}

.rd-navbar-wrap .rd-navbar-brand > a span {
  display: none;
}

.rd-navbar-wrap, .rd-navbar, .rd-navbar-brand, .rd-navbar-slogan,
.rd-navbar-dropdown, .rd-navbar-megamenu, .rd-navbar-collapse-items,
.brand-name, .rd-navbar-nav, .rd-navbar-panel, .rd-navbar-search-form-input,
.rd-navbar-search-form-submit, .rd-navbar-search-toggle,
.rd-navbar-live-search-results, .rd-navbar-search-form {
  transition: .3s all ease;
}

.rd-navbar-collapse-toggle {
  display: inline-block;
  position: relative;
  width: 48px;
  height: 48px;
  line-height: 48px;
  cursor: pointer;
  color: white;
  display: none;
}

.rd-navbar-collapse-toggle span {
  top: 50%;
  margin-top: -3px;
}

.rd-navbar-collapse-toggle span, .rd-navbar-collapse-toggle span:before, .rd-navbar-collapse-toggle span:after {
  position: absolute;
  width: 6px;
  height: 6px;
  line-height: 6px;
  text-align: center;
  background: white;
  left: 50%;
  margin-left: -3px;
  border-radius: 50%;
  transition: .3s all ease;
}

.rd-navbar-collapse-toggle span:before, .rd-navbar-collapse-toggle span:after {
  content: '';
}

.rd-navbar-collapse-toggle span:before {
  bottom: 100%;
  margin-bottom: 3px;
}

.rd-navbar-collapse-toggle span:after {
  top: 100%;
  margin-top: 3px;
}

.rd-navbar-collapse-toggle.active span {
  -webkit-transform: scale(0.7);
  transform: scale(0.7);
}

.rd-navbar-collapse-toggle.active span:before {
  -webkit-transform: translateY(18px);
  transform: translateY(18px);
}

.rd-navbar-collapse-toggle.active span:after {
  -webkit-transform: translateY(-18px);
  transform: translateY(-18px);
}

.rd-navbar--has-sidebar body {
  padding-left: 270px;
}

.rd-navbar--is-stuck {
  box-shadow: none;
}

.rd-navbar.rd-navbar-fixed + .rd-navbar.rd-navbar--is-clone,
.rd-navbar.rd-navbar-sidebar + .rd-navbar.rd-navbar--is-clone {
  display: none;
}

.rd-navbar.rd-navbar--is-stuck.rd-navbar--loading {
  visibility: hidden;
  -webkit-transform: translateY(-100%);
  transform: translateY(-100%);
}

/*
* Navbar components
*/
.rd-navbar {
  display: none;
  background: transparent;
  box-shadow: none;
}

.rd-navbar-toggle {
  display: inline-block;
  position: relative;
  width: 48px;
  height: 48px;
  line-height: 48px;
  cursor: pointer;
  color: #fff;
  background-color: transparent;
  border: none;
  display: none;
}

.rd-navbar-toggle span {
  position: relative;
  display: block;
  margin: auto;
  transition: .3s all ease;
}

.rd-navbar-toggle span:after,
.rd-navbar-toggle span:before {
  content: "";
  position: absolute;
  left: 0;
  top: -8px;
  transition: .3s all ease;
}

.rd-navbar-toggle span:after {
  top: 8px;
}

.rd-navbar-toggle span:after,
.rd-navbar-toggle span:before,
.rd-navbar-toggle span {
  width: 24px;
  height: 4px;
  background-color: #fff;
  backface-visibility: hidden;
  border-radius: 2px;
}

.rd-navbar-toggle span {
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg);
}

.rd-navbar-toggle span:before,
.rd-navbar-toggle span:after {
  -webkit-transform-origin: 1.71429px center;
  -moz-transform-origin: 1.71429px center;
  -ms-transform-origin: 1.71429px center;
  transform-origin: 1.71429px center;
  -webkit-transform-origin: 1.71429px center;
  -moz-transform-origin: 1.71429px center;
  -ms-transform-origin: 1.71429px center;
  transform-origin: 1.71429px center;
}

.rd-navbar-toggle.active span {
  -webkit-transform: rotate(360deg);
  transform: rotate(360deg);
}

.rd-navbar-toggle.active span:before,
.rd-navbar-toggle.active span:after {
  top: 0;
  width: 15px;
}

.rd-navbar-toggle.active span:before {
  -webkit-transform: rotate3d(0, 0, 1, -40deg);
  transform: rotate3d(0, 0, 1, -40deg);
}

.rd-navbar-toggle.active span:after {
  -webkit-transform: rotate3d(0, 0, 1, 40deg);
  transform: rotate3d(0, 0, 1, 40deg);
}

.rd-navbar-toggle:focus {
  outline: none;
}

.rd-navbar-brand .brand-name {
  color: white;
  font-size: 25px;
  line-height: 40px;
  font-weight: 700;
}

.rd-navbar-dropdown {
  display: none;
}

.rd-navbar-search-toggle {
  display: inline-block;
  font: 400 18px/36px "FontAwesome";
}

.rd-navbar-search-toggle, .rd-navbar-search-toggle:before, .rd-navbar-search-toggle:after {
  text-align: center;
  width: 36px;
  height: 36px;
}

.rd-navbar-search-toggle:before, .rd-navbar-search-toggle:after {
  position: absolute;
  left: 0;
  top: 0;
}

.rd-navbar-search-toggle:before {
  content: '\f002';
  transition: .3s all ease;
  -webkit-transform: scale(1) rotate(0deg);
  transform: scale(1) rotate(0deg);
}

.rd-navbar:not(.rd-navbar-fixed) .rd-navbar-search-toggle:after {
  content: '\f00d';
  transition: .3s all ease;
  -webkit-transform: scale(0) rotate(-90deg);
  transform: scale(0) rotate(-90deg);
}

.rd-navbar:not(.rd-navbar-fixed) .rd-navbar-search-toggle.active:before {
  -webkit-transform: scale(0) rotate(90deg);
  transform: scale(0) rotate(90deg);
}

.rd-navbar:not(.rd-navbar-fixed) .rd-navbar-search-toggle.active:after {
  -webkit-transform: scale(1) rotate(0deg);
  transform: scale(1) rotate(0deg);
}

.rd-navbar-fixed .rd-navbar-search-toggle, .rd-navbar-fixed .rd-navbar-search-toggle:before {
  width: 48px;
  line-height: 48px;
}

.rd-navbar-search-form-submit {
  display: inline-block;
  position: relative;
  width: 48px;
  height: 48px;
  line-height: 48px;
  cursor: pointer;
  color: white;
  text-align: center;
  font-size: 24px;
}

.rd-navbar-search-form-submit:before {
  content: "\f002";
  font-weight: 400;
  font-family: "FontAwesome";
}

.rd-navbar-search-form-submit.active {
  -webkit-transform: scale(0.7);
  transform: scale(0.7);
}

.rd-navbar-live-search-results {
  position: absolute;
  left: 4px;
  right: 4px;
  padding: 16px 8px 8px;
  top: 100%;
  font-size: 16px;
  line-height: 34px;
  color: #333;
  background: #FFF;
  box-shadow: none;
  opacity: 0;
  visibility: hidden;
  text-align: left;
  z-index: 998;
}

.rd-navbar-live-search-results .search-quick-result {
  padding-left: 8px;
  font-size: 14px;
  line-height: 30px;
  color: #757575;
}

.rd-navbar-live-search-results .search_list {
  margin-top: 4px;
  font-size: 16px;
  line-height: 30px;
}

.rd-navbar-live-search-results .search_list li + li {
  margin-top: 2px;
}

.rd-navbar-live-search-results .search_list .search_list li + li:last-child {
  margin-top: 8px;
  border-top: 1px solid #EBEBEB;
  padding-top: 7px;
}

.rd-navbar-live-search-results .search_link {
  display: block;
  padding: 8px;
  color: #757575;
  border-radius: 2px;
}

.rd-navbar-live-search-results .search_link:hover {
  background: #F7F7F7;
}

.rd-navbar-live-search-results .search_link p {
  margin-top: 0;
  font-size: 14px;
  display: none;
}

.rd-navbar-live-search-results .search_title {
  color: #212121;
  font-weight: 400;
}

.rd-navbar-live-search-results .search_submit {
  display: block;
  text-align: center;
  padding: 8px;
  font-weight: 700;
  color: #e89e00;
  text-transform: uppercase;
  -webkit-border-radius: 2px;
  -moz-border-radius: 2px;
  border-radius: 2px;
}

.rd-navbar-live-search-results .search_submit:hover {
  background: #F7F7F7;
}

.rd-navbar-live-search-results.active {
  visibility: visible;
  opacity: 1;
}

@media (min-width: 1200px) {
  .rd-navbar-live-search-results .search_link p {
    display: block;
  }
}

.rd-navbar-live-search-results {
  -webkit-transform: translateY(-100%);
  transform: translateY(-100%);
}

.rd-navbar-live-search-results.active {
  -webkit-transform: translateY(0);
  transform: translateY(0);
}

.rd-navbar-shop {
  display: inline-block;
  font-size: 22px;
  color: #fff;
  position: absolute;
  right: 12px;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
  top: 50%;
  z-index: 9;
  transition: .3s;
}

.rd-navbar-shop:hover {
  color: #e89e00;
}

.rd-navbar-shop:focus {
  outline: 0;
  color: #e89e00;
}

/*
* @subsection   Hybrid  Styles
*/
.rd-navbar-static .rd-navbar-search-form-input input, .rd-navbar-sidebar .rd-navbar-search-form-input input, .rd-navbar-fullwidth .rd-navbar-search-form-input input {
  width: 100%;
  padding: 7px 40px 7px 18px;
  height: 48px;
  font-size: 16px;
  line-height: 34px;
  color: white;
}

.rd-navbar-static:after, .rd-navbar-fullwidth:after {
  content: '';
  background: transparent;
}

.rd-navbar-static .rd-navbar-brand, .rd-navbar-static .rd-navbar-nav > li > a, .rd-navbar-static .rd-navbar-search-toggle, .rd-navbar-fullwidth .rd-navbar-brand, .rd-navbar-fullwidth .rd-navbar-nav > li > a, .rd-navbar-fullwidth .rd-navbar-search-toggle {
  position: relative;
  z-index: 2;
}

.rd-navbar-static .rd-navbar-nav > li > a, .rd-navbar-fullwidth .rd-navbar-nav > li > a {
  position: relative;
  display: block;
  padding: 10px 0px;
  color: #fff;
  font-weight: 900;
  font-size: 13px;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  line-height: 1.2;
}

.rd-navbar-static .rd-navbar-nav > li > a:after, .rd-navbar-fullwidth .rd-navbar-nav > li > a:after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 50%;
  width: 0;
  height: 3px;
  transition: .4s;
}

.rd-navbar-static .rd-navbar-nav > li.focus > a:after, .rd-navbar-static .rd-navbar-nav > li > a:hover:after, .rd-navbar-static .rd-navbar-nav > li.active > a:after, .rd-navbar-fullwidth .rd-navbar-nav > li.focus > a:after, .rd-navbar-fullwidth .rd-navbar-nav > li > a:hover:after, .rd-navbar-fullwidth .rd-navbar-nav > li.active > a:after {
  left: 0;
  width: 100%;
}

.rd-navbar-static .rd-navbar-nav > .rd-navbar-submenu > ul, .rd-navbar-fullwidth .rd-navbar-nav > .rd-navbar-submenu > ul {
  box-shadow: none;
}

.rd-navbar-static .rd-navbar-nav > .rd-navbar-submenu li, .rd-navbar-fullwidth .rd-navbar-nav > .rd-navbar-submenu li {
  font-size: 14px;
  line-height: 30px;
}

.rd-navbar-static .rd-navbar-nav > .rd-navbar-submenu > .rd-navbar-dropdown, .rd-navbar-static .rd-navbar-nav > .rd-navbar-submenu > .rd-navbar-megamenu, .rd-navbar-fullwidth .rd-navbar-nav > .rd-navbar-submenu > .rd-navbar-dropdown, .rd-navbar-fullwidth .rd-navbar-nav > .rd-navbar-submenu > .rd-navbar-megamenu {
  opacity: 0;
  visibility: hidden;
  -webkit-transform: translateY(30px);
  transform: translateY(30px);
}

.rd-navbar-static .rd-navbar-nav > .rd-navbar-submenu.focus > .rd-navbar-dropdown, .rd-navbar-static .rd-navbar-nav > .rd-navbar-submenu.focus > .rd-navbar-megamenu, .rd-navbar-fullwidth .rd-navbar-nav > .rd-navbar-submenu.focus > .rd-navbar-dropdown, .rd-navbar-fullwidth .rd-navbar-nav > .rd-navbar-submenu.focus > .rd-navbar-megamenu {
  opacity: 1;
  visibility: visible;
  -webkit-transform: translateY(0);
  transform: translateY(0);
}

.rd-navbar-static .rd-navbar-nav > .rd-navbar-submenu .rd-navbar-submenu.focus > .rd-navbar-dropdown, .rd-navbar-fullwidth .rd-navbar-nav > .rd-navbar-submenu .rd-navbar-submenu.focus > .rd-navbar-dropdown {
  display: block;
}

.rd-navbar-static .rd-navbar-inner, .rd-navbar-fullwidth .rd-navbar-inner {
  position: relative;
  max-width: 1200px;
  margin-left: auto;
  margin-right: auto;
  padding: 60px 15px 30px;
}

.rd-navbar-static .rd-navbar-nav > li > .rd-navbar-dropdown, .rd-navbar-fullwidth .rd-navbar-nav > li > .rd-navbar-dropdown {
  display: block;
  position: absolute;
  text-align: left;
  margin-top: 10px;
  left: 50%;
  margin-left: -135px;
  width: 270px;
  background: #7e7e7e;
  z-index: 5;
}

.rd-navbar-static .rd-navbar-dropdown, .rd-navbar-fullwidth .rd-navbar-dropdown {
  background: #7e7e7e;
  padding: 10px 0;
}

.rd-navbar-static .rd-navbar-dropdown .rd-navbar-dropdown > li > a, .rd-navbar-fullwidth .rd-navbar-dropdown .rd-navbar-dropdown > li > a {
  color: #fff;
}

.rd-navbar-static .rd-navbar-dropdown > li > a, .rd-navbar-fullwidth .rd-navbar-dropdown > li > a {
  display: block;
  padding: 2px 20px;
  color: #fff;
  text-transform: uppercase;
  background: transparent;
}

.rd-navbar-static .rd-navbar-dropdown > li > a:hover, .rd-navbar-fullwidth .rd-navbar-dropdown > li > a:hover {
  color: #e89e00;
  background: transparent;
}

.rd-navbar-static .rd-navbar-dropdown > li.focus > a, .rd-navbar-fullwidth .rd-navbar-dropdown > li.focus > a {
  color: #e89e00;
  background: transparent;
}

.rd-navbar-static .rd-navbar-megamenu, .rd-navbar-fullwidth .rd-navbar-megamenu {
  display: table;
  position: absolute;
  text-align: left;
  right: 15px;
  border-spacing: 31px 25px;
  table-layout: fixed;
  width: 55%;
  margin-top: 10px;
  max-width: 1200px;
  background: #7e7e7e;
  z-index: 4;
}

.rd-navbar-static .rd-navbar-megamenu > li, .rd-navbar-fullwidth .rd-navbar-megamenu > li {
  position: relative;
  display: table-cell;
}

.rd-navbar-static .rd-navbar-megamenu > li > p, .rd-navbar-fullwidth .rd-navbar-megamenu > li > p {
  font-weight: 400;
  text-transform: uppercase;
  color: #fff;
}

.rd-navbar-static .rd-navbar-megamenu > li > ul, .rd-navbar-fullwidth .rd-navbar-megamenu > li > ul {
  padding: 8px 9px;
}

.rd-navbar-static .rd-navbar-megamenu > li > ul li + li, .rd-navbar-fullwidth .rd-navbar-megamenu > li > ul li + li {
  margin-top: 5px;
}

.rd-navbar-static .rd-navbar-megamenu > li > ul a, .rd-navbar-fullwidth .rd-navbar-megamenu > li > ul a {
  display: inline-block;
  color: #fff;
  background: transparent;
}

.rd-navbar-static .rd-navbar-megamenu > li > ul a:hover, .rd-navbar-fullwidth .rd-navbar-megamenu > li > ul a:hover {
  color: #e89e00;
  background: transparent;
}

.rd-navbar-static .rd-navbar-megamenu > li + li, .rd-navbar-fullwidth .rd-navbar-megamenu > li + li {
  padding-left: 10px;
}

.rd-navbar-static .rd-navbar-megamenu > li + li:before, .rd-navbar-fullwidth .rd-navbar-megamenu > li + li:before {
  content: '';
  position: absolute;
  top: 30px;
  bottom: 30px;
  width: 1px;
  right: 100%;
  margin-right: 17px;
  background: #919191;
}

.rd-navbar-static.rd-navbar--is-clone, .rd-navbar-fullwidth.rd-navbar--is-clone {
  display: none;
  -webkit-transform: translateY(-110%);
  transform: translateY(-110%);
}

.rd-navbar-static.rd-navbar--is-clone.rd-navbar--is-stuck, .rd-navbar-fullwidth.rd-navbar--is-clone.rd-navbar--is-stuck {
  -webkit-transform: translateY(0);
  transform: translateY(0);
}

.rd-navbar-static .rd-navbar-search-form .form-group, .rd-navbar-fullwidth .rd-navbar-search-form .form-group {
  margin-bottom: 0;
}

.rd-navbar-static .rd-navbar-search-form:after, .rd-navbar-fullwidth .rd-navbar-search-form:after {
  left: 100%;
}

.rd-navbar-static .rd-navbar-search-form-submit, .rd-navbar-fullwidth .rd-navbar-search-form-submit {
  background-color: transparent;
  right: 27px;
  width: auto;
  height: auto;
  line-height: inherit;
  font-size: 16px;
  border: none;
}

.rd-navbar-static .rd-navbar-search-form-submit:focus, .rd-navbar-fullwidth .rd-navbar-search-form-submit:focus {
  outline: none;
}

.rd-navbar-static .rd-navbar-search-form-input, .rd-navbar-fullwidth .rd-navbar-search-form-input {
  position: relative;
  display: inline-block;
  padding-right: 24px;
  padding-left: 10px;
}

.rd-navbar-static .rd-navbar-search-toggle, .rd-navbar-fullwidth .rd-navbar-search-toggle {
  position: absolute;
  right: 50px;
  top: 50%;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
  color: #fff;
  background-color: transparent;
  border: none;
}

.rd-navbar-static .rd-navbar-search-toggle:focus, .rd-navbar-fullwidth .rd-navbar-search-toggle:focus {
  outline: 0;
}

.rd-navbar-static .rd-navbar-search-toggle:hover, .rd-navbar-fullwidth .rd-navbar-search-toggle:hover {
  color: #e89e00;
}

.rd-navbar-static .rd-navbar-search.active .rd-navbar-search-form, .rd-navbar-fullwidth .rd-navbar-search.active .rd-navbar-search-form {
  visibility: visible;
  -webkit-transform: rotateX(0deg);
  transform: rotateX(0deg);
}

.rd-navbar-static .rd-navbar-live-search-results, .rd-navbar-fullwidth .rd-navbar-live-search-results {
  top: calc(100% + 56px);
  z-index: 0;
}

.rd-navbar-static.rd-navbar--is-stuck,
.rd-navbar-static.rd-navbar--is-clone, .rd-navbar-fullwidth.rd-navbar--is-stuck,
.rd-navbar-fullwidth.rd-navbar--is-clone {
  display: none;
  position: fixed;
  left: 0;
  top: 0;
  right: 0;
  z-index: 999;
  background: #fff;
}

.rd-navbar-static.rd-navbar--is-stuck .rd-navbar-panel,
.rd-navbar-static.rd-navbar--is-clone .rd-navbar-panel, .rd-navbar-fullwidth.rd-navbar--is-stuck .rd-navbar-panel,
.rd-navbar-fullwidth.rd-navbar--is-clone .rd-navbar-panel {
  padding: 8px 0;
}

.rd-navbar-static.rd-navbar--is-stuck .rd-navbar-collapse,
.rd-navbar-static.rd-navbar--is-clone .rd-navbar-collapse, .rd-navbar-fullwidth.rd-navbar--is-stuck .rd-navbar-collapse,
.rd-navbar-fullwidth.rd-navbar--is-clone .rd-navbar-collapse {
  display: none;
}

.rd-navbar-static .rd-navbar-dropdown,
.rd-navbar-static .rd-navbar-megamenu, .rd-navbar-fullwidth .rd-navbar-dropdown,
.rd-navbar-fullwidth .rd-navbar-megamenu {
  position: absolute;
  -webkit-transform: translateY(30px);
  transform: translateY(30px);
  padding: 8px 0;
  text-align: left;
  visibility: hidden;
  opacity: 0;
  background: white;
}

.rd-navbar-static .rd-navbar-dropdown li > a,
.rd-navbar-static .rd-navbar-megamenu li > a, .rd-navbar-fullwidth .rd-navbar-dropdown li > a,
.rd-navbar-fullwidth .rd-navbar-megamenu li > a {
  display: block;
  font-size: 14px;
  line-height: 24px;
  padding: 6px 16px;
}

.rd-navbar-static .rd-navbar-dropdown, .rd-navbar-fullwidth .rd-navbar-dropdown {
  width: 270px;
}

.rd-navbar-static .rd-navbar-megamenu, .rd-navbar-fullwidth .rd-navbar-megamenu {
  margin-top: 10px;
  left: 0;
  right: 0;
  display: table;
  table-layout: fixed;
  width: 100%;
  padding: 16px 8px;
  background: white;
}

.rd-navbar-static .rd-navbar-megamenu > li, .rd-navbar-fullwidth .rd-navbar-megamenu > li {
  display: table-cell;
}

.rd-navbar-static .rd-navbar-nav, .rd-navbar-fullwidth .rd-navbar-nav {
  display: block;
  text-align: right;
}

.rd-navbar-static .rd-navbar-nav li.rd-navbar--has-dropdown, .rd-navbar-fullwidth .rd-navbar-nav li.rd-navbar--has-dropdown {
  position: relative;
}

.rd-navbar-static .rd-navbar-nav li.focus > .rd-navbar-dropdown,
.rd-navbar-static .rd-navbar-nav li.focus > .rd-navbar-megamenu,
.rd-navbar-static .rd-navbar-nav li.opened > .rd-navbar-dropdown, .rd-navbar-static .rd-navbar-nav li.opened > .rd-navbar-megamenu, .rd-navbar-fullwidth .rd-navbar-nav li.focus > .rd-navbar-dropdown,
.rd-navbar-fullwidth .rd-navbar-nav li.focus > .rd-navbar-megamenu,
.rd-navbar-fullwidth .rd-navbar-nav li.opened > .rd-navbar-dropdown, .rd-navbar-fullwidth .rd-navbar-nav li.opened > .rd-navbar-megamenu {
  opacity: 1;
  visibility: visible;
  -webkit-transform: translateY(0);
  transform: translateY(0);
}

.rd-navbar-static .rd-navbar-nav > li, .rd-navbar-fullwidth .rd-navbar-nav > li {
  display: inline-block;
}

.rd-navbar-static .rd-navbar-nav > li > .rd-navbar-dropdown, .rd-navbar-static .rd-navbar-nav > li > .rd-navbar-megamenu, .rd-navbar-fullwidth .rd-navbar-nav > li > .rd-navbar-dropdown, .rd-navbar-fullwidth .rd-navbar-nav > li > .rd-navbar-megamenu {
  top: 100%;
  z-index: 1;
}

.rd-navbar-static .rd-navbar-nav > li > .rd-navbar-dropdown, .rd-navbar-fullwidth .rd-navbar-nav > li > .rd-navbar-dropdown {
  left: 50%;
  margin-top: 10px;
  margin-left: -135px;
}

.rd-navbar-static .rd-navbar-nav > li > .rd-navbar-dropdown .rd-navbar-dropdown, .rd-navbar-fullwidth .rd-navbar-nav > li > .rd-navbar-dropdown .rd-navbar-dropdown {
  left: 100%;
  top: -8px;
  z-index: 2;
}

.rd-navbar-static .rd-navbar-nav > li > a, .rd-navbar-fullwidth .rd-navbar-nav > li > a {
  display: block;
  font-weight: 500;
  font-size: 18px;
  line-height: 26px;
  color: white;
}

.rd-navbar-static .rd-navbar-nav > li.active > a, .rd-navbar-static .rd-navbar-nav > li.opened > a, .rd-navbar-static .rd-navbar-nav > li.focus > a, .rd-navbar-static .rd-navbar-nav > li > a:hover, .rd-navbar-fullwidth .rd-navbar-nav > li.active > a, .rd-navbar-fullwidth .rd-navbar-nav > li.opened > a, .rd-navbar-fullwidth .rd-navbar-nav > li.focus > a, .rd-navbar-fullwidth .rd-navbar-nav > li > a:hover {
  color: #e89e00;
}

.rd-navbar-static .rd-navbar--has-dropdown, .rd-navbar-fullwidth .rd-navbar--has-dropdown {
  position: relative;
}

.rd-navbar-static.rd-navbar--is-clone, .rd-navbar-fullwidth.rd-navbar--is-clone {
  display: block;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  background-color: #fff;
  box-shadow: 0 0 24px -1px rgba(0, 0, 0, 0.2);
}

.rd-navbar-static.rd-navbar--is-clone .rd-navbar-nav > li > a,
.rd-navbar-static.rd-navbar--is-clone .rd-navbar-search-toggle,
.rd-navbar-static.rd-navbar--is-clone .rd-navbar-shop, .rd-navbar-fullwidth.rd-navbar--is-clone .rd-navbar-nav > li > a,
.rd-navbar-fullwidth.rd-navbar--is-clone .rd-navbar-search-toggle,
.rd-navbar-fullwidth.rd-navbar--is-clone .rd-navbar-shop {
  color: #7e7e7e;
}

.rd-navbar-fixed .rd-navbar-collapse-toggle, .rd-navbar-sidebar .rd-navbar-collapse-toggle {
  display: inline-block;
  z-index: 1;
}

.rd-navbar-fixed .rd-navbar-dropdown, .rd-navbar-sidebar .rd-navbar-dropdown {
  display: block;
}

.rd-navbar-fixed .rd-navbar-collapse-items, .rd-navbar-sidebar .rd-navbar-collapse-items {
  position: absolute;
  width: 260px;
  padding: 25px 15px;
  box-shadow: none;
  color: white;
  background: transparent;
  font-size: 16px;
  line-height: 34px;
}

.rd-navbar-fixed .rd-navbar-collapse-items li > *, .rd-navbar-sidebar .rd-navbar-collapse-items li > * {
  vertical-align: middle;
}

.rd-navbar-fixed .rd-navbar-collapse-items li + li, .rd-navbar-sidebar .rd-navbar-collapse-items li + li {
  margin-top: 10px;
}

.rd-navbar-fixed .rd-navbar-collapse-items .icon, .rd-navbar-fixed .rd-navbar-collapse-items a, .rd-navbar-sidebar .rd-navbar-collapse-items .icon, .rd-navbar-sidebar .rd-navbar-collapse-items a {
  display: inline-block;
  font-size: 16px;
  line-height: 30px;
}

.rd-navbar-fixed .rd-navbar-collapse-items .icon, .rd-navbar-fixed .rd-navbar-collapse-items a[class*="fa"]:before, .rd-navbar-sidebar .rd-navbar-collapse-items .icon, .rd-navbar-sidebar .rd-navbar-collapse-items a[class*="fa"]:before {
  display: inline-block;
  width: 30px;
  height: 30px;
  padding-right: 5px;
}

.rd-navbar-fixed .rd-navbar-nav,
.rd-navbar-sidebar {
  position: fixed;
  width: 270px;
  height: 100%;
  left: 0;
  top: 0;
  overflow-y: auto;
  overflow-x: hidden;
  -webkit-overflow-scrolling: touch;
  font-size: 16px;
  line-height: 34px;
  color: white;
  background: #1F1F1F;
  box-shadow: 0 0 11px 2px rgba(0, 0, 0, 0.17);
  z-index: 998;
  padding: 120px 0;
}

.rd-navbar-fixed .rd-navbar-nav:before,
.rd-navbar-fixed .rd-navbar-nav:after,
.rd-navbar-sidebar:before, .rd-navbar-sidebar:after {
  content: '';
  display: block;
  height: 56px;
}

.rd-navbar-fixed .rd-navbar-nav::-webkit-scrollbar,
.rd-navbar-sidebar::-webkit-scrollbar {
  width: 4px;
}

.rd-navbar-fixed .rd-navbar-nav::-webkit-scrollbar-thumb,
.rd-navbar-sidebar::-webkit-scrollbar-thumb {
  background: rgba(26, 26, 26, 0);
  border: none;
  border-radius: 0;
  opacity: .2;
}

.rd-navbar-fixed .rd-navbar-nav::-webkit-scrollbar-track,
.rd-navbar-sidebar::-webkit-scrollbar-track {
  background: transparent;
  border: none;
  border-radius: 0;
}

.rd-navbar-fixed .rd-navbar-nav p,
.rd-navbar-sidebar .rd-navbar-nav p {
  font-weight: 700;
  color: #7e7e7e;
  padding: 5px 40px 5px 15px;
}

.rd-navbar-fixed .rd-navbar-nav p > a,
.rd-navbar-sidebar .rd-navbar-nav p > a {
  display: block;
  color: white;
  margin: -5px -40px -5px -15px;
  font-weight: 400;
  padding: 5px 40px 5px 15px;
}

.rd-navbar-fixed .rd-navbar-nav p > a:hover,
.rd-navbar-sidebar .rd-navbar-nav p > a:hover {
  color: #FFF;
  background: #e89e00;
  text-decoration: none;
}

.rd-navbar-fixed .rd-navbar-nav li,
.rd-navbar-sidebar .rd-navbar-nav li {
  position: relative;
}

.rd-navbar-fixed .rd-navbar-nav li li > a,
.rd-navbar-sidebar .rd-navbar-nav li li > a {
  padding-left: 20px;
}

.rd-navbar-fixed .rd-navbar-nav li > a,
.rd-navbar-sidebar .rd-navbar-nav li > a {
  position: relative;
  display: block;
  padding: 5px 45px 5px 15px;
}

.rd-navbar-fixed .rd-navbar-nav li > a:first-letter,
.rd-navbar-sidebar .rd-navbar-nav li > a:first-letter {
  text-transform: uppercase;
}

.rd-navbar-fixed .rd-navbar-nav li.active > a,
.rd-navbar-sidebar .rd-navbar-nav li.active > a {
  color: white;
  background: transparent;
}

.rd-navbar-fixed .rd-navbar-nav li.focus > a,
.rd-navbar-fixed .rd-navbar-nav li > a:hover,
.rd-navbar-sidebar .rd-navbar-nav li.focus > a, .rd-navbar-sidebar .rd-navbar-nav li > a:hover {
  color: #FFF;
  background: #e89e00;
}

.rd-navbar-fixed .rd-navbar-nav li + li,
.rd-navbar-fixed .rd-navbar-nav li > img + a,
.rd-navbar-fixed .rd-navbar-nav li > a + a,
.rd-navbar-fixed .rd-navbar-nav li > a + ul,
.rd-navbar-sidebar .rd-navbar-nav li + li, .rd-navbar-sidebar .rd-navbar-nav li > img + a, .rd-navbar-sidebar .rd-navbar-nav li > a + a, .rd-navbar-sidebar .rd-navbar-nav li > a + ul {
  margin-top: 4px;
}

.rd-navbar-fixed .rd-navbar-nav .rd-navbar-dropdown > li > a,
.rd-navbar-sidebar .rd-navbar-nav .rd-navbar-dropdown > li > a {
  padding-left: 20px;
}

.rd-navbar-fixed .rd-navbar-nav .rd-navbar-dropdown ul > li > a,
.rd-navbar-sidebar .rd-navbar-nav .rd-navbar-dropdown ul > li > a {
  padding-left: 25px;
}

.rd-navbar-fixed .rd-navbar-search-form-submit, .rd-navbar-sidebar .rd-navbar-search-form-submit {
  -webkit-transform: scale(0.7);
  transform: scale(0.7);
}

/*
* Static Layout
*/
.rd-navbar-static {
  display: block;
}

.rd-navbar-static .contact-info {
  float: right;
  display: none;
  font-family: "Cinzel", serif;
  letter-spacing: 0.9px;
  padding-top: 10px;
}

@media (min-width: 992px) {
  .rd-navbar-static .contact-info {
    display: inline-block;
  }
}

.rd-navbar-static .contact-info p {
  display: inline-block;
  text-transform: uppercase;
}

.rd-navbar-static .contact-info a {
  padding-left: 5px;
  color: #ffb822;
  font-weight: 700;
  transition: .3s;
}

.rd-navbar-static .contact-info a:hover {
  color: #fff;
  text-shadow: 0 0 5px #fff;
}

.rd-navbar-static .rd-navbar-collapse {
  display: block;
  float: right;
  margin-left: -15px;
  margin-top: 23px;
}

.rd-navbar-static .rd-navbar-collapse li {
  display: inline-block;
  margin-left: 15px;
}

.rd-navbar-static .rd-navbar-collapse li a:hover {
  text-decoration: underline;
}

.rd-navbar-static .rd-navbar-panel, .rd-navbar-static .rd-navbar-nav-wrap {
  display: inline-block;
}

.rd-navbar-static .rd-navbar-panel {
  text-align: left;
  vertical-align: middle;
}

.rd-navbar-static .rd-navbar-panel:before,
.rd-navbar-static .rd-navbar-panel:after {
  content: " ";
  display: table;
}

.rd-navbar-static .rd-navbar-panel:after {
  clear: both;
}

.rd-navbar-static .rd-navbar-panel-canvas {
  position: fixed;
  height: 56px;
  left: 0;
  top: 0;
  width: 100%;
  background: #fff;
  z-index: 16;
}

.rd-navbar-static .rd-navbar-toggle {
  position: fixed;
  z-index: 17;
  top: 4px;
  left: 4px;
}

.rd-navbar-static .rd-navbar-nav-wrap {
  width: 100%;
  text-align: right;
}

.rd-navbar-static .rd-navbar-nav {
  margin-bottom: 0;
}

.rd-navbar-static .rd-navbar-nav > li {
  display: inline-block;
}

.rd-navbar-static .rd-navbar-nav > li + li {
  margin-left: 36px;
}

.rd-navbar-static .rd-navbar-static--visible {
  display: block;
}

.rd-navbar-static .rd-navbar-static--hidden {
  display: none;
}

/*
* Fullwidth Layout
*/
.rd-navbar-fullwidth {
  display: block;
}

.rd-navbar-fullwidth .rd-navbar-panel {
  text-align: center;
  padding: 24px 0;
}

.rd-navbar-fullwidth .rd-navbar-nav-wrap {
  padding-right: 40px;
  position: relative;
  padding-bottom: 5px;
}

.rd-navbar-fullwidth .rd-navbar-nav-wrap .rd-navbar-megamenu {
  left: 0;
  right: 0;
}

.rd-navbar-fullwidth .rd-navbar-search-toggle {
  right: 6%;
}

.rd-navbar-fullwidth .rd-navbar-nav {
  width: 100%;
  display: table;
}

.rd-navbar-fullwidth .rd-navbar-nav > li {
  display: table-cell;
}

.rd-navbar-fullwidth .rd-navbar-nav > li > a {
  display: block;
  text-align: center;
  padding: 10px;
}

.rd-navbar-fullwidth.rd-navbar--is-stuck {
  -webkit-transform: translateY(-120px);
  transform: translateY(-120px);
}

.rd-navbar-fullwidth.rd-navbar--is-stuck .rd-navbar-panel {
  display: none;
}

.rd-navbar-fullwidth .rd-navbar-fullwidth--visible {
  display: block;
}

.rd-navbar-fullwidth .rd-navbar-fullwidth--hidden {
  display: none;
}

/*
* Fixed Layout
*/
.rd-navbar-fixed {
  display: block;
}

.rd-navbar-fixed .rd-navbar-brand {
  position: relative;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  width: calc(100% - 104px);
}

.rd-navbar-fixed .rd-navbar-brand .brand-name {
  display: inline-block;
  font-size: 39px;
  line-height: 48px;
  color: #fff;
}

.rd-navbar-fixed .rd-navbar-brand .brand-name:before {
  display: none;
}

.rd-navbar-fixed .rd-navbar-brand .brand-slogan {
  display: none;
}

.rd-navbar-fixed .rd-navbar-brand {
  display: block;
  text-align: left;
  position: fixed;
  top: 4px;
  left: 56px;
  right: 112px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  font-size: 22px;
  line-height: 46px;
  height: 48px;
  z-index: 17;
}

.rd-navbar-fixed .rd-navbar-brand img {
  display: none;
}

.rd-navbar-fixed .rd-navbar-brand a {
  display: inline-block;
}

.rd-navbar-fixed .rd-navbar-panel {
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  position: fixed;
  left: 0;
  top: 0;
  right: 0;
  padding: 4px;
  height: 56px;
  color: white;
  z-index: 999;
}

.rd-navbar-fixed .rd-navbar-panel:before {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  right: 0;
  box-shadow: 0 0 13px -1px rgba(0, 0, 0, 0.17);
  background: #e89e00;
}

.rd-navbar-fixed .rd-navbar-toggle {
  display: inline-block;
}

.rd-navbar-fixed .rd-navbar-nav-wrap {
  position: fixed;
  top: -56px;
  left: 0;
  width: 232px;
  padding: 112px 0 56px;
  bottom: -56px;
  color: #fff;
  background: transparent;
  z-index: 15;
  -webkit-transform: translateX(-120%);
  transform: translateX(-120%);
}

.rd-navbar-fixed .rd-navbar-nav-wrap.active {
  -webkit-transform: translateX(0);
  transform: translateX(0);
}

.rd-navbar-fixed .rd-navbar-nav {
  display: block;
  height: 100%;
  overflow: auto;
  font-size: 16px;
  line-height: 26px;
  text-align: left;
}

.rd-navbar-fixed .rd-navbar-nav:before, .rd-navbar-fixed .rd-navbar-nav:after {
  content: '';
  display: block;
  height: 8px;
}

.rd-navbar-fixed .rd-navbar-nav li > a {
  display: block;
  padding: 11px 56px 11px 16px;
  color: #fff;
}

.rd-navbar-fixed .rd-navbar-nav li.opened > a, .rd-navbar-fixed .rd-navbar-nav li a:hover {
  background: white;
}

.rd-navbar-fixed .rd-navbar-nav li.active .rd-navbar-submenu-toggle:after {
  color: #fff;
}

.rd-navbar-fixed .rd-navbar-nav li.active > a {
  color: #fff;
  background: #e89e00;
}

.rd-navbar-fixed .rd-navbar-dropdown,
.rd-navbar-fixed .rd-navbar-megamenu {
  display: none;
}

.rd-navbar-fixed .rd-navbar-submenu {
  position: relative;
}

.rd-navbar-fixed .rd-navbar-submenu li > a {
  padding-left: 32px;
}

.rd-navbar-fixed .rd-navbar-submenu .rd-navbar-dropdown li li > a,
.rd-navbar-fixed .rd-navbar-submenu .rd-navbar-megamenu ul li li > a {
  padding-left: 48px;
}

.rd-navbar-fixed .rd-navbar-submenu.opened > .rd-navbar-dropdown,
.rd-navbar-fixed .rd-navbar-submenu.opened > .rd-navbar-megamenu {
  display: block;
}

.rd-navbar-fixed .rd-navbar-search {
  display: block;
}

.rd-navbar-fixed .rd-navbar-search form button[type="submit"] {
  display: none;
}

.rd-navbar-fixed .rd-navbar-search.active .form-group {
  opacity: 1;
  visibility: visible;
}

.rd-navbar-fixed .rd-navbar-search-form, .rd-navbar-fixed .rd-navbar-search-toggle {
  right: 4px;
}

.rd-navbar-fixed .rd-navbar-search-toggle {
  display: block;
  position: fixed;
  top: 4px;
  right: 56px;
  font-family: 'Material Icons';
  width: 48px;
  height: 48px;
  z-index: 18;
  color: white;
}

.rd-navbar-fixed .rd-navbar-search .form-group {
  position: fixed;
  top: 0;
  padding-top: 4px;
  left: 56px;
  right: 112px;
  height: 56px;
  background: transparent;
  z-index: 17;
  visibility: hidden;
  opacity: 0;
}

.rd-navbar-fixed .rd-navbar-search .form-group input {
  width: 100%;
  height: 46px;
  display: block;
  font-size: 22px;
  line-height: 46px;
}

.rd-navbar-fixed .rd-navbar-search-form, .rd-navbar-fixed .rd-navbar-search .rd-navbar-live-search-results {
  position: fixed;
  margin-right: 0;
  margin-left: auto;
}

.rd-navbar-fixed .rd-navbar-search .rd-navbar-live-search-results {
  top: 56px;
}

.rd-navbar-fixed .rd-navbar-search-form {
  top: 0;
  z-index: 1000;
  left: 50px;
  right: 0;
  height: 56px;
}

.rd-navbar-fixed .rd-navbar-search-form label {
  display: none;
}

.rd-navbar-fixed .rd-navbar-search-form-input {
  padding: 8px 40px 8px 10px;
  visibility: hidden;
  opacity: 0;
  height: 40px;
  border: 1px solid #C3C3C3;
  position: relative;
  top: 8px;
  background: #EAEAEA;
  transition: .3s all ease;
  z-index: 1;
  width: 100%;
}

.rd-navbar-fixed .rd-navbar-search-form-input input {
  display: block;
  width: 100%;
  padding: 0 48px 0 20px;
  height: 40px;
  font-size: 16px;
  line-height: 34px;
  color: white;
  background: silver;
}

.rd-navbar-fixed .rd-navbar-search-form-submit {
  position: absolute;
  top: 4px;
  right: 4px;
  opacity: 0;
  visibility: hidden;
  z-index: 9;
  background-color: transparent;
  border: none;
}

.rd-navbar-fixed .rd-navbar-search-form-submit:focus {
  outline: none;
}

.rd-navbar-fixed .rd-navbar-search-toggle.active {
  opacity: 0;
  visibility: hidden;
}

.rd-navbar-fixed .rd-navbar-search.active .rd-navbar-search-form-input,
.rd-navbar-fixed .rd-navbar-search.active .rd-navbar-search-form-submit {
  opacity: 1;
  visibility: visible;
}

@media (min-width: 992px) {
  .rd-navbar-fixed .rd-navbar-search-form, .rd-navbar-fixed .rd-navbar-search .rd-navbar-live-search-results {
    max-width: 340px;
  }
  .rd-navbar-fixed .rd-navbar-search .rd-navbar-live-search-results {
    right: 4px;
  }
}

@media (min-width: 480px) {
  .rd-navbar-fixed .rd-navbar-search .rd-navbar-brand .brand-name {
    font-size: 24px;
  }
}

.rd-navbar-fixed .rd-navbar-nav li:hover > a,
.rd-navbar-fixed .rd-navbar-nav li:hover > a:hover,
.rd-navbar-fixed .rd-navbar-nav li.focus > a, .rd-navbar-fixed .rd-navbar-nav li.focus > a:hover {
  color: #FFF;
  background: #e89e00;
}

.rd-navbar-fixed .rd-navbar-nav li:hover > .rd-navbar-submenu-toggle,
.rd-navbar-fixed .rd-navbar-nav li.focus > .rd-navbar-submenu-toggle {
  color: #fff;
}

.rd-navbar-fixed .rd-navbar-nav li:hover > .rd-navbar-submenu-toggle:hover,
.rd-navbar-fixed .rd-navbar-nav li.focus > .rd-navbar-submenu-toggle:hover {
  cursor: pointer;
  color: #fff;
}

.rd-navbar-fixed .rd-navbar-nav li .rd-navbar-dropdown,
.rd-navbar-fixed .rd-navbar-nav li .rd-navbar-megamenu {
  transition: opacity 0.3s, height 0.4s ease;
  opacity: 0;
  height: 0;
  overflow: hidden;
}

.rd-navbar-fixed .rd-navbar-nav li.opened > .rd-navbar-dropdown,
.rd-navbar-fixed .rd-navbar-nav li.opened > .rd-navbar-megamenu {
  opacity: 1;
  height: auto;
}

.rd-navbar-fixed .rd-navbar-nav li.opened > a {
  background: #e89e00;
  color: #FFF;
}

.rd-navbar-fixed .rd-navbar-nav li.opened > .rd-navbar-submenu-toggle {
  color: #fff;
}

.rd-navbar-fixed .rd-navbar-nav li.opened > .rd-navbar-submenu-toggle::after {
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg);
}

.rd-navbar-fixed .rd-navbar-nav .rd-navbar-submenu-toggle::after {
  content: '\f078';
  position: absolute;
  top: 22px;
  right: 0;
  margin-top: -22px;
  width: 65px;
  height: 44px;
  font: 400 14px "FontAwesome";
  line-height: 42px;
  text-align: center;
  transition: 0.4s all ease;
  z-index: 2;
  color: #fff;
}

.rd-navbar-fixed .rd-navbar-collapse,
.rd-navbar-fixed .rd-navbar-search-toggle {
  position: fixed;
  top: 4px;
  height: 48px;
  z-index: 1000;
  background-color: transparent;
  border: none;
}

.rd-navbar-fixed .rd-navbar-collapse:focus,
.rd-navbar-fixed .rd-navbar-search-toggle:focus {
  outline: none;
}

.rd-navbar-fixed .rd-navbar-shop {
  position: fixed;
  right: 62px;
  top: 28px;
  z-index: 999;
}

.rd-navbar-fixed.active .rd-navbar-nav {
  -webkit-transform: translateX(0);
  transform: translateX(0);
}

@media (max-width: 1199px) {
  .rd-navbar-fixed.rd-navbar--on-search .brand-name {
    opacity: 0;
    visibility: hidden;
    -webkit-transform: scale(0.7);
    transform: scale(0.7);
  }
}

.rd-navbar-fixed.rd-navbar--is-clone {
  display: none;
}

.rd-navbar-fixed.rd-navbar--is-clone .rd-navbar-panel {
  -webkit-transform: translateY(-110%);
  transform: translateY(-110%);
}

.rd-navbar-fixed.rd-navbar--is-clone.rd-navbar--is-stuck .rd-navbar-panel {
  -webkit-transform: translateY(0);
  transform: translateY(0);
}

.rd-navbar-fixed .rd-navbar-fixed--visible {
  display: block;
}

.rd-navbar-fixed .rd-navbar-fixed--hidden {
  display: none;
}

/*
* Sidebar Layout
*/
html.rd-navbar-sidebar-linked body {
  padding-left: 270px;
}

.rd-navbar-sidebar {
  display: block;
}

.rd-navbar-sidebar .rd-navbar-nav li:hover > a,
.rd-navbar-sidebar .rd-navbar-nav li:hover > a:hover,
.rd-navbar-sidebar .rd-navbar-nav li.focus > a, .rd-navbar-sidebar .rd-navbar-nav li.focus > a:hover {
  color: #FFF;
  background: #e89e00;
}

.rd-navbar-sidebar .rd-navbar-nav li:hover > .rd-navbar-submenu-toggle,
.rd-navbar-sidebar .rd-navbar-nav li.focus > .rd-navbar-submenu-toggle {
  color: #fff;
}

.rd-navbar-sidebar .rd-navbar-nav li:hover > .rd-navbar-submenu-toggle:hover,
.rd-navbar-sidebar .rd-navbar-nav li.focus > .rd-navbar-submenu-toggle:hover {
  cursor: pointer;
  color: #fff;
}

.rd-navbar-sidebar .rd-navbar-nav li .rd-navbar-dropdown,
.rd-navbar-sidebar .rd-navbar-nav li .rd-navbar-megamenu {
  transition: opacity 0.3s, height 0.4s ease;
  opacity: 0;
  height: 0;
  overflow: hidden;
}

.rd-navbar-sidebar .rd-navbar-nav li.opened > .rd-navbar-dropdown,
.rd-navbar-sidebar .rd-navbar-nav li.opened > .rd-navbar-megamenu {
  opacity: 1;
  height: auto;
}

.rd-navbar-sidebar .rd-navbar-nav li.opened > a {
  background: #e89e00;
  color: #FFF;
}

.rd-navbar-sidebar .rd-navbar-nav li.opened > .rd-navbar-submenu-toggle {
  color: #fff;
}

.rd-navbar-sidebar .rd-navbar-nav li.opened > .rd-navbar-submenu-toggle::after {
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg);
}

.rd-navbar-sidebar .rd-navbar-submenu-toggle::after {
  content: '\f078';
  position: absolute;
  top: 22px;
  right: 0px;
  margin-top: -22px;
  width: 65px;
  height: 44px;
  font: 400 14px "FontAwesome";
  line-height: 42px;
  text-align: center;
  transition: 0.4s all ease;
  z-index: 2;
}

.rd-navbar-sidebar .rd-navbar-brand {
  text-align: center;
  margin-bottom: 28px;
  padding: 10%;
}

.rd-navbar-sidebar .rd-navbar-brand .brand-name {
  font-size: 30px;
}

.rd-navbar-sidebar .rd-navbar-search {
  position: relative;
  margin-bottom: 10px;
}

.rd-navbar-sidebar .rd-navbar-search-toggle {
  display: none;
}

.rd-navbar-sidebar .rd-navbar-search label {
  display: block;
}

.rd-navbar-sidebar .rd-navbar-search.active .rd-navbar-search-form-input {
  opacity: 1;
  visibility: visible;
}

.rd-navbar-sidebar .rd-navbar-live-search-results {
  -webkit-transform: translateY(30px);
  transform: translateY(30px);
}

.rd-navbar-sidebar .rd-navbar-live-search-results.active {
  -webkit-transform: translateY(0);
  transform: translateY(0);
}

.rd-navbar-sidebar .rd-navbar-live-search-results .search_link p {
  display: none;
}

.rd-navbar-sidebar .rd-navbar-collapse-items {
  top: 0;
  left: 0;
  padding-top: 45px;
  -webkit-transform: scale(0.7);
  transform: scale(0.7);
  -webkit-transform-origin: 0% 0%;
  -moz-transform-origin: 0% 0%;
  -ms-transform-origin: 0% 0%;
  transform-origin: 0% 0%;
  opacity: 0;
  visibility: hidden;
}

.rd-navbar-sidebar .rd-navbar-collapse {
  position: absolute;
  top: 4px;
  left: 4px;
  display: inline-block;
  z-index: 1;
}

.rd-navbar-sidebar .rd-navbar-collapse.active .rd-navbar-collapse-items {
  opacity: 1;
  visibility: visible;
  -webkit-transform: scale(1);
  transform: scale(1);
}

.rd-navbar-sidebar .rd-navbar-sidebar--visible {
  display: block;
}

.rd-navbar-sidebar .rd-navbar-sidebar--hidden {
  display: none;
}

/*
* @subsection   Page boxed layout style redeclaration
*
* @description  Redefines navbar style inside boxed layout
*
* @see          ../modules/_page-layouts.scss
*/
html.boxed.rd-navbar--has-sidebar body {
  padding-left: 300px;
  padding-right: 30px;
}

html.boxed .rd-navbar--is-clone {
  max-width: 1920px;
  margin-left: auto;
  margin-right: auto;
}

ul ul, ul ol, ol ul, ol ol {
  padding-left: 0;
}

.rd-navbar.static-position:first-child {
  position: static;
}

.rd-navbar.static-position:first-child .rd-navbar-nav > li > a,
.rd-navbar.static-position:first-child .rd-navbar-shop,
.rd-navbar.static-position:first-child .rd-navbar-search-toggle {
  color: #212121;
}

.rd-navbar.static-position:first-child .rd-navbar-inner {
  padding-top: 31px;
  padding-bottom: 40px;
}

.rd-navbar.static-position:first-child .rd-navbar-nav-wrap {
  padding-top: 9px;
}

.rd-navbar.static-position:first-child:after {
  content: none;
}

/*
* @subsection   ToTop
* @license      MIT license - http://opensource.org/licenses/MIT
* @version      1.0.0
*/
.ui-to-top {
  font-size: 50px;
  line-height: 1;
  color: #fff;
  border-radius: 50%;
  position: fixed;
  right: 15px;
  bottom: 15px;
  overflow: hidden;
  text-align: center;
  text-decoration: none;
  z-index: 20;
  transition: .3s all ease;
  -webkit-transform: translateY(100px);
  transform: translateY(100px);
}

.ui-to-top:hover, .ui-to-top:focus {
  color: #e89e00;
  text-decoration: none;
}

.ui-to-top.active {
  -webkit-transform: translateY(0);
  transform: translateY(0);
}

.mobile .ui-to-top,
.tablet .ui-to-top {
  display: none !important;
}

@media (min-width: 480px) {
  .ui-to-top {
    right: 40px;
    bottom: 40px;
  }
}

.scrollspy-example {
  position: relative;
  height: 200px;
  margin-top: 10px;
  overflow: auto;
}

/*
* @subsection   RD Google Map
*
* @description  Describes style declarations for RD Google Map extension
*
* @author       Evgeniy Gusarov
* @link         https://ua.linkedin.com/pub/evgeniy-gusarov/8a/a40/54a
* @version      1.0.0
*/
.rd-google-map * {
  color: #000;
}

.rd-google-map__model {
  height: 250px;
}

.rd-google-map__model img {
  max-width: none !important;
}

@media (min-width: 480px) {
  .rd-google-map__model {
    height: 250px;
  }
}

@media (min-width: 768px) {
  .rd-google-map__model {
    height: 295px;
  }
}

.rd-google-map__locations {
  display: none;
}

/*
* @subsection   RD Mail Form
*
* @description  Describes style declarations for RD Mail Form extension
*
* @author       Aleksey Patsurkivskiy
* @version      2.0.0
*/
.rd-mailform {
  position: relative;
  text-align: left;
  margin-left: auto;
  margin-right: auto;
  margin-top: 60px;
}

.rd-mailform fieldset {
  border: none;
}

.rd-mailform fieldset > .row + .row {
  margin-top: 30px;
}

.rd-mailform {
  position: relative;
  display: block;
  width: 100%;
  margin-top: 25px;
  text-align: center;
}

.rd-mailform:first-child {
  margin-top: 0;
}

.rd-mailform label {
  font-weight: inherit;
}

.rd-mailform input, .rd-mailform select {
  height: 56px;
}

.rd-mailform input, .rd-mailform textarea {
  display: block;
  width: 100%;
  font-size: 18px;
  padding: 13px 18px;
  line-height: 28px;
  color: #cdcdcd;
  background: none;
  outline: none;
  font-family: "Roboto", sans-serif;
  text-transform: none;
  border: none;
  text-align: center;
  font-weight: 400;
  border-bottom: 1px solid #fff;
}

.rd-mailform input:-moz-placeholder, .rd-mailform textarea:-moz-placeholder {
  color: #cdcdcd;
  opacity: 1;
  transition: 0.3s;
  text-transform: capitalize;
}

.rd-mailform input::-webkit-input-placeholder, .rd-mailform textarea::-webkit-input-placeholder {
  color: #cdcdcd;
  opacity: 1;
  transition: 0.3s;
}

.rd-mailform input::-moz-placeholder, .rd-mailform textarea::-moz-placeholder {
  color: #cdcdcd;
  opacity: 1;
  transition: 0.3s;
}

.rd-mailform input:-ms-input-placeholder, .rd-mailform textarea:-ms-input-placeholder {
  color: #cdcdcd;
  opacity: 1;
  transition: 0.3s;
}

.rd-mailform input:focus:-moz-placeholder, .rd-mailform textarea:focus:-moz-placeholder {
  opacity: 0.4;
}

.rd-mailform input:focus::-webkit-input-placeholder, .rd-mailform textarea:focus::-webkit-input-placeholder {
  opacity: 0.4;
}

.rd-mailform input:focus::-moz-placeholder, .rd-mailform textarea:focus::-moz-placeholder {
  opacity: 0.4;
}

.rd-mailform input:focus:-ms-input-placeholder, .rd-mailform textarea:focus:-ms-input-placeholder {
  opacity: 0.4;
}

.rd-mailform textarea {
  resize: none;
  overflow: hidden;
  min-height: 56px;
  height: 56px;
  max-height: 84px;
}

.rd-mailform > * + * {
  margin-top: 69px;
}

@media (min-width: 768px) {
  .rd-mailform {
    margin-top: 70px;
  }
}

div[class^="rd-mailform-validate"] {
  position: fixed;
  left: 50%;
  bottom: 50px;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%);
  margin-left: auto;
  margin-right: auto;
  margin-top: 40px;
  min-height: 50px;
  font-weight: 700;
  text-align: center;
  padding: 12px 25px 10px 40px;
  font-size: 16px;
  opacity: 0;
  transition: .3s;
  color: #fff;
  background: #ff6859;
  z-index: 999;
  pointer-events: none;
}

div[class^="rd-mailform-validate"]:before {
  content: '\f00d';
  font-family: 'FontAwesome';
  display: inline-block;
  font-size: 14px;
  position: absolute;
  top: 50%;
  left: 15px;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
}

div[class^="rd-mailform-validate"].success {
  opacity: 1;
}

div[class^="rd-mailform-validate"].error {
  opacity: 1;
}

.mfInput {
  position: relative;
}

/**
 * RD Validator
 * @Section
 */
.mfValidation {
  position: absolute;
  top: 0;
  right: 7px;
  color: #e89e00;
  font-weight: inherit;
  font-size: 12px;
  line-height: 2;
  opacity: 0;
  visibility: hidden;
  pointer-events: none;
  transition: .3s all ease;
}

.mfValidation.mfValidation--active {
  opacity: 1;
  visibility: visible;
}

.mfInput {
  position: relative;
}

}

</style>
<div class="page">
      <!-- Page Header-->
      <header style="background-image:url('images/index-1.jpg')" class="page-head bg-image">
        <div class="rd-navbar-wrap" style="height: 0px;">
          <nav class="rd-navbar rd-navbar-fixed">
            <div class="rd-navbar-inner">
              <!-- RD Navbar Panel-->
              <div class="rd-navbar-panel">
                <div class="rd-navbar-brand"><a href="index.html" class="brand-name">majestic</a></div>
              </div>
              <div class="contact-info">
                <p>delivery &amp; reservation:<a href="callto:#">+1 800 559 35 48</a></p>
              </div>
            </div>
          </nav>
        </div>
        <section class="section-gradient section-xs">
          <div class="container p0 border-radius-sm z-index-2">
            <div class="bg-image-2 border-radius-sm container-shadow">
              <!--Jumbotron-->
              <div class="jumbotron text-md-left text-center">
                <div class="row">
                  <div class="col-md-5 col-md-offset-5">
                    <p class="big">enjoy</p>
                    <p>our delicious &amp; fine<br> Italian Cuisine</p><a href="#" class="btn btn-primary btn-xs">More</a>
                  </div>
                </div>
              </div>
            </div>
            <ul class="list-inline text-center">
              <li><a href="#"><span class="icon icon-xs icon-default fl-glypho-facebook2"></span></a></li>
              <li><a href="#"><span class="icon icon-xs icon-default fl-glypho-twitter"></span></a></li>
              <li><a href="#"><span class="icon icon-xs icon-default fl-glypho-google-plus"></span></a></li>
              <li><a href="#"><span class="icon icon-xs icon-default fl-glypho-instagram19"></span></a></li>
            </ul>
          </div>
        </section>
      </header>
      <!-- Page Content-->
      <main class="page-content"></main>
      <!--Section Welcome to Majestic-->
      <section style="background-image:url('images/index-3.jpg')" class="section-gradient section-sm bg-image text-center text-md-left">
        <div class="shell">
          <div class="range range-md-reverse z-index-2">
            <div class="cell-md-5 cell-md-preffix-1 inset-3">
              <h1 class="offset-1">welcome</h1>
              <p class="h3">to majestic</p>
              <p>Come to experience the exceptional gastronomic voyage in the ultimate venue. Our authentic cuisine unites people connecting history and traditions in the warm and friendly atmosphere.</p>
              <p>Our family has been in the restaurant business for a very long time. Nowadays we can proudly boast our reputation for a well known Italian restaurant in our area. We are famous for the fabulous authentic cuisine, professional chef and dedicated staff.</p>
            </div>
            <div class="cell-md-6">
              <!--Thumbnail-->
              <div class="thumbnail border-radius-xs box-shadow"><img src="images/index-4.jpg" width="570" height="595" alt="">
                <div class="caption">
                  <p class="big">every Thursday!</p>
                  <h1>Seafood Night</h1>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!--Section Menu-->
      <section style="background-image:url('images/index-5.jpg')" class="bg-image section-gradient section-md">
        <div class="shell">
          <h1 class="text-center">menu</h1>
          <p class="h3 text-center">THE TASTE OF ITALY</p>
          <div class="range z-index-2 flow-offset-2">
            <div class="cell-sm-6 cell-lg-4">
              <!--Pricing Table-->
              <div class="pricing-table">
                <h6 class="text-center">Pane &amp; pizzetta</h6>
                <table class="table-content">
                  <tbody><tr>
                    <td>Pane fresco</td>
                    <td>$5.50</td>
                  </tr>
                  <tr>
                    <td>Pane all′aglio</td>
                    <td>$4.50</td>
                  </tr>
                  <tr>
                    <td>Pizzetta bianca</td>
                    <td>$7.00</td>
                  </tr>
                  <tr>
                    <td>Pizzetta napoli</td>
                    <td>$8.50</td>
                  </tr>
                  <tr>
                    <td>Pizzetta  rotolo</td>
                    <td>$14.00</td>
                  </tr>
                  <tr>
                    <td>Bruschetta</td>
                    <td>$11.00</td>
                  </tr>
                  <tr>
                    <td>Calamari fritti</td>
                    <td>$13.00</td>
                  </tr>
                  <tr>
                    <td>Gamberi</td>
                    <td>$9.99</td>
                  </tr>
                  <tr>
                    <td>Vitello tonnato</td>
                    <td>$13.00</td>
                  </tr>
                  <tr>
                    <td>Arancini</td>
                    <td>$21.00</td>
                  </tr>
                </tbody></table>
              </div>
            </div>
            <div class="cell-sm-6 cell-lg-4">
              <!--Pricing Table-->
              <div class="pricing-table">
                <h6 class="text-center">Pizza</h6>
                <table class="table-content">
                  <tbody><tr>
                    <td>Margherita</td>
                    <td>$16.00</td>
                  </tr>
                  <tr>
                    <td>Cotto</td>
                    <td>$22.00</td>
                  </tr>
                  <tr>
                    <td>Calabrese</td>
                    <td>$18.00</td>
                  </tr>
                  <tr>
                    <td>Siciliana</td>
                    <td>$23.50</td>
                  </tr>
                  <tr>
                    <td>Popeye</td>
                    <td>$21.00</td>
                  </tr>
                  <tr>
                    <td>Vegetariana</td>
                    <td>$20.00</td>
                  </tr>
                  <tr>
                    <td>Calzone vegetariano</td>
                    <td>$24.00</td>
                  </tr>
                  <tr>
                    <td>Modenese</td>
                    <td>$20.50</td>
                  </tr>
                  <tr>
                    <td>Parma</td>
                    <td>$24.00</td>
                  </tr>
                  <tr>
                    <td>Pizza Bologna</td>
                    <td>$21.00</td>
                  </tr>
                </tbody></table>
              </div>
            </div>
            <div class="cell-sm-6 cell-sm-preffix-3 cell-lg-4 cell-lg-preffix-0">
              <!--Pricing Table-->
              <div class="pricing-table">
                <h6 class="text-center">Pasta Fresca</h6>
                <table class="table-content">
                  <tbody><tr>
                    <td>Spaghetti carbonara</td>
                    <td>$14.50</td>
                  </tr>
                  <tr>
                    <td>Paccheri allo zafferano</td>
                    <td>$16.00</td>
                  </tr>
                  <tr>
                    <td>Tagliatelle al ragu</td>
                    <td>$13.00</td>
                  </tr>
                  <tr>
                    <td>Gnocchi  amatriciana</td>
                    <td>$12.50</td>
                  </tr>
                  <tr>
                    <td>Risotto marinara</td>
                    <td>$21.00</td>
                  </tr>
                  <tr>
                    <td>Ravioli di mare</td>
                    <td>$22.00</td>
                  </tr>
                  <tr>
                    <td>Ravioli di ricotta</td>
                    <td>$24.00</td>
                  </tr>
                  <tr>
                    <td>Lasagne Romagnole</td>
                    <td>$19.99</td>
                  </tr>
                  <tr>
                    <td>Fetuccine</td>
                    <td>$13.00</td>
                  </tr>
                  <tr>
                    <td>Casarecce alla siciliana</td>
                    <td>$21.00</td>
                  </tr>
                </tbody></table>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!--Section Catering-->
      <section style="background-image:url('images/index-6.jpg')" class="bg-image section-gradient section-md section-md-inset-1">
        <div class="shell">
          <h1 class="text-center">catering</h1>
          <p class="h3 text-center">please call at least 24 hours in advance<br> for catering orders</p>
          <div class="range offset-2 flow-offset-1">
            <div class="cell-sm-6 cell-md-4">
              <!--Product--><a href="#" class="product border-radius-xs">
                <div class="product-inner"><span class="icon icon-sm icon-primary restaurant-icon-08"></span>
                  <h4>appetizers</h4>
                </div></a>
            </div>
            <div class="cell-sm-6 cell-md-4">
              <!--Product--><a href="#" class="product border-radius-xs">
                <div class="product-inner"><span class="icon icon-sm icon-primary restaurant-icon-22"></span>
                  <h4>party platters</h4>
                </div></a>
            </div>
            <div class="cell-sm-6 cell-md-4">
              <!--Product--><a href="#" class="product border-radius-xs">
                <div class="product-inner"><span class="icon icon-sm icon-primary restaurant-icon-33"></span>
                  <h4>desserts</h4>
                </div></a>
            </div>
            <div class="cell-sm-6 cell-md-4">
              <!--Product--><a href="#" class="product border-radius-xs">
                <div class="product-inner"><span class="icon icon-sm icon-primary restaurant-icon-30"></span>
                  <h4>drinks</h4>
                </div></a>
            </div>
            <div class="cell-sm-6 cell-md-4">
              <!--Product--><a href="#" class="product border-radius-xs">
                <div class="product-inner"><span class="icon icon-sm icon-primary restaurant-icon-18"></span>
                  <h4>pizza</h4>
                </div></a>
            </div>
            <div class="cell-sm-6 cell-md-4">
              <!--Product--><a href="#" class="product border-radius-xs">
                <div class="product-inner"><span class="icon icon-sm icon-primary restaurant-icon-36"></span>
                  <h4>vegan menu</h4>
                </div></a>
            </div>
          </div>
        </div>
      </section>
      <!--Section Opening Times-->
      <section style="background-image:url('images/index-7.jpg')" class="bg-image section-lg section-gradient text-center">
        <div class="shell">
          <h2 class="opacity-half">Opening Times</h2>
          <div class="range">
            <div class="cell-sm-6">
              <!--Panel-->
              <div class="panel">
                <h5>Lunch</h5>
                <p class="h5">Friday – 11:30am to 2:00pm</p>
              </div>
            </div>
            <div class="cell-sm-6">
              <!--Panel-->
              <div class="panel">
                <h5>Dinner</h5>
                <p class="h5">7 Days  5:30pm to 9:30pm</p>
              </div>
            </div>
          </div>
          <h2>contact form</h2>
          <!-- Rd Mailform result field-->
          <div class="rd-mailform-validate"></div>
          <!-- RD Mailform-->
          <form data-result-class="rd-mailform-validate" data-form-type="contact" method="post" action="bat/rd-mailform.php" class="rd-mailform z-index-2">
            <div class="range">
              <div class="cell-sm-4">
                <div class="mfInput"><input type="text" name="name" data-constraints="@NotEmpty" placeholder="Your Name"><div class="mfValidation"></div></div>
              </div>
              <div class="cell-sm-4">
                <div class="mfInput"><input type="text" name="email" data-constraints="@NotEmpty @Email" placeholder="Your Email"><div class="mfValidation"></div></div>
              </div>
              <div class="cell-sm-4">
                <div class="mfInput"><textarea name="message" data-constraints="@NotEmpty" placeholder="Message"></textarea><div class="mfValidation"></div></div>
              </div>
            </div>
            <button class="btn btn-sm btn-primary">Send</button>
          </form>
        </div>
      </section>
      <!-- Page Footer-->
      <!--Footer Page-->
      <footer class="page-foot text-center">
        <!--Section Address-->
        <section class="inset-2 section-transparent">
          <div class="shell">
            <div class="range range-xs-middle">
              <div class="cell-md-4 text-md-left">
                <address class="contact-info">
                  <p class="h5">28 Jackson Blvd Ste 1020 Chicago<br>IL 60604-2340</p>
                </address>
              </div>
              <div class="cell-md-4">
                <p class="h5"><a href="mailto:#info@demolink.org">info@demolink.org</a></p>
              </div>
              <div class="cell-md-3 cell-md-preffix-1 text-md-left copyright">
                <p>© <span id="copyright-year">2019</span></p>
                <p>all rights reserved
                </p>
              </div>
            </div>
          </div>
        </section>
        <!-- Section RD Google Map-->
        <section>
          <div class="rd-google-map">
            <div id="google-map" data-zoom="14" data-x="-73.9874068" data-y="40.643180" class="rd-google-map__model lazy-loaded" style="position: relative; overflow: hidden;"><div style="height: 100%; width: 100%; position: absolute; top: 0px; left: 0px; background-color: rgb(229, 227, 223);"><div class="gm-style" style="position: absolute; z-index: 0; left: 0px; top: 0px; height: 100%; width: 100%; padding: 0px; border-width: 0px; margin: 0px;"><div tabindex="0" style="position: absolute; z-index: 0; left: 0px; top: 0px; height: 100%; width: 100%; padding: 0px; border-width: 0px; margin: 0px; cursor: url(&quot;https://maps.gstatic.com/mapfiles/openhand_8_8.cur&quot;), default; touch-action: pan-x pan-y;"><div style="z-index: 1; position: absolute; left: 50%; top: 50%; width: 100%; transform: translate(0px, 0px);"><div style="position: absolute; left: 0px; top: 0px; z-index: 100; width: 100%;"><div style="position: absolute; left: 0px; top: 0px; z-index: 0;"><div style="position: absolute; z-index: 986; transform: matrix(1, 0, 0, 1, -192, -63);"><div style="position: absolute; left: 256px; top: 0px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div><div style="position: absolute; left: 0px; top: 0px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div><div style="position: absolute; left: 0px; top: -256px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div><div style="position: absolute; left: 256px; top: -256px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div><div style="position: absolute; left: 512px; top: -256px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div><div style="position: absolute; left: 512px; top: 0px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div><div style="position: absolute; left: -256px; top: 0px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div><div style="position: absolute; left: -256px; top: -256px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div><div style="position: absolute; left: 768px; top: -256px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div><div style="position: absolute; left: 768px; top: 0px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div><div style="position: absolute; left: -512px; top: 0px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div><div style="position: absolute; left: -512px; top: -256px; width: 256px; height: 256px;"><div style="width: 256px; height: 256px;"></div></div></div></div></div><div style="position: absolute; left: 0px; top: 0px; z-index: 101; width: 100%;"></div><div style="position: absolute; left: 0px; top: 0px; z-index: 102; width: 100%;"></div><div style="position: absolute; left: 0px; top: 0px; z-index: 103; width: 100%;"><div style="width: 46px; height: 61px; overflow: hidden; position: absolute; left: -23px; top: -61px; z-index: 0;"><img alt="" src="images/gmap_marker.png" draggable="false" style="position: absolute; left: 0px; top: 0px; user-select: none; width: 46px; height: 61px; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: 0px; top: 0px; z-index: -1;"><div style="position: absolute; z-index: 986; transform: matrix(1, 0, 0, 1, -192, -63);"><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: 256px; top: 0px;"></div><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: 0px; top: 0px;"></div><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: 0px; top: -256px;"></div><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: 256px; top: -256px;"></div><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: 512px; top: -256px;"></div><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: 512px; top: 0px;"></div><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: -256px; top: 0px;"></div><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: -256px; top: -256px;"></div><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: 768px; top: -256px;"></div><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: 768px; top: 0px;"></div><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: -512px; top: 0px;"></div><div style="width: 256px; height: 256px; overflow: hidden; position: absolute; left: -512px; top: -256px;"></div></div></div></div><div style="position: absolute; left: 0px; top: 0px; z-index: 0;"><div style="position: absolute; z-index: 986; transform: matrix(1, 0, 0, 1, -192, -63);"><div style="position: absolute; left: 256px; top: 0px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4825!3i6164!4i256!2m3!1e0!2sm!3i454162878!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=85471" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: 0px; top: 0px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4824!3i6164!4i256!2m3!1e0!2sm!3i454162878!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=26044" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: 0px; top: -256px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4824!3i6163!4i256!2m3!1e0!2sm!3i454162890!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=52615" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: 256px; top: -256px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4825!3i6163!4i256!2m3!1e0!2sm!3i454162890!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=112042" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: 512px; top: -256px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4826!3i6163!4i256!2m3!1e0!2sm!3i454162890!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=40398" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: 512px; top: 0px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4826!3i6164!4i256!2m3!1e0!2sm!3i454162866!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=79342" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: -256px; top: 0px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4823!3i6164!4i256!2m3!1e0!2sm!3i454162878!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=97688" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: -256px; top: -256px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4823!3i6163!4i256!2m3!1e0!2sm!3i454162890!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=124259" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: 768px; top: -256px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4827!3i6163!4i256!2m3!1e0!2sm!3i454162890!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=99825" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: 768px; top: 0px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4827!3i6164!4i256!2m3!1e0!2sm!3i454162866!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=7698" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: -512px; top: 0px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4822!3i6164!4i256!2m3!1e0!2sm!3i454162830!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=38179" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div><div style="position: absolute; left: -512px; top: -256px; width: 256px; height: 256px; transition: opacity 200ms linear 0s;"><img draggable="false" alt="" role="presentation" src="https://maps.google.com/maps/vt?pb=!1m5!1m4!1i14!2i4822!3i6163!4i256!2m3!1e0!2sm!3i454162830!2m3!1e2!6m1!3e5!3m14!2sen-IN!3sUS!5e18!12m1!1e68!12m3!1e37!2m1!1ssmartmaps!12m4!1e26!2m2!1sstyles!2zcC5zOi02MHxwLmw6LTYw!4e0&amp;token=90151" style="width: 256px; height: 256px; user-select: none; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div></div></div></div><div class="gm-style-pbc" style="z-index: 2; position: absolute; height: 100%; width: 100%; padding: 0px; border-width: 0px; margin: 0px; left: 0px; top: 0px; opacity: 0;"><p class="gm-style-pbt"></p></div><div style="z-index: 3; position: absolute; height: 100%; width: 100%; padding: 0px; border-width: 0px; margin: 0px; left: 0px; top: 0px; touch-action: pan-x pan-y;"><div style="z-index: 4; position: absolute; left: 50%; top: 50%; width: 100%; transform: translate(0px, 0px);"><div style="position: absolute; left: 0px; top: 0px; z-index: 104; width: 100%;"></div><div style="position: absolute; left: 0px; top: 0px; z-index: 105; width: 100%;"></div><div style="position: absolute; left: 0px; top: 0px; z-index: 106; width: 100%;"><div title="" style="width: 46px; height: 61px; overflow: hidden; position: absolute; opacity: 0; cursor: pointer; touch-action: none; left: -23px; top: -61px; z-index: 0;"><img alt="" src="images/gmap_marker.png" draggable="false" style="position: absolute; left: 0px; top: 0px; user-select: none; width: 46px; height: 61px; border: 0px; padding: 0px; margin: 0px; max-width: none;"></div></div><div style="position: absolute; left: 0px; top: 0px; z-index: 107; width: 100%;"></div></div></div></div><iframe aria-hidden="true" frameborder="0" style="z-index: -1; position: absolute; width: 100%; height: 100%; top: 0px; left: 0px; border: none;" src="about:blank"></iframe><div style="margin-left: 5px; margin-right: 5px; z-index: 1000000; position: absolute; left: 0px; bottom: 0px;"><a target="_blank" rel="noopener" href="https://maps.google.com/maps?ll=40.64318,-73.987407&amp;z=14&amp;t=m&amp;hl=en-IN&amp;gl=US&amp;mapclient=apiv3" title="Open this area in Google Maps (opens a new window)" style="position: static; overflow: visible; float: none; display: inline;"><div style="width: 66px; height: 26px; cursor: pointer;"><img alt="" src="https://maps.gstatic.com/mapfiles/api-3/images/google_white5.png" draggable="false" style="position: absolute; left: 0px; top: 0px; width: 66px; height: 26px; user-select: none; border: 0px; padding: 0px; margin: 0px;"></div></a></div><div style="background-color: white; padding: 15px 21px; border: 1px solid rgb(171, 171, 171); font-family: Roboto, Arial, sans-serif; color: rgb(34, 34, 34); box-sizing: border-box; box-shadow: rgba(0, 0, 0, 0.2) 0px 4px 16px; z-index: 10000002; display: none; width: 300px; height: 180px; position: absolute; left: 525px; top: 58px;"><div style="padding: 0px 0px 10px; font-size: 16px;">Map Data</div><div style="font-size: 13px;">Map data ©2019 Google</div><button draggable="false" title="Close" aria-label="Close" type="button" class="gm-ui-hover-effect" style="background: none; display: block; border: 0px; margin: 0px; padding: 0px; position: absolute; cursor: pointer; user-select: none; top: 0px; right: 0px; width: 37px; height: 37px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2224px%22%20height%3D%2224px%22%20viewBox%3D%220%200%2024%2024%22%20fill%3D%22%23000000%22%3E%0A%20%20%20%20%3Cpath%20d%3D%22M19%206.41L17.59%205%2012%2010.59%206.41%205%205%206.41%2010.59%2012%205%2017.59%206.41%2019%2012%2013.41%2017.59%2019%2019%2017.59%2013.41%2012z%22%2F%3E%0A%20%20%20%20%3Cpath%20d%3D%22M0%200h24v24H0z%22%20fill%3D%22none%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="pointer-events: none; display: block; width: 13px; height: 13px; margin: 12px;"></button></div><div class="gmnoprint" style="z-index: 1000001; position: absolute; right: 286px; bottom: 0px; width: 121px;"><div draggable="false" class="gm-style-cc" style="user-select: none; height: 14px; line-height: 14px;"><div style="opacity: 0.7; width: 100%; height: 100%; position: absolute;"><div style="width: 1px;"></div><div style="background-color: rgb(245, 245, 245); width: auto; height: 100%; margin-left: 1px;"></div></div><div style="position: relative; padding-right: 6px; padding-left: 6px; font-family: Roboto, Arial, sans-serif; font-size: 10px; color: rgb(68, 68, 68); white-space: nowrap; direction: ltr; text-align: right; vertical-align: middle; display: inline-block;"><a style="text-decoration: none; cursor: pointer; display: none;">Map Data</a><span>Map data ©2019 Google</span></div></div></div><div class="gmnoscreen" style="position: absolute; right: 0px; bottom: 0px;"><div style="font-family: Roboto, Arial, sans-serif; font-size: 11px; color: rgb(68, 68, 68); direction: ltr; text-align: right; background-color: rgb(245, 245, 245);">Map data ©2019 Google</div></div><div class="gmnoprint gm-style-cc" draggable="false" style="z-index: 1000001; user-select: none; height: 14px; line-height: 14px; position: absolute; right: 215px; bottom: 0px;"><div style="opacity: 0.7; width: 100%; height: 100%; position: absolute;"><div style="width: 1px;"></div><div style="background-color: rgb(245, 245, 245); width: auto; height: 100%; margin-left: 1px;"></div></div><div style="position: relative; padding-right: 6px; padding-left: 6px; font-family: Roboto, Arial, sans-serif; font-size: 10px; color: rgb(68, 68, 68); white-space: nowrap; direction: ltr; text-align: right; vertical-align: middle; display: inline-block;"><a href="https://www.google.com/intl/en-IN_US/help/terms_maps.html" target="_blank" rel="noopener" style="text-decoration: none; cursor: pointer; color: rgb(68, 68, 68);">Terms of Use</a></div></div><button draggable="false" title="Toggle fullscreen view" aria-label="Toggle fullscreen view" type="button" style="background: none rgb(255, 255, 255); display: none; border: 0px; margin: 10px; padding: 0px; position: absolute; cursor: pointer; user-select: none; top: 0px; right: 0px;"></button><div draggable="false" class="gm-style-cc" style="user-select: none; height: 14px; line-height: 14px; position: absolute; right: 120px; bottom: 0px;"><div style="opacity: 0.7; width: 100%; height: 100%; position: absolute;"><div style="width: 1px;"></div><div style="background-color: rgb(245, 245, 245); width: auto; height: 100%; margin-left: 1px;"></div></div><div style="position: relative; padding-right: 6px; padding-left: 6px; font-family: Roboto, Arial, sans-serif; font-size: 10px; color: rgb(68, 68, 68); white-space: nowrap; direction: ltr; text-align: right; vertical-align: middle; display: inline-block;"><a target="_blank" rel="noopener" title="Report errors in the road map or imagery to Google" href="https://www.google.com/maps/@40.64318,-73.9874068,14z/data=!10m1!1e1!12b1?source=apiv3&amp;rapsrc=apiv3" style="font-family: Roboto, Arial, sans-serif; font-size: 10px; color: rgb(68, 68, 68); text-decoration: none; position: relative;">Report a map error</a></div></div><div class="gmnoprint gm-bundled-control gm-bundled-control-on-bottom" draggable="false" controlwidth="40" controlheight="113" style="margin: 10px; user-select: none; position: absolute; bottom: 126px; right: 40px;"><div class="gmnoprint" controlwidth="40" controlheight="81" style="position: absolute; left: 0px; top: 32px;"><div draggable="false" style="user-select: none; box-shadow: rgba(0, 0, 0, 0.3) 0px 1px 4px -1px; border-radius: 2px; cursor: pointer; background-color: rgb(255, 255, 255); width: 40px; height: 81px;"><button draggable="false" title="Zoom in" aria-label="Zoom in" type="button" class="gm-control-active" style="background: none; display: block; border: 0px; margin: 0px; padding: 0px; position: relative; cursor: pointer; user-select: none; overflow: hidden; width: 40px; height: 40px; top: 0px; left: 0px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2218%22%20height%3D%2218%22%20viewBox%3D%220%200%2018%2018%22%3E%0A%20%20%3Cpolygon%20fill%3D%22%23666%22%20points%3D%2218%2C7%2011%2C7%2011%2C0%207%2C0%207%2C7%200%2C7%200%2C11%207%2C11%207%2C18%2011%2C18%2011%2C11%2018%2C11%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="height: 18px; width: 18px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2218%22%20height%3D%2218%22%20viewBox%3D%220%200%2018%2018%22%3E%0A%20%20%3Cpolygon%20fill%3D%22%23333%22%20points%3D%2218%2C7%2011%2C7%2011%2C0%207%2C0%207%2C7%200%2C7%200%2C11%207%2C11%207%2C18%2011%2C18%2011%2C11%2018%2C11%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="height: 18px; width: 18px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2218%22%20height%3D%2218%22%20viewBox%3D%220%200%2018%2018%22%3E%0A%20%20%3Cpolygon%20fill%3D%22%23111%22%20points%3D%2218%2C7%2011%2C7%2011%2C0%207%2C0%207%2C7%200%2C7%200%2C11%207%2C11%207%2C18%2011%2C18%2011%2C11%2018%2C11%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="height: 18px; width: 18px;"></button><div style="position: relative; overflow: hidden; width: 30px; height: 1px; margin: 0px 5px; background-color: rgb(230, 230, 230); top: 0px;"></div><button draggable="false" title="Zoom out" aria-label="Zoom out" type="button" class="gm-control-active" style="background: none; display: block; border: 0px; margin: 0px; padding: 0px; position: relative; cursor: pointer; user-select: none; overflow: hidden; width: 40px; height: 40px; top: 0px; left: 0px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2218%22%20height%3D%2218%22%20viewBox%3D%220%200%2018%2018%22%3E%0A%20%20%3Cpath%20fill%3D%22%23666%22%20d%3D%22M0%2C7h18v4H0V7z%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="height: 18px; width: 18px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2218%22%20height%3D%2218%22%20viewBox%3D%220%200%2018%2018%22%3E%0A%20%20%3Cpath%20fill%3D%22%23333%22%20d%3D%22M0%2C7h18v4H0V7z%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="height: 18px; width: 18px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2218%22%20height%3D%2218%22%20viewBox%3D%220%200%2018%2018%22%3E%0A%20%20%3Cpath%20fill%3D%22%23111%22%20d%3D%22M0%2C7h18v4H0V7z%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="height: 18px; width: 18px;"></button></div></div><div style="position: absolute; left: 20px; top: 0px;"></div><div class="gmnoprint" controlwidth="40" controlheight="40" style="display: none; position: absolute;"><div style="width: 40px; height: 40px;"><button draggable="false" title="Rotate map 90 degrees" aria-label="Rotate map 90 degrees" type="button" class="gm-control-active" style="background: none rgb(255, 255, 255); display: none; border: 0px; margin: 0px 0px 32px; padding: 0px; position: relative; cursor: pointer; user-select: none; width: 40px; height: 40px; top: 0px; left: 0px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.3) 0px 1px 4px -1px; border-radius: 2px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2224%22%20height%3D%2222%22%20viewBox%3D%220%200%2024%2022%22%3E%0A%20%20%3Cpath%20fill%3D%22%23666%22%20fill-rule%3D%22evenodd%22%20d%3D%22M20%2010c0-5.52-4.48-10-10-10s-10%204.48-10%2010v5h5v-5c0-2.76%202.24-5%205-5s5%202.24%205%205v5h-4l6.5%207%206.5-7h-4v-5z%22%20clip-rule%3D%22evenodd%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="height: 18px; width: 18px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2224%22%20height%3D%2222%22%20viewBox%3D%220%200%2024%2022%22%3E%0A%20%20%3Cpath%20fill%3D%22%23333%22%20fill-rule%3D%22evenodd%22%20d%3D%22M20%2010c0-5.52-4.48-10-10-10s-10%204.48-10%2010v5h5v-5c0-2.76%202.24-5%205-5s5%202.24%205%205v5h-4l6.5%207%206.5-7h-4v-5z%22%20clip-rule%3D%22evenodd%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="height: 18px; width: 18px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2224%22%20height%3D%2222%22%20viewBox%3D%220%200%2024%2022%22%3E%0A%20%20%3Cpath%20fill%3D%22%23111%22%20fill-rule%3D%22evenodd%22%20d%3D%22M20%2010c0-5.52-4.48-10-10-10s-10%204.48-10%2010v5h5v-5c0-2.76%202.24-5%205-5s5%202.24%205%205v5h-4l6.5%207%206.5-7h-4v-5z%22%20clip-rule%3D%22evenodd%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="height: 18px; width: 18px;"></button><button draggable="false" title="Tilt map" aria-label="Tilt map" type="button" class="gm-tilt gm-control-active" style="background: none rgb(255, 255, 255); display: block; border: 0px; margin: 0px; padding: 0px; position: relative; cursor: pointer; user-select: none; width: 40px; height: 40px; top: 0px; left: 0px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.3) 0px 1px 4px -1px; border-radius: 2px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2218px%22%20height%3D%2216px%22%20viewBox%3D%220%200%2018%2016%22%3E%0A%20%20%3Cpath%20fill%3D%22%23666%22%20d%3D%22M0%2C16h8V9H0V16z%20M10%2C16h8V9h-8V16z%20M0%2C7h8V0H0V7z%20M10%2C0v7h8V0H10z%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="width: 18px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2218px%22%20height%3D%2216px%22%20viewBox%3D%220%200%2018%2016%22%3E%0A%20%20%3Cpath%20fill%3D%22%23333%22%20d%3D%22M0%2C16h8V9H0V16z%20M10%2C16h8V9h-8V16z%20M0%2C7h8V0H0V7z%20M10%2C0v7h8V0H10z%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="width: 18px;"><img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%2218px%22%20height%3D%2216px%22%20viewBox%3D%220%200%2018%2016%22%3E%0A%20%20%3Cpath%20fill%3D%22%23111%22%20d%3D%22M0%2C16h8V9H0V16z%20M10%2C16h8V9h-8V16z%20M0%2C7h8V0H0V7z%20M10%2C0v7h8V0H10z%22%2F%3E%0A%3C%2Fsvg%3E%0A" style="width: 18px;"></button></div></div></div></div></div><div style="background-color: white; font-weight: 500; font-family: Roboto, sans-serif; padding: 15px 25px; box-sizing: border-box; top: 5px; border: 1px solid rgba(0, 0, 0, 0.12); border-radius: 5px; left: 50%; max-width: 375px; position: absolute; transform: translateX(-50%); width: calc(100% - 10px); z-index: 1;"><div><img alt="" src="https://maps.gstatic.com/mapfiles/api-3/images/google_gray.svg" draggable="false" style="padding: 0px; margin: 0px; border: 0px; height: 17px; vertical-align: middle; width: 52px; user-select: none;"></div><div style="line-height: 20px; margin: 15px 0px;"><span style="color: rgba(0, 0, 0, 0.87); font-size: 14px;">This page can't load Google Maps correctly.</span></div><table style="width: 100%;"><tr><td style="line-height: 16px; vertical-align: middle;"><a href="https://developers.google.com/maps/documentation/javascript/error-messages?utm_source=maps_js&amp;utm_medium=degraded&amp;utm_campaign=keyless#api-key-and-billing-errors" target="_blank" rel="noopener" style="color: rgba(0, 0, 0, 0.54); font-size: 12px;">Do you own this website?</a></td><td style="text-align: right;"><button class="dismissButton">OK</button></td></tr></table></div><div style="background-color: white; font-weight: 500; font-family: Roboto, sans-serif; padding: 15px 25px; box-sizing: border-box; top: 5px; border: 1px solid rgba(0, 0, 0, 0.12); border-radius: 5px; left: 50%; max-width: 375px; position: absolute; transform: translateX(-50%); width: calc(100% - 10px); z-index: 1;"><div><img alt="" src="https://maps.gstatic.com/mapfiles/api-3/images/google_gray.svg" draggable="false" style="padding: 0px; margin: 0px; border: 0px; height: 17px; vertical-align: middle; width: 52px; user-select: none;"></div><div style="line-height: 20px; margin: 15px 0px;"><span style="color: rgba(0, 0, 0, 0.87); font-size: 14px;">This page can't load Google Maps correctly.</span></div><table style="width: 100%;"><tr><td style="line-height: 16px; vertical-align: middle;"><a href="https://developers.google.com/maps/documentation/javascript/error-messages?utm_source=maps_js&amp;utm_medium=degraded&amp;utm_campaign=billing#api-key-and-billing-errors" target="_blank" rel="noopener" style="color: rgba(0, 0, 0, 0.54); font-size: 12px;">Do you own this website?</a></td><td style="text-align: right;"><button class="dismissButton">OK</button></td></tr></table></div></div>
            <ul class="rd-google-map__locations">
              <li data-x="-73.9874068" data-y="40.643180">
                <p>9870 St Vincent Place, Glasgow, DC 45 Fr 45.<span>800 2345-6789</span></p>
              </li>
            </ul>
          </div>
        </section>
      </footer>
    </div>
