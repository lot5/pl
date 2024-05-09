Lampa.Platform.tv();
function log() {
        console.log.apply(console.log, arguments);
      }
log('Hotkeys', 'Hotkeys 171 loaded');

function openPanel(element) {
	if ('parseFloat(Lampa.Manifest.app_version)' >= '1.7') {
        //log('Hotkeys', '1.7.0');
		Lampa.Utils.trigger(document.querySelector(element), 'click');
	} else {
        //log('Hotkeys', 'old version');
		document.querySelector(element).click();
	}
};

function listenDestroy() {
	document.removeEventListener("keydown", listenHotkeys);
	Lampa.Player.listener.remove('destroy', listenDestroy);	
};

function startHotkeys() {
	document.addEventListener("keydown", listenHotkeys);
	Lampa.Player.listener.follow('destroy', listenDestroy);
};

function listenHotkeys(e) {

//log('Hotkeys', e.keyCode);
	
  if (e.keyCode === 166 || e.keyCode === 427 || e.keyCode === 27 || e.keyCode === 33) {
	openPanel('.player-panel__next.button.selector');
  }

  if (e.keyCode === 167 || e.keyCode === 428 || e.keyCode === 28 || e.keyCode === 34) {
	openPanel('.player-panel__prev.button.selector');
  }
	
  if (e.keyCode === 48 || e.keyCode === 96) {
    //log('Hotkeys', '0 pressed');
    if (!document.querySelector('body.selectbox--open')) {
	//log('Hotkeys', 'subs list not visible');
	openPanel('.player-panel__subs.button.selector');
    } else {
      	history.back();
    }
  }
  if (e.keyCode === 53 || e.keyCode === 101) {
    //log('Hotkeys', '5 pressed');
    if (!document.querySelector('body.selectbox--open')) {
	//log('Hotkeys', 'playlist not visible');
      	openPanel('.player-panel__playlist.button.selector');
    } else {
      	history.back();
    }
  }
  if (e.keyCode === 56 || e.keyCode === 104) {
    //log('Hotkeys', '8 pressed');
    if (!document.querySelector('body.selectbox--open')) {
	//log('Hotkeys', 'audio list not visible');
      	openPanel('.player-panel__tracks.button.selector');
    } else {
      	history.back();
    }
  }
};

Lampa.Player.listener.follow('ready',startHotkeys);
