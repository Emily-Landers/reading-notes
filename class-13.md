# The Past, Present, and Future of Local Storage for Web Applications
- UserData allows web pages to store up to 64 KB of data per domain
- HTML5 storage is a way for web pages to store named key/value pairs locally
- the data remains after you navigate away from the web site
- HTML5 is supported on IE, Firefox, Safari, Chrome, Opera, Iphone, and Android
- to check for HTML5 storage: ```function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}```
- Web SQL databases are supported by IE, Firefox, Safari, Chrome, Opera, Iphone, and Android
- SQL database allows you to do things like ```openDatabase('documents', '1.0', 'Local document storage', 5*1024*1024, function (db) {
  db.changeVersion('', '1.0', function (t) {
    t.executeSql('CREATE TABLE docids (id, name)');
  }, error);
});``` from JavaScript