<html lang="en"><head><meta charset="utf-8">
<link rel="icon" href="/portfolio/favicon.png"><meta name="viewport" content="width=device-width,initial-scale=1">
<meta name="theme-color" content="#000000"><meta name="description" content="Portfolio Website">
<link rel="apple-touch-icon" href="/portfolio/favicon.png"><link rel="manifest" href="/portfolio/manifest.json">
<meta name="description" content="Use Developer Portfolio and create your own personalised portfolio today! With multiple themes to choose from, our easily customisable, user friendly website is designed to cater to developers and freelancers alike."><meta property="og:image" content="Developer Portfolio">
<meta property="og:site_name" content="Developer Portfolio"><meta property="og:title" content="Developer Portfolio">
<meta property="og:url" content="https://dev-portfolio-template.netlify.app/"><meta property="og:type" content="website">
<meta property="og:description" content="Use Developer Portfolio and create your own personalised portfolio today! With multiple themes to choose from, our easily customisable, user friendly website is designed to cater to developers and freelancers alike.">
<meta itemprop="name" content="Developer Portfolio"><meta itemprop="url" content="https://dev-portfolio-template.netlify.app/">
<meta itemprop="description" content="Use Developer Portfolio and create your own personalised portfolio today! With multiple themes to choose from, our easily customisable, user friendly website is designed to cater to developers and freelancers alike."><meta itemprop="thumbnailUrl" content="">
<meta name="twitter:url" content="https://dev-portfolio-template.netlify.app/"><meta name="twitter:title" content="Developer Portfolio">
<meta name="twitter:description" content="Use Developer Portfolio and create your own personalised portfolio today! With multiple themes to choose from, our easily customisable, user friendly website is designed to cater to developers and freelancers alike."><meta name="twitter:card" content="summary">
<title>Prashant Bhutani - Porfolio</title><script defer="defer" src="/portfolio/static/js/main.2ffa87cb.js"></script>
<link href="/portfolio/static/css/main.fdf992df.css" rel="stylesheet"><style></style>
<style type="text/css">
.marquee-container {
  overflow-x: hidden !important;
  display: flex !important;
  flex-direction: row !important;
  position: relative;
  width: 100%;
}
.marquee-container:hover div {
  animation-play-state: var(--pause-on-hover);
}
.marquee-container:active div {
  animation-play-state: var(--pause-on-click);
}

.overlay {
  position: absolute;
  width: 100%;
  height: 100%;
}
.overlay::before, .overlay::after {
  background: linear-gradient(to right, var(--gradient-color));
  content: "";
  height: 100%;
  position: absolute;
  width: var(--gradient-width);
  z-index: 2;
}
.overlay::after {
  right: 0;
  top: 0;
  transform: rotateZ(180deg);
}
.overlay::before {
  left: 0;
  top: 0;
}

.marquee {
  flex: 0 0 auto;
  min-width: 100%;
  z-index: 1;
  display: flex;
  flex-direction: row;
  align-items: center;
  animation: scroll var(--duration) linear var(--delay) var(--iteration-count);
  animation-play-state: var(--play);
  animation-delay: var(--delay);
  animation-direction: var(--direction);
}
@keyframes scroll {
  0% {
    transform: translateX(0%);
  }
  100% {
    transform: translateX(-100%);
  }
}</style>
<style data-jss="" data-meta="MuiDrawer">
.MuiDrawer-docked {
  flex: 0 0 auto;
}
.MuiDrawer-paper {
  top: 0;
  flex: 1 0 auto;
  height: 100%;
  display: flex;
  outline: 0;
  z-index: 1200;
  position: fixed;
  overflow-y: auto;
  flex-direction: column;
  -webkit-overflow-scrolling: touch;
}
.MuiDrawer-paperAnchorLeft {
  left: 0;
  right: auto;
}
.MuiDrawer-paperAnchorRight {
  left: auto;
  right: 0;
}
.MuiDrawer-paperAnchorTop {
  top: 0;
  left: 0;
  right: 0;
  bottom: auto;
  height: auto;
  max-height: 100%;
}
.MuiDrawer-paperAnchorBottom {
  top: auto;
  left: 0;
  right: 0;
  bottom: 0;
  height: auto;
  max-height: 100%;
}
.MuiDrawer-paperAnchorDockedLeft {
  border-right: 1px solid rgba(0, 0, 0, 0.12);
}
.MuiDrawer-paperAnchorDockedTop {
  border-bottom: 1px solid rgba(0, 0, 0, 0.12);
}
.MuiDrawer-paperAnchorDockedRight {
  border-left: 1px solid rgba(0, 0, 0, 0.12);
}
.MuiDrawer-paperAnchorDockedBottom {
  border-top: 1px solid rgba(0, 0, 0, 0.12);
}
</style><style data-jss="" data-meta="MuiTouchRipple">
.MuiTouchRipple-root {
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 0;
  overflow: hidden;
  position: absolute;
  border-radius: inherit;
  pointer-events: none;
}
.MuiTouchRipple-ripple {
  opacity: 0;
  position: absolute;
}
.MuiTouchRipple-rippleVisible {
  opacity: 0.3;
  animation: MuiTouchRipple-keyframes-enter 550ms cubic-bezier(0.4, 0, 0.2, 1);
  transform: scale(1);
}
.MuiTouchRipple-ripplePulsate {
  animation-duration: 200ms;
}
.MuiTouchRipple-child {
  width: 100%;
  height: 100%;
  display: block;
  opacity: 1;
  border-radius: 50%;
  background-color: currentColor;
}
.MuiTouchRipple-childLeaving {
  opacity: 0;
  animation: MuiTouchRipple-keyframes-exit 550ms cubic-bezier(0.4, 0, 0.2, 1);
}
.MuiTouchRipple-childPulsate {
  top: 0;
  left: 0;
  position: absolute;
  animation: MuiTouchRipple-keyframes-pulsate 2500ms cubic-bezier(0.4, 0, 0.2, 1) 200ms infinite;
}
@-webkit-keyframes MuiTouchRipple-keyframes-enter {
  0% {
    opacity: 0.1;
    transform: scale(0);
  }
  100% {
    opacity: 0.3;
    transform: scale(1);
  }
}
@-webkit-keyframes MuiTouchRipple-keyframes-exit {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
}
@-webkit-keyframes MuiTouchRipple-keyframes-pulsate {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(0.92);
  }
  100% {
    transform: scale(1);
  }
}
</style><style data-jss="" data-meta="MuiButtonBase">
.MuiButtonBase-root {
  color: inherit;
  border: 0;
  cursor: pointer;
  margin: 0;
  display: inline-flex;
  outline: 0;
  padding: 0;
  position: relative;
  align-items: center;
  user-select: none;
  border-radius: 0;
  vertical-align: middle;
  -moz-appearance: none;
  justify-content: center;
  text-decoration: none;
  background-color: transparent;
  -webkit-appearance: none;
  -webkit-tap-highlight-color: transparent;
}
.MuiButtonBase-root::-moz-focus-inner {
  border-style: none;
}
.MuiButtonBase-root.Mui-disabled {
  cursor: default;
  pointer-events: none;
}
@media print {
  .MuiButtonBase-root {
    -webkit-print-color-adjust: exact;
  }
}
</style><style data-jss="" data-meta="MuiButton">
.MuiButton-root {
  color: rgba(0, 0, 0, 0.87);
  padding: 6px 16px;
  font-size: 0.875rem;
  min-width: 64px;
  box-sizing: border-box;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms,box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms,border 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms;
  font-family: "Roboto", "Helvetica", "Arial", sans-serif;
  font-weight: 500;
  line-height: 1.75;
  border-radius: 4px;
  letter-spacing: 0.02857em;
  text-transform: uppercase;
}
.MuiButton-root:hover {
  text-decoration: none;
  background-color: rgba(0, 0, 0, 0.04);
}
.MuiButton-root.Mui-disabled {
  color: rgba(0, 0, 0, 0.26);
}
@media (hover: none) {
  .MuiButton-root:hover {
    background-color: transparent;
  }
}
.MuiButton-root:hover.Mui-disabled {
  background-color: transparent;
}
.MuiButton-label {
  width: 100%;
  display: inherit;
  align-items: inherit;
  justify-content: inherit;
}
.MuiButton-text {
  padding: 6px 8px;
}
.MuiButton-textPrimary {
  color: #3f51b5;
}
.MuiButton-textPrimary:hover {
  background-color: rgba(63, 81, 181, 0.04);
}
@media (hover: none) {
  .MuiButton-textPrimary:hover {
    background-color: transparent;
  }
}
.MuiButton-textSecondary {
  color: #f50057;
}
.MuiButton-textSecondary:hover {
  background-color: rgba(245, 0, 87, 0.04);
}
@media (hover: none) {
  .MuiButton-textSecondary:hover {
    background-color: transparent;
  }
}
.MuiButton-outlined {
  border: 1px solid rgba(0, 0, 0, 0.23);
  padding: 5px 15px;
}
.MuiButton-outlined.Mui-disabled {
  border: 1px solid rgba(0, 0, 0, 0.12);
}
.MuiButton-outlinedPrimary {
  color: #3f51b5;
  border: 1px solid rgba(63, 81, 181, 0.5);
}
.MuiButton-outlinedPrimary:hover {
  border: 1px solid #3f51b5;
  background-color: rgba(63, 81, 181, 0.04);
}
@media (hover: none) {
  .MuiButton-outlinedPrimary:hover {
    background-color: transparent;
  }
}
.MuiButton-outlinedSecondary {
  color: #f50057;
  border: 1px solid rgba(245, 0, 87, 0.5);
}
.MuiButton-outlinedSecondary:hover {
  border: 1px solid #f50057;
  background-color: rgba(245, 0, 87, 0.04);
}
.MuiButton-outlinedSecondary.Mui-disabled {
  border: 1px solid rgba(0, 0, 0, 0.26);
}
@media (hover: none) {
  .MuiButton-outlinedSecondary:hover {
    background-color: transparent;
  }
}
.MuiButton-contained {
  color: rgba(0, 0, 0, 0.87);
  box-shadow: 0px 3px 1px -2px rgba(0,0,0,0.2),0px 2px 2px 0px rgba(0,0,0,0.14),0px 1px 5px 0px rgba(0,0,0,0.12);
  background-color: #e0e0e0;
}
.MuiButton-contained:hover {
  box-shadow: 0px 2px 4px -1px rgba(0,0,0,0.2),0px 4px 5px 0px rgba(0,0,0,0.14),0px 1px 10px 0px rgba(0,0,0,0.12);
  background-color: #d5d5d5;
}
.MuiButton-contained.Mui-focusVisible {
  box-shadow: 0px 3px 5px -1px rgba(0,0,0,0.2),0px 6px 10px 0px rgba(0,0,0,0.14),0px 1px 18px 0px rgba(0,0,0,0.12);
}
.MuiButton-contained:active {
  box-shadow: 0px 5px 5px -3px rgba(0,0,0,0.2),0px 8px 10px 1px rgba(0,0,0,0.14),0px 3px 14px 2px rgba(0,0,0,0.12);
}
.MuiButton-contained.Mui-disabled {
  color: rgba(0, 0, 0, 0.26);
  box-shadow: none;
  background-color: rgba(0, 0, 0, 0.12);
}
@media (hover: none) {
  .MuiButton-contained:hover {
    box-shadow: 0px 3px 1px -2px rgba(0,0,0,0.2),0px 2px 2px 0px rgba(0,0,0,0.14),0px 1px 5px 0px rgba(0,0,0,0.12);
    background-color: #e0e0e0;
  }
}
.MuiButton-contained:hover.Mui-disabled {
  background-color: rgba(0, 0, 0, 0.12);
}
.MuiButton-containedPrimary {
  color: #fff;
  background-color: #3f51b5;
}
.MuiButton-containedPrimary:hover {
  background-color: #303f9f;
}
@media (hover: none) {
  .MuiButton-containedPrimary:hover {
    background-color: #3f51b5;
  }
}
.MuiButton-containedSecondary {
  color: #fff;
  background-color: #f50057;
}
.MuiButton-containedSecondary:hover {
  background-color: #c51162;
}
@media (hover: none) {
  .MuiButton-containedSecondary:hover {
    background-color: #f50057;
  }
}
.MuiButton-disableElevation {
  box-shadow: none;
}
.MuiButton-disableElevation:hover {
  box-shadow: none;
}
.MuiButton-disableElevation.Mui-focusVisible {
  box-shadow: none;
}
.MuiButton-disableElevation:active {
  box-shadow: none;
}
.MuiButton-disableElevation.Mui-disabled {
  box-shadow: none;
}
.MuiButton-colorInherit {
  color: inherit;
  border-color: currentColor;
}
.MuiButton-textSizeSmall {
  padding: 4px 5px;
  font-size: 0.8125rem;
}
.MuiButton-textSizeLarge {
  padding: 8px 11px;
  font-size: 0.9375rem;
}
.MuiButton-outlinedSizeSmall {
  padding: 3px 9px;
  font-size: 0.8125rem;
}
.MuiButton-outlinedSizeLarge {
  padding: 7px 21px;
  font-size: 0.9375rem;
}
.MuiButton-containedSizeSmall {
  padding: 4px 10px;
  font-size: 0.8125rem;
}
.MuiButton-containedSizeLarge {
  padding: 8px 22px;
  font-size: 0.9375rem;
}
.MuiButton-fullWidth {
  width: 100%;
}
.MuiButton-startIcon {
  display: inherit;
  margin-left: -4px;
  margin-right: 8px;
}
.MuiButton-startIcon.MuiButton-iconSizeSmall {
  margin-left: -2px;
}
.MuiButton-endIcon {
  display: inherit;
  margin-left: 8px;
  margin-right: -4px;
}
.MuiButton-endIcon.MuiButton-iconSizeSmall {
  margin-right: -2px;
}
.MuiButton-iconSizeSmall > *:first-child {
  font-size: 18px;
}
.MuiButton-iconSizeMedium > *:first-child {
  font-size: 20px;
}
.MuiButton-iconSizeLarge > *:first-child {
  font-size: 22px;
}
</style><style data-jss="" data-meta="MuiSnackbar">
.MuiSnackbar-root {
  left: 8px;
  right: 8px;
  display: flex;
  z-index: 1400;
  position: fixed;
  align-items: center;
  justify-content: center;
}
.MuiSnackbar-anchorOriginTopCenter {
  top: 8px;
}
@media (min-width:600px) {
  .MuiSnackbar-anchorOriginTopCenter {
    top: 24px;
    left: 50%;
    right: auto;
    transform: translateX(-50%);
  }
}
.MuiSnackbar-anchorOriginBottomCenter {
  bottom: 8px;
}
@media (min-width:600px) {
  .MuiSnackbar-anchorOriginBottomCenter {
    left: 50%;
    right: auto;
    bottom: 24px;
    transform: translateX(-50%);
  }
}
.MuiSnackbar-anchorOriginTopRight {
  top: 8px;
  justify-content: flex-end;
}
@media (min-width:600px) {
  .MuiSnackbar-anchorOriginTopRight {
    top: 24px;
    left: auto;
    right: 24px;
  }
}
.MuiSnackbar-anchorOriginBottomRight {
  bottom: 8px;
  justify-content: flex-end;
}
@media (min-width:600px) {
  .MuiSnackbar-anchorOriginBottomRight {
    left: auto;
    right: 24px;
    bottom: 24px;
  }
}
.MuiSnackbar-anchorOriginTopLeft {
  top: 8px;
  justify-content: flex-start;
}
@media (min-width:600px) {
  .MuiSnackbar-anchorOriginTopLeft {
    top: 24px;
    left: 24px;
    right: auto;
  }
}
.MuiSnackbar-anchorOriginBottomLeft {
  bottom: 8px;
  justify-content: flex-start;
}
@media (min-width:600px) {
  .MuiSnackbar-anchorOriginBottomLeft {
    left: 24px;
    right: auto;
    bottom: 24px;
  }
}
</style><style data-jss="" data-meta="makeStyles">
.jss35 {
  color: #eaeaea;
  font-size: 3rem;
}
</style><style data-jss="" data-meta="makeStyles">
.jss37 {
  color: #eaeaea;
  font-size: 3rem;
}
</style><style data-jss="" data-meta="makeStyles">
.jss39 {
  color: #eaeaea;
  font-size: 3rem;
}
</style><style data-jss="" data-meta="makeStyles">
.jss41 {
  color: #eaeaea;
  font-size: 3rem;
}
</style><style data-jss="" data-meta="makeStyles">
.jss75 {
  color: #eaeaea;
  cursor: pointer;
  font-size: 2.5rem;
  transform: translateY(-10px);
  transition: color 0.3s;
}
.jss75:hover {
  color: #3fc337;
}
@media (max-width:959.95px) {
  .jss75 {
    font-size: 2.5rem;
  }
}
@media (max-width:599.95px) {
  .jss75 {
    font-size: 2rem;
  }
}
.jss76 {
  width: 14em;
  padding: 0em 1.8em;
  overflow: hidden;
  font-size:  24px;
  background: #212121;
  font-style:  normal;
  font-family:  var(--primaryFont);
  font-weight:  normal;
  border-top-right-radius: 40px;
  border-bottom-right-radius: 40px;
}
@media (max-width:959.95px) {
  .jss76 {
    width: 12em;
  }
}
.jss77 {
  top: 40px;
  color: #3fc337;
  right: 40px;
  cursor: pointer;
  position: absolute;
  font-size: 2rem;
  transition: color 0.2s;
  font-weight: bold;
}
.jss77:hover {
  color: #eaeaea;
}
@media (max-width:959.95px) {
  .jss77 {
    top: 20px;
    right: 20px;
  }
}
.jss78 {
  color: #3fc337;
  width: 85%;
  border: 2px solid;
  height: 60px;
  margin: 2rem auto;
  display: flex;
  padding: 0 30px;
  background: #212121;
  box-sizing: border-box;
  transition: background-color 0.2s, color 0.2s;
  align-items: center;
  border-color: #3fc337;
  border-radius: 78.8418px;
  justify-content: space-evenly;
}
.jss78:hover {
  color: #212121;
  background: #3fc337;
}
@media (max-width:959.95px) {
  .jss78 {
    width: 100%;
    height: 55px;
    padding: 0 25px;
  }
}
.jss79 {
  width: 50%;
  font-size: 1.3rem;
  font-family: var(--primaryFont);
  font-weight: 600;
}
@media (max-width:959.95px) {
  .jss79 {
    font-size: 1.125rem;
  }
}
.jss80 {
  font-size: 1.6rem;
}
@media (max-width:959.95px) {
  .jss80 {
    font-size: 1.385rem;
  }
}
</style><style data-jss="" data-meta="makeStyles">
.jss81 {
  color: #3fc337;
  width: 150px;
  border: 3px solid #3fc337;
  height: 50px;
  font-size: 1rem;
  transition: 100ms ease-out;
  font-family: var(--primaryFont);
  font-weight: 500;
  border-radius: 30px;
  text-transform: inherit;
  text-decoration: none;
}
.jss81:hover {
  color: #212121;
  border: 3px solid #eaeaea;
  background-color: #eaeaea;
}
@media (max-width:959.95px) {
  .jss81 {
    width: 180px;
  }
}
.jss82 {
  color: #212121;
  width: 150px;
  border: 3px solid #3fc337;
  height: 50px;
  font-size: 1rem;
  transition: 100ms ease-out;
  font-family: var(--primaryFont);
  font-weight: 500;
  border-radius: 30px;
  text-transform: inherit;
  text-decoration: none;
  background-color: #3fc337;
}
.jss82:hover {
  color: #eaeaea;
  border: 3px solid #eaeaea;
  background-color: #212121;
}
@media (max-width:959.95px) {
  .jss82 {
    display: none;
  }
}
</style><style data-jss="" data-meta="makeStyles">
.jss83 {
  background-color: #3fc3374d;
}
.jss83:hover {
  background-color: #3fc33780;
}
</style><style data-jss="" data-meta="makeStyles">
.jss84 {
  background-color: #3fc3374d;
}
.jss84:hover {
  background-color: #3fc33780;
}
</style><style data-jss="" data-meta="makeStyles">
.jss85 {
  background-color: #3fc3374d;
}
.jss85:hover {
  background-color: #3fc33780;
}
</style><style data-jss="" data-meta="makeStyles">
.jss86 {
  background-color: #3fc3374d;
}
.jss86:hover {
  background-color: #3fc33780;
}
</style><style data-jss="" data-meta="makeStyles">
.jss87 {
  background-color: #3fc3374d;
}
.jss87:hover {
  background-color: #3fc33780;
}
</style><style data-jss="" data-meta="makeStyles">
.jss88 {
  color: #eaeaea;
  transition: color 0.2s;
  background-color: #3fc337;
}
.jss88:hover {
  color: #212121;
  background-color: #3fc337;
}
.jss89 {
  color: #eaeaea;
  width: 40px;
  cursor: pointer;
  height: 40px;
  padding: 0.5rem;
  font-size: 1.05rem;
  transition: background-color 0.2s;
  border-radius: 50%;
  background-color: #212121b3;
}
.jss89:hover {
  color: #eaeaea;
  background-color: #212121;
}
</style><style data-jss="" data-meta="makeStyles">
.jss90 {
  color: #eaeaea;
  width: 40px;
  border: 2px solid #eaeaea;
  height: 40px;
  display: flex;
  transition: all 0.2s;
  align-items: center;
  border-radius: 50px;
  justify-content: center;
}
.jss90:hover {
  color: #3fc337;
  border: 2px solid #212121;
  transform: scale(1.1);
  background-color: #212121;
}
.jss91 {
  font-size: 1.1rem;
  transition: all 0.2s;
}
</style><style data-jss="" data-meta="makeStyles">
.jss92 {
  color: #eaeaea;
  width: 40px;
  border: 2px solid #eaeaea;
  height: 40px;
  display: flex;
  transition: all 0.2s;
  align-items: center;
  border-radius: 50px;
  justify-content: center;
}
.jss92:hover {
  color: #3fc337;
  border: 2px solid #212121;
  transform: scale(1.1);
  background-color: #212121;
}
.jss93 {
  font-size: 1.1rem;
  transition: all 0.2s;
}
</style><style data-jss="" data-meta="makeStyles">
.jss94 {
  color: #eaeaea;
  width: 40px;
  border: 2px solid #eaeaea;
  height: 40px;
  display: flex;
  transition: all 0.2s;
  align-items: center;
  border-radius: 50px;
  justify-content: center;
}
.jss94:hover {
  color: #3fc337;
  border: 2px solid #212121;
  transform: scale(1.1);
  background-color: #212121;
}
.jss95 {
  font-size: 1.1rem;
  transition: all 0.2s;
}
</style><style data-jss="" data-meta="makeStyles">
.jss96 {
  background-color: #3fc3374d;
}
.jss96:hover {
  background-color: #3fc33780;
}
</style><style data-jss="" data-meta="makeStyles">
.jss97 {
  background-color: #3fc3374d;
}
.jss97:hover {
  background-color: #3fc33780;
}
</style><style data-jss="" data-meta="makeStyles">
.jss98 {
  background-color: #3fc3374d;
}
.jss98:hover {
  background-color: #3fc33780;
}
</style><style data-jss="" data-meta="makeStyles">
.jss99 {
  color: #eaeaea;
  background-color: #3fc337;
}
.jss99:hover {
  color: #212121;
  background-color: #3fc337;
}
.jss100 {
  color: #eaeaea;
  width: 40px;
  cursor: pointer;
  height: 40px;
  padding: 0.5rem;
  font-size: 1.05rem;
  border-radius: 50%;
  background-color: #212121b3;
}
.jss100:hover {
  color: #eaeaea;
  background-color: #212121;
}
</style><style data-jss="" data-meta="makeStyles">
.jss101 {
  color: #eaeaea;
  border: 4px solid #3fc337cc;
  transition: border 0.2s ease-in-out;
  font-family: var(--primaryFont);
  font-weight: 500;
  background-color: #212121;
}
.jss101:focus {
  border: 4px solid #29c51f;
}
.jss102 {
  color: #eaeaea;
  border: 4px solid #3fc337cc;
  transition: border 0.2s ease-in-out;
  font-family: var(--primaryFont);
  font-weight: 500;
  background-color: #212121;
}
.jss102:focus {
  border: 4px solid #29c51f;
}
.jss103 {
  color: #3fc337;
  display: inline-flex;
  padding: 0 5px;
  font-size: 0.9rem;
  transform: translate(25px,50%);
  font-family: var(--primaryFont);
  font-weight: 600;
  background-color: #212121;
}
.jss104 {
  color: #212121;
  width: 45px;
  height: 45px;
  display: flex;
  font-size: 21px;
  transition: 250ms ease-in-out;
  align-items: center;
  border-radius: 50%;
  justify-content: center;
  background-color: #3fc337;
}
.jss104:hover {
  color: #212121;
  transform: scale(1.1);
  background-color: #eaeaea;
}
.jss105 {
  color: #212121;
  width: 45px;
  height: 45px;
  display: flex;
  font-size: 23px;
  transition: 250ms ease-in-out;
  align-items: center;
  flex-shrink: 0;
  border-radius: 50%;
  justify-content: center;
  background-color: #3fc337;
}
.jss105:hover {
  color: #212121;
  transform: scale(1.1);
  background-color: #eaeaea;
}
.jss106 {
  color: #212121;
  transition: 250ms ease-in-out;
  background-color: #3fc337;
}
.jss106:hover {
  color: #212121;
  transform: scale(1.08);
  background-color: #eaeaea;
}
</style><style data-jss="" data-meta="makeStyles">
.jss109 {
  color: #eaeaea;
  font-size: 3rem;
}
</style><style data-jss="" data-meta="makeStyles">
.jss111 {
  color: #eaeaea;
  font-size: 3rem;
}
</style><style data-jss="" data-meta="makeStyles">
.jss113 {
  color: #eaeaea;
  font-size: 3rem;
}
</style><style data-jss="" data-meta="makeStyles">
.jss114 {
  color: #eaeaea;
  font-size: 3rem;
}
</style><style data-jss="" data-meta="makeStyles">
.jss115 {
  color: #eaeaea;
  font-size: 3rem;
}
</style></head><body data-new-gr-c-s-check-loaded="14.1152.0" data-gr-ext-installed=""><noscript>You need to enable JavaScript to run this app.</noscript><div id="root"><div class="app"><div><div class="navbar"><div class="navbar--container"><h1 style="color: rgb(33, 33, 33);">Prashant</h1><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" class="jss75" aria-label="Menu" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M64 384h384v-42.67H64zm0-106.67h384v-42.66H64zM64 128v42.67h384V128z"></path></svg></div></div><div class="landing"><div class="landing--container"><div class="landing--container-left" style="background-color: rgb(63, 195, 55);"><div class="lcl--content"><a href="https://www.linkedin.com/in/prashantbhutani" target="_blank" rel="noreferrer"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 448 512" class="landing--social" aria-label="LinkedIn" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg" style="color: rgb(33, 33, 33);"><path d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z"></path></svg></a><a href="https://github.com/prabhutani" target="_blank" rel="noreferrer"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 496 512" class="landing--social" aria-label="GitHub" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg" style="color: rgb(33, 33, 33);"><path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"></path></svg></a></div></div><img src="/portfolio/static/media/potrait.10bf3817c41a2d013922.jpg" alt="" class="landing--img" style="opacity: 1; border-color: rgb(33, 33, 33);"><div class="landing--container-right" style="background-color: rgb(33, 33, 33);"><div class="lcr--content" style="color: rgb(234, 234, 234);"><h6>Software Engineer/Graduate Student</h6><h1>Prashant Bhutani</h1><p>Amidst the bustling city's hum and din, He stood, with eyes fixed on the skyline. Determined, purposeful, his heart within Embraced the challenges ahead as a sign. For he knew, through hardships and strife, He'd grow stronger, better equipped for life. </p><p></p><p></p><p></p><p></p><p></p><div class="lcr-buttonContainer"><a href="/portfolio/static/media/resume.d04061a2cfb97068eb09.pdf" download="resume" target="_blank" rel="noreferrer"><button class="MuiButtonBase-root MuiButton-root MuiButton-text jss81" tabindex="0" type="button"><span class="MuiButton-label">Download CV</span><span class="MuiTouchRipple-root"></span></button></a><a spy="true" duration="2000" href="/#contacts"><button class="MuiButtonBase-root MuiButton-root MuiButton-text jss82" tabindex="0" type="button"><span class="MuiButton-label">Contact</span><span class="MuiTouchRipple-root"></span></button></a></div></div></div></div></div><div class="about" id="about" style="background-color: rgb(33, 33, 33);"><div class="line-styling"><div class="style-circle" style="background-color: rgb(63, 195, 55);"></div><div class="style-circle" style="background-color: rgb(63, 195, 55);"></div><div class="style-line" style="background-color: rgb(63, 195, 55);"></div></div><div class="about-body"><div class="about-description"><h2 style="color: rgb(63, 195, 55);">Who I am</h2><p style="color: rgba(234, 234, 234, 0.8);">My name is Prashant. I'm a Computer Science Graduate Student and an Experienced Software Engineer based in Chicago, IL.<br><br>I have over 3 years of professional work experience.
 During my career I have built products helping Big 4 US &amp; UK Banks to leverage technology ensuring efficient operations at scale.
 I am currently looking to work at entry or mid-level Software Engineering roles as I gradute with a Masters in Computer Science.</p></div><div class="about-img"><img src="/portfolio/static/media/greenTheme-boy.7d67734f0cfec86072445c75c9252df5.svg" alt=""></div></div></div><div class="education" id="resume" style="background-color: rgb(33, 33, 33);"><div class="education-body"><div class="education-description"><h1 style="color: rgb(63, 195, 55);">Education</h1><div class="react-reveal education-card jss83" style="animation-fill-mode: both; animation-duration: 1000ms; animation-delay: 0ms; animation-iteration-count: 1; opacity: 1; animation-name: react-reveal-671048430839742-1;"><div class="educard-img" style="background-color: rgb(63, 195, 55);"><img src="/portfolio/static/media/eduImgWhite.433f9250502a8b9b87ba754528481d86.svg" alt=""></div><div class="education-details"><h6 style="color: rgb(63, 195, 55);">2015-2019</h6><h4 style="color: rgb(234, 234, 234);">Bachelor of Technology</h4><h5 style="color: rgba(234, 234, 234, 0.8);">Jaypee Institute of Informtaion Technology, India</h5></div></div><div class="react-reveal education-card jss84" style="animation-fill-mode: both; animation-duration: 1000ms; animation-delay: 0ms; animation-iteration-count: 1; opacity: 1; animation-name: react-reveal-671048430839742-1;"><div class="educard-img" style="background-color: rgb(63, 195, 55);"><img src="/portfolio/static/media/eduImgWhite.433f9250502a8b9b87ba754528481d86.svg" alt=""></div><div class="education-details"><h6 style="color: rgb(63, 195, 55);">2021-2023</h6><h4 style="color: rgb(234, 234, 234);">Master of Computer Science</h4><h5 style="color: rgba(234, 234, 234, 0.8);">Illinois Institute of Technology</h5></div></div></div><div class="education-image"><img src="/portfolio/static/media/eduGreen.3fe155447d7d12afc637edc0933c8d8e.svg" alt=""></div></div></div><div class="skills" id="skills" style="background-color: rgb(33, 33, 33);"><div class="skillsHeader"><h2 style="color: rgb(63, 195, 55);">Skills</h2></div><div class="skillsContainer"><div class="skill--scroll"><div class=" marquee-container" style="--pause-on-hover: paused; --pause-on-click: paused;"><div class="marquee" style="--play: running; --direction: normal; --duration: 31.2s; --delay: 0s; --iteration-count: infinite;"><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/html.75bdf0b057c088503944680032ea6347.svg" alt="HTML"><h3 style="color: rgb(234, 234, 234);">HTML</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/css.afb434f6d712d3e4ff53be8da4d9876a.svg" alt="CSS"><h3 style="color: rgb(234, 234, 234);">CSS</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/json.5a49a284f24dec258df0.png" alt="JSON"><h3 style="color: rgb(234, 234, 234);">JSON</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/yaml.51a193e7483400d8f3a0.png" alt="YAML"><h3 style="color: rgb(234, 234, 234);">YAML</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/react.c3a0b34aae466451a91157424eec1ee3.svg" alt="React"><h3 style="color: rgb(234, 234, 234);">React</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/typescript.f66836b8961d019a6f633b3c89b0c2ad.svg" alt="Typescript"><h3 style="color: rgb(234, 234, 234);">Typescript</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/javascript.f84ec7103324dc7e616d00ed43ecd531.svg" alt="Javascript"><h3 style="color: rgb(234, 234, 234);">Javascript</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/python.0934792163d56e233fb5f42cc69d7ed1.svg" alt="Python"><h3 style="color: rgb(234, 234, 234);">Python</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/java.e9ccff93b0aa1395d35e7c0ba529ac54.svg" alt="Java"><h3 style="color: rgb(234, 234, 234);">Java</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/cplusplus.3b0d7340ed9a40a744043d23ffa5ebe1.svg" alt="C++"><h3 style="color: rgb(234, 234, 234);">C++</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/figma.cc8e111619371cf586cc11dbd3173da0.svg" alt="Figma"><h3 style="color: rgb(234, 234, 234);">Figma</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/elasticsearch.e53978a0b1d24a189f50.png" alt="ElasticStack"><h3 style="color: rgb(234, 234, 234);">ElasticStack</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/postgresql.f0f3d0b9f02ed22418fc182be982a49c.svg" alt="PostgreSQL"><h3 style="color: rgb(234, 234, 234);">PostgreSQL</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/mongoDB.4428e2ce754003752672dce4c3d81b9d.svg" alt="MongoDB"><h3 style="color: rgb(234, 234, 234);">MongoDB</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/git.2d7df16e58dae6c26bba033ee2e8c4d8.svg" alt="Git"><h3 style="color: rgb(234, 234, 234);">Git</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/nginx.63e0789fac1cc3a927c53707fadcd312.svg" alt="nginx"><h3 style="color: rgb(234, 234, 234);">nginx</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/docker.26ada6e465df47e1423793e7e41f43ba.svg" alt="Docker"><h3 style="color: rgb(234, 234, 234);">Docker</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/kubernetes.56c7b55c70184ff7fce5.png" alt="Kubernetes"><h3 style="color: rgb(234, 234, 234);">Kubernetes</h3></div></div><div class="marquee" aria-hidden="true" style="--play: running; --direction: normal; --duration: 31.2s; --delay: 0s; --iteration-count: infinite;"><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/html.75bdf0b057c088503944680032ea6347.svg" alt="HTML"><h3 style="color: rgb(234, 234, 234);">HTML</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/css.afb434f6d712d3e4ff53be8da4d9876a.svg" alt="CSS"><h3 style="color: rgb(234, 234, 234);">CSS</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/json.5a49a284f24dec258df0.png" alt="JSON"><h3 style="color: rgb(234, 234, 234);">JSON</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/yaml.51a193e7483400d8f3a0.png" alt="YAML"><h3 style="color: rgb(234, 234, 234);">YAML</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/react.c3a0b34aae466451a91157424eec1ee3.svg" alt="React"><h3 style="color: rgb(234, 234, 234);">React</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/typescript.f66836b8961d019a6f633b3c89b0c2ad.svg" alt="Typescript"><h3 style="color: rgb(234, 234, 234);">Typescript</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/javascript.f84ec7103324dc7e616d00ed43ecd531.svg" alt="Javascript"><h3 style="color: rgb(234, 234, 234);">Javascript</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/python.0934792163d56e233fb5f42cc69d7ed1.svg" alt="Python"><h3 style="color: rgb(234, 234, 234);">Python</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/java.e9ccff93b0aa1395d35e7c0ba529ac54.svg" alt="Java"><h3 style="color: rgb(234, 234, 234);">Java</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/cplusplus.3b0d7340ed9a40a744043d23ffa5ebe1.svg" alt="C++"><h3 style="color: rgb(234, 234, 234);">C++</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/figma.cc8e111619371cf586cc11dbd3173da0.svg" alt="Figma"><h3 style="color: rgb(234, 234, 234);">Figma</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/elasticsearch.e53978a0b1d24a189f50.png" alt="ElasticStack"><h3 style="color: rgb(234, 234, 234);">ElasticStack</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/postgresql.f0f3d0b9f02ed22418fc182be982a49c.svg" alt="PostgreSQL"><h3 style="color: rgb(234, 234, 234);">PostgreSQL</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/mongoDB.4428e2ce754003752672dce4c3d81b9d.svg" alt="MongoDB"><h3 style="color: rgb(234, 234, 234);">MongoDB</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/git.2d7df16e58dae6c26bba033ee2e8c4d8.svg" alt="Git"><h3 style="color: rgb(234, 234, 234);">Git</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/nginx.63e0789fac1cc3a927c53707fadcd312.svg" alt="nginx"><h3 style="color: rgb(234, 234, 234);">nginx</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/docker.26ada6e465df47e1423793e7e41f43ba.svg" alt="Docker"><h3 style="color: rgb(234, 234, 234);">Docker</h3></div><div class="skill--box" style="background-color: rgb(33, 33, 33); box-shadow: rgba(63, 195, 55, 0.3) 0px 0px 30px;"><img src="/portfolio/static/media/kubernetes.56c7b55c70184ff7fce5.png" alt="Kubernetes"><h3 style="color: rgb(234, 234, 234);">Kubernetes</h3></div></div></div></div></div></div><div class="experience" id="experience" style="background-color: rgb(33, 33, 33);"><div class="experience-body"><div class="experience-image"><img src="/portfolio/static/media/expGreen.16b06cc584dc9f60d8200ab5e3366036.svg" alt=""></div><div class="experience-description"><h1 style="color: rgb(63, 195, 55);">Experience</h1><div class="react-reveal experience-card jss85" style="animation-fill-mode: both; animation-duration: 1000ms; animation-delay: 0ms; animation-iteration-count: 1; opacity: 1; animation-name: react-reveal-671048430839742-1;"><div class="expcard-img" style="background-color: rgb(63, 195, 55);"><img src="/portfolio/static/media/expImgWhite.b9923db466bf4544f6942bc67c5b4a7b.svg" alt=""></div><div class="experience-details"><h6 style="color: rgb(63, 195, 55);">2019-2020</h6><h4 style="color: rgb(234, 234, 234);">Software Developer</h4><h5 style="color: rgba(234, 234, 234, 0.8);">Tata Consultancy Services Ltd.</h5></div></div><div class="react-reveal experience-card jss86" style="animation-fill-mode: both; animation-duration: 1000ms; animation-delay: 0ms; animation-iteration-count: 1; opacity: 1; animation-name: react-reveal-671048430839742-1;"><div class="expcard-img" style="background-color: rgb(63, 195, 55);"><img src="/portfolio/static/media/expImgWhite.b9923db466bf4544f6942bc67c5b4a7b.svg" alt=""></div><div class="experience-details"><h6 style="color: rgb(63, 195, 55);">2020-2021</h6><h4 style="color: rgb(234, 234, 234);">Software Engineer</h4><h5 style="color: rgba(234, 234, 234, 0.8);">Lloyds Banking Group Plc</h5></div></div><div class="react-reveal experience-card jss87" style="animation-fill-mode: both; animation-duration: 1000ms; animation-delay: 0ms; animation-iteration-count: 1; opacity: 1; animation-name: react-reveal-671048430839742-1;"><div class="expcard-img" style="background-color: rgb(63, 195, 55);"><img src="/portfolio/static/media/expImgWhite.b9923db466bf4544f6942bc67c5b4a7b.svg" alt=""></div><div class="experience-details"><h6 style="color: rgb(63, 195, 55);">2022-2023</h6><h4 style="color: rgb(234, 234, 234);">Software Developer &amp; Grad TA - Enterprise Web Dev &amp; Information Security</h4><h5 style="color: rgba(234, 234, 234, 0.8);">Illinois Institute of Technology</h5></div></div></div></div></div><div class="projects" id="projects" style="background-color: rgb(33, 33, 33);"><div class="projects--header"><h1 style="color: rgb(63, 195, 55);">Projects</h1></div><div class="projects--body"><div class="projects--bodyContainer"><div class="react-reveal singleProject" style="background-color: rgb(87, 215, 80); animation-fill-mode: both; animation-duration: 1000ms; animation-delay: 0ms; animation-iteration-count: 1; opacity: 1; animation-name: react-reveal-671048430839742-1;"><div class="projectContent"><h2 id="cyberposter" style="color: rgb(234, 234, 234);">Cyberposter</h2><img src="/portfolio/static/media/one.9ac983ad8f730af44014d704fa53a700.svg" alt="Cyberposter"><div class="project--showcaseBtn"><a href="https://prabhutani.github.io/Robofriends/" target="_blank" rel="noreferrer" class="jss90" aria-labelledby="cyberposter cyberposter-demo"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 448 512" id="cyberposter-demo" class="jss91" aria-label="Demo" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M424.4 214.7L72.4 6.6C43.8-10.3 0 6.1 0 47.9V464c0 37.5 40.7 60.1 72.4 41.3l352-208c31.4-18.5 31.5-64.1 0-82.6z"></path></svg></a><a href="https://github.com/prabhutani/Robofriends" target="_blank" rel="noreferrer" class="jss90" aria-labelledby="cyberposter cyberposter-code"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 640 512" id="cyberposter-code" class="jss91" aria-label="Code" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M278.9 511.5l-61-17.7c-6.4-1.8-10-8.5-8.2-14.9L346.2 8.7c1.8-6.4 8.5-10 14.9-8.2l61 17.7c6.4 1.8 10 8.5 8.2 14.9L293.8 503.3c-1.9 6.4-8.5 10.1-14.9 8.2zm-114-112.2l43.5-46.4c4.6-4.9 4.3-12.7-.8-17.2L117 256l90.6-79.7c5.1-4.5 5.5-12.3.8-17.2l-43.5-46.4c-4.5-4.8-12.1-5.1-17-.5L3.8 247.2c-5.1 4.7-5.1 12.8 0 17.5l144.1 135.1c4.9 4.6 12.5 4.4 17-.5zm327.2.6l144.1-135.1c5.1-4.7 5.1-12.8 0-17.5L492.1 112.1c-4.8-4.5-12.4-4.3-17 .5L431.6 159c-4.6 4.9-4.3 12.7.8 17.2L523 256l-90.6 79.7c-5.1 4.5-5.5 12.3-.8 17.2l43.5 46.4c4.5 4.9 12.1 5.1 17 .6z"></path></svg></a></div></div><p class="project--desc" style="background: rgb(33, 33, 33); color: rgb(234, 234, 234);">The application demonstrates common attacks on distributed systems and their countermeasures just by toggling security features on and off</p><div class="project--lang" style="background: rgb(33, 33, 33); color: rgba(234, 234, 234, 0.8);"><span>React</span><span>Express</span><span>AWS EC2</span><span>API Gateway</span><span>JWT</span><span>Rate Limitter</span></div></div><div class="react-reveal singleProject" style="background-color: rgb(87, 215, 80); animation-fill-mode: both; animation-duration: 1000ms; animation-delay: 0ms; animation-iteration-count: 1; opacity: 1; animation-name: react-reveal-671048430839742-1;"><div class="projectContent"><h2 id="grocery-hub" style="color: rgb(234, 234, 234);">Grocery Hub</h2><img src="/portfolio/static/media/two.4b4e9d26cc5158497835d2d88bcf4cf7.svg" alt="Grocery Hub"><div class="project--showcaseBtn"><a href="https://github.com/prabhutani/Groceryhub" target="_blank" rel="noreferrer" class="jss92" aria-labelledby="grocery-hub grocery-hub-demo"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 448 512" id="grocery-hub-demo" class="jss93" aria-label="Demo" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M424.4 214.7L72.4 6.6C43.8-10.3 0 6.1 0 47.9V464c0 37.5 40.7 60.1 72.4 41.3l352-208c31.4-18.5 31.5-64.1 0-82.6z"></path></svg></a><a href="https://github.com/prabhutani/Groceryhub" target="_blank" rel="noreferrer" class="jss92" aria-labelledby="grocery-hub grocery-hub-code"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 640 512" id="grocery-hub-code" class="jss93" aria-label="Code" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M278.9 511.5l-61-17.7c-6.4-1.8-10-8.5-8.2-14.9L346.2 8.7c1.8-6.4 8.5-10 14.9-8.2l61 17.7c6.4 1.8 10 8.5 8.2 14.9L293.8 503.3c-1.9 6.4-8.5 10.1-14.9 8.2zm-114-112.2l43.5-46.4c4.6-4.9 4.3-12.7-.8-17.2L117 256l90.6-79.7c5.1-4.5 5.5-12.3.8-17.2l-43.5-46.4c-4.5-4.8-12.1-5.1-17-.5L3.8 247.2c-5.1 4.7-5.1 12.8 0 17.5l144.1 135.1c4.9 4.6 12.5 4.4 17-.5zm327.2.6l144.1-135.1c5.1-4.7 5.1-12.8 0-17.5L492.1 112.1c-4.8-4.5-12.4-4.3-17 .5L431.6 159c-4.6 4.9-4.3 12.7.8 17.2L523 256l-90.6 79.7c-5.1 4.5-5.5 12.3-.8 17.2l43.5 46.4c4.5 4.9 12.1 5.1 17 .6z"></path></svg></a></div></div><p class="project--desc" style="background: rgb(33, 33, 33); color: rgb(234, 234, 234);">An online grocey shopping platform offering home delivery and pickup orders</p><div class="project--lang" style="background: rgb(33, 33, 33); color: rgba(234, 234, 234, 0.8);"><span>React</span><span>Nodejs</span><span>CSS</span><span>Material Ui</span></div></div><div class="react-reveal singleProject" style="background-color: rgb(87, 215, 80); animation-fill-mode: both; animation-duration: 1000ms; animation-delay: 0ms; animation-iteration-count: 1; opacity: 1; animation-name: react-reveal-671048430839742-1;"><div class="projectContent"><h2 id="robo-friends" style="color: rgb(234, 234, 234);">Robo Friends</h2><img src="/portfolio/static/media/three.e7994ba3f5ac40c49e54d43df2db02c9.svg" alt="Robo Friends"><div class="project--showcaseBtn"><a href="https://prabhutani.github.io/Robofriends/" target="_blank" rel="noreferrer" class="jss94" aria-labelledby="robo-friends robo-friends-demo"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 448 512" id="robo-friends-demo" class="jss95" aria-label="Demo" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M424.4 214.7L72.4 6.6C43.8-10.3 0 6.1 0 47.9V464c0 37.5 40.7 60.1 72.4 41.3l352-208c31.4-18.5 31.5-64.1 0-82.6z"></path></svg></a><a href="https://github.com/prabhutani/Robofriends" target="_blank" rel="noreferrer" class="jss94" aria-labelledby="robo-friends robo-friends-code"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 640 512" id="robo-friends-code" class="jss95" aria-label="Code" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M278.9 511.5l-61-17.7c-6.4-1.8-10-8.5-8.2-14.9L346.2 8.7c1.8-6.4 8.5-10 14.9-8.2l61 17.7c6.4 1.8 10 8.5 8.2 14.9L293.8 503.3c-1.9 6.4-8.5 10.1-14.9 8.2zm-114-112.2l43.5-46.4c4.6-4.9 4.3-12.7-.8-17.2L117 256l90.6-79.7c5.1-4.5 5.5-12.3.8-17.2l-43.5-46.4c-4.5-4.8-12.1-5.1-17-.5L3.8 247.2c-5.1 4.7-5.1 12.8 0 17.5l144.1 135.1c4.9 4.6 12.5 4.4 17-.5zm327.2.6l144.1-135.1c5.1-4.7 5.1-12.8 0-17.5L492.1 112.1c-4.8-4.5-12.4-4.3-17 .5L431.6 159c-4.6 4.9-4.3 12.7.8 17.2L523 256l-90.6 79.7c-5.1 4.5-5.5 12.3-.8 17.2l43.5 46.4c4.5 4.9 12.1 5.1 17 .6z"></path></svg></a></div></div><p class="project--desc" style="background: rgb(33, 33, 33); color: rgb(234, 234, 234);">This project is a simple Frontend project using Robo Friends API to demonstrate Responsive React UI</p><div class="project--lang" style="background: rgb(33, 33, 33); color: rgba(234, 234, 234, 0.8);"><span>React</span><span>CSS</span><span>Tachyons</span></div></div></div><div class="projects--viewAll"><a href="/projects"><button class="jss88">View All<svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 20 20" class="jss89" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg></button></a></div></div></div><div class="achievement" id="achievement" style="background-color: rgb(33, 33, 33);"><div class="achievement-body"><h1 style="color: rgb(63, 195, 55);">Achievements</h1><h4 style="color: rgb(234, 234, 234);">I have been relentlessly in my pursuit of knowledge and apply my skills to build products, I am fortunate to have been awarded for my efforts.</h4></div><div class="achievement-cards"><div class="react-reveal achievement-card jss96" style="animation-fill-mode: both; animation-duration: 1000ms; animation-delay: 0ms; animation-iteration-count: 1; opacity: 1; animation-name: react-reveal-671048430839742-1;"><div class="achievecard-content"><div class="achievecard-details1"><h2 style="color: rgb(234, 234, 234);">Winner - Hacknite 2023</h2><p style="color: rgba(234, 234, 234, 0.8);">Won the first prize at Hacknite 2023, annual hackathon hosted at the Illinois Institute of Technology, Chicago</p></div><div class="achievecard-details2" style="color: rgb(63, 195, 55);"><h5>April 20, 2023</h5><div class="achievecard-field"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 1024 1024" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M880 298.4H521L403.7 186.2a8.15 8.15 0 0 0-5.5-2.2H144c-17.7 0-32 14.3-32 32v592c0 17.7 14.3 32 32 32h736c17.7 0 32-14.3 32-32V330.4c0-17.7-14.3-32-32-32zM840 768H184V256h188.5l119.6 114.4H840V768z"></path></svg><h5>Software Development</h5></div></div></div><div class="achievecard-imgcontainer"><img src="/portfolio/static/media/win.2b83e87bb7ecb701baeb.jpg" width="fit" height="auto" style="display: block; margin-left: auto; margin-right: auto;"></div></div><div class="react-reveal achievement-card jss97" style="animation-fill-mode: both; animation-duration: 1000ms; animation-delay: 0ms; animation-iteration-count: 1; opacity: 1; animation-name: react-reveal-671048430839742-1;"><div class="achievecard-content"><div class="achievecard-details1"><h2 style="color: rgb(234, 234, 234);">1st Prize at Kaplan Pitch Tank 2022</h2><p style="color: rgba(234, 234, 234, 0.8);">Built MVP for a Pharma tech startup, which won the first prize (30K USD as seed fund) at Kaplan Pitch Tank 2022.</p></div><div class="achievecard-details2" style="color: rgb(63, 195, 55);"><h5>April, 2022</h5><div class="achievecard-field"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 1024 1024" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M880 298.4H521L403.7 186.2a8.15 8.15 0 0 0-5.5-2.2H144c-17.7 0-32 14.3-32 32v592c0 17.7 14.3 32 32 32h736c17.7 0 32-14.3 32-32V330.4c0-17.7-14.3-32-32-32zM840 768H184V256h188.5l119.6 114.4H840V768z"></path></svg><h5>Technology</h5></div></div></div><div class="achievecard-imgcontainer"><img src="/portfolio/static/media/discreedly.fe2964799c212a482f71.jpg" width="fit" height="auto" style="display: block; margin-left: auto; margin-right: auto;"></div></div><div class="react-reveal achievement-card jss98" style="animation-fill-mode: both; animation-duration: 1000ms; animation-delay: 0ms; animation-iteration-count: 1; opacity: 1; animation-name: react-reveal-671048430839742-1;"><div class="achievecard-content"><div class="achievecard-details1"><h2 style="color: rgb(234, 234, 234);">AWS Certified Cloud Practitioner</h2><p style="color: rgba(234, 234, 234, 0.8);">Learnt various cloud services provided by AWS and how to build solutions with them.</p></div><div class="achievecard-details2" style="color: rgb(63, 195, 55);"><h5>August, 2019</h5><div class="achievecard-field"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 1024 1024" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M880 298.4H521L403.7 186.2a8.15 8.15 0 0 0-5.5-2.2H144c-17.7 0-32 14.3-32 32v592c0 17.7 14.3 32 32 32h736c17.7 0 32-14.3 32-32V330.4c0-17.7-14.3-32-32-32zM840 768H184V256h188.5l119.6 114.4H840V768z"></path></svg><h5>Cloud and DevOps</h5></div></div></div><div class="achievecard-imgcontainer"><img src="https://upload.wikimedia.org/wikipedia/commons/9/93/Amazon_Web_Services_Logo.svg" width="fit" height="auto" style="display: block; margin-left: auto; margin-right: auto;"></div></div></div></div><div class="contacts" id="contacts" style="background-color: rgb(33, 33, 33);"><div class="contacts--container"><h1 style="color: rgb(63, 195, 55);">Contacts</h1><div class="contacts-body"><div class="contacts-form"><form><div class="input-container"><label for="Name" class="jss103">Name</label><input placeholder="Prashant Bhutani" type="text" name="Name" class="form-input jss101" value=""></div><div class="input-container"><label for="Email" class="jss103">Email</label><input placeholder="Prashant@Bhutani.com" type="email" name="Email" class="form-input jss101" value=""></div><div class="input-container"><label for="Message" class="jss103">Message</label><textarea placeholder="Type your message...." type="text" name="Message" class="form-message jss102"></textarea></div><div class="submit-btn"><button type="submit" class="jss106"><p>Send</p><div class="submit-icon"><svg stroke="currentColor" fill="currentColor" stroke-width="0" t="1569683742680" viewBox="0 0 1024 1024" version="1.1" class="send-icon" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg" style="animation: initial; position: initial;"><defs></defs><path d="M931.4 498.9L94.9 79.5c-3.4-1.7-7.3-2.1-11-1.2-8.5 2.1-13.8 10.7-11.7 19.3l86.2 352.2c1.3 5.3 5.2 9.6 10.4 11.3l147.7 50.7-147.6 50.7c-5.2 1.8-9.1 6-10.3 11.3L72.2 926.5c-0.9 3.7-0.5 7.6 1.2 10.9 3.9 7.9 13.5 11.1 21.5 7.2l836.5-417c3.1-1.5 5.6-4.1 7.2-7.1 3.9-8 0.7-17.6-7.2-21.6zM170.8 826.3l50.3-205.6 295.2-101.3c2.3-0.8 4.2-2.6 5-5 1.4-4.2-0.8-8.7-5-10.2L221.1 403 171 198.2l628 314.9-628.2 313.2z"></path></svg><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 1024 1024" class="success-icon" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg" style="display: none; opacity: 0;"><path d="M699 353h-46.9c-10.2 0-19.9 4.9-25.9 13.3L469 584.3l-71.2-98.8c-6-8.3-15.6-13.3-25.9-13.3H325c-6.5 0-10.3 7.4-6.5 12.7l124.6 172.8a31.8 31.8 0 0 0 51.7 0l210.6-292c3.9-5.3.1-12.7-6.4-12.7z"></path><path d="M512 64C264.6 64 64 264.6 64 512s200.6 448 448 448 448-200.6 448-448S759.4 64 512 64zm0 820c-205.4 0-372-166.6-372-372s166.6-372 372-372 372 166.6 372 372-166.6 372-372 372z"></path></svg></div></button></div></form></div><div class="contacts-details"><a href="mailto:pbhutani@hawk.iit.edu" class="personal-details"><div class="jss105"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><circle cx="12" cy="12" r="4"></circle><path d="M16 8v5a3 3 0 0 0 6 0v-1a10 10 0 1 0-3.92 7.94"></path></svg></div><p style="color: rgb(234, 234, 234);">pbhutani@hawk.iit.edu</p></a><a href="tel:+1 312 358 6481" class="personal-details"><div class="jss105"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path></svg></div><p style="color: rgb(234, 234, 234);">+1 312 358 6481</p></a><div class="personal-details"><div class="jss105"><svg stroke="currentColor" fill="none" stroke-width="0" viewBox="0 0 24 24" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg></div><p style="color: rgb(234, 234, 234);">Chicago, IL </p></div><div class="socialmedia-icons"><a href="https://github.com/prabhutani" target="_blank" rel="noreferrer" class="jss104"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 496 512" aria-label="GitHub" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"></path></svg></a><a href="https://www.linkedin.com/in/prashantbhutani" target="_blank" rel="noreferrer" class="jss104"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 448 512" aria-label="LinkedIn" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M100.28 448H7.4V148.9h92.88zM53.79 108.1C24.09 108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 29.7-24.1 54.3-53.79 54.3zM447.9 448h-92.68V302.4c0-34.7-.7-79.2-48.29-79.2-48.29 0-55.69 37.7-55.69 76.7V448h-92.78V148.9h89.08v40.8h1.3c12.4-23.5 42.69-48.3 87.88-48.3 94 0 111.28 61.9 111.28 142.3V448z"></path></svg></a><a href="https://www.leetcode.com/prashantbhutani" target="_blank" rel="noreferrer" class="jss104"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 640 512" aria-label="leetcode" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M278.9 511.5l-61-17.7c-6.4-1.8-10-8.5-8.2-14.9L346.2 8.7c1.8-6.4 8.5-10 14.9-8.2l61 17.7c6.4 1.8 10 8.5 8.2 14.9L293.8 503.3c-1.9 6.4-8.5 10.1-14.9 8.2zm-114-112.2l43.5-46.4c4.6-4.9 4.3-12.7-.8-17.2L117 256l90.6-79.7c5.1-4.5 5.5-12.3.8-17.2l-43.5-46.4c-4.5-4.8-12.1-5.1-17-.5L3.8 247.2c-5.1 4.7-5.1 12.8 0 17.5l144.1 135.1c4.9 4.6 12.5 4.4 17-.5zm327.2.6l144.1-135.1c5.1-4.7 5.1-12.8 0-17.5L492.1 112.1c-4.8-4.5-12.4-4.3-17 .5L431.6 159c-4.6 4.9-4.3 12.7.8 17.2L523 256l-90.6 79.7c-5.1 4.5-5.5 12.3-.8 17.2l43.5 46.4c4.5 4.9 12.1 5.1 17 .6z"></path></svg></a></div></div></div></div><img src="/portfolio/static/media/contactsGreen.47f34fc682de82476b815b925a392d5f.svg" alt="contacts" class="contacts--img"></div><div class="footer" style="background-color: rgb(33, 33, 33);"><p style="color: rgb(234, 234, 234);">Made with<span style="color: rgb(63, 195, 55); margin: 0px 0.5rem -1rem;">❤</span>by Prashant</p></div></div><div class="backToTop" style="display: none;"><button aria-label="Back to top"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" class="jss114" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M256 464c114.9 0 208-93.1 208-208S370.9 48 256 48 48 141.1 48 256s93.1 208 208 208zm0-244.5l-81.1 81.9c-7.5 7.5-19.8 7.5-27.3 0s-7.5-19.8 0-27.3l95.7-95.4c7.3-7.3 19.1-7.5 26.6-.6l94.3 94c3.8 3.8 5.7 8.7 5.7 13.7 0 4.9-1.9 9.9-5.6 13.6-7.5 7.5-19.7 7.6-27.3 0l-81-79.9z"></path></svg></button></div></div></div></body><style>
@media print {
  #simplifyJobsContainer {
    display: none;
  }
}
</style><div id="simplifyJobsContainer" style="position: absolute; top: 0px; left: 0px; width: 0px; height: 0px; overflow: visible; z-index: 2147483647;"><span></span></div><script id="simplifyJobsPageScript" src="chrome-extension://pbanhockgagggenencehbnadejlgchfc/js/pageScript.bundle.js"></script><grammarly-desktop-integration data-grammarly-shadow-root="true"></grammarly-desktop-integration></html>
