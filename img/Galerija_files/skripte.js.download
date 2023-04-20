$(document).ready(function () {
  $(".faq-body").hide();
  $(".faq-header").click("function", function () {
    $(".faq-body")
      .hide()
      .css("background", "white")
      .css("padding", "10px")
      .css("text-align", "center")
      .css("text-shadow", "1px 1px 1px");

    $(this).closest(".faq-box").find(".faq-body").slideDown(1000);
  });
});
$(document).ready(function () {
  $("#theme1").click(function () {
    $("body").toggleClass("night");
    $(this).css("display", "none");
    $("#theme2").css("display", "inline-block");
  });
});
$(document).ready(function () {
  $("#theme2").click(function () {
    $("body").toggleClass("night");
    $(this).css("display", "none");
    $("#theme1").css("display", "inline-block");
  });
});
