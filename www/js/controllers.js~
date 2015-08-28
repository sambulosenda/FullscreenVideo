angular.module('starter.controllers', [])
.controller('DashCtrl', function($scope) {
})

.controller('PoemCtrl', function($scope) {
 $scope.bg = 'img/ionic.png';
 $scope.clipSrc = '/android_asset/www/video/poem1.mp4'

 var video = document.getElementById("myvideo");
  if (video.requestFullscreen) {
    video.requestFullscreen();
  } else if (video.msRequestFullscreen) {
    video.msRequestFullscreen();
  } else if (video.mozRequestFullScreen) {
    video.mozRequestFullScreen();
  } else if (video.webkitRequestFullscreen) {
    video.webkitRequestFullscreen();
  }
});
