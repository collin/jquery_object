jQuery.clone = function(obj) {
  var _Object = {
    clone: function(obj) {
      function F(o) { _.extend(this, o); }
      F.prototype = this;
      return new F(obj);
    }
  };
  
  return _Object.clone(obj);
}
