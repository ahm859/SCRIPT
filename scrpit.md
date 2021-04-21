<script type='text/javascript'>
/*<![CDATA[*/
var idBlog= "878686850506644702";
var idPage= "5476333564144476257"; 
$.ajax({
    dataType: "json",
    url: "https://www.blogger.com/feeds/"+idBlog+"/pages/default/"+idPage+"?alt=json-in-script",
    method: "GET",
    dataType: "jsonp",
    success: function(e) {
        var o, t = $(e.entry.content.$t),
            n = t.find("li"),
            a = t.find("script"),
            l = [];
            $allow = !0, $("body").append(a);
        for (o = 0; o < n.length; o += 1) l.push($(n[o]).text());
        o = window.location.hostname.toLowerCase(), n = window.location.href.toLowerCase();
        var s;
        l.length;
        for (s = 0; s < l.length; s += 1) {
            if (-1 != o.indexOf(l[s])) {
                break
            }
  s == l.length - 1 && $('body *').remove() && $('body').addClass('RE').append("<style>body.RE {background: url(//2.bp.blogspot.com/-do3kTvbcSfk/WrwXWhWRh3I/AAAAAAAAANA/YxjG53tSZTQo3vSCt9KxZ-SPDj5z5jzPQCK4BGAYYCw/s1600/%25D8%25B3%25D9%258A%25D9%2588%25D8%25A8%25D9%2584%25D8%25B3.png) no-repeat center #eee;background-position: center center;height: 98vh;}</style>")
        }
    }
});
/*]]>*/
</script>
