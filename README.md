# TheCodingBrotha
$.ajax({
  type: 'GET',
  url: 'https://wakatime.com/share/@2e5ac7e9-8439-4484-bfc0-262ab5940fa6/577c9000-b24c-423c-805f-9a7e76b0bfb2.json',
  dataType: 'jsonp',
  success: function(response) {
    console.log(response.data);
  },
});
