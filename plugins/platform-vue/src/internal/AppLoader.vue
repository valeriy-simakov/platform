<!--
// Copyright © 2020 Anticrm Platform Contributors.
// 
// Licensed under the Eclipse Public License, Version 2.0 (the "License");
// you may not use this file except in compliance with the License. You may
// obtain a copy of the License at https://www.eclipse.org/legal/epl-2.0
// 
// Unless required by applicable law or agreed to in writing, software
// distributed under the License is distributed on an "AS IS" BASIS,
// WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
// 
// See the License for the specific language governing permissions and
// limitations under the License.
-->

<template>
  <div class="sk-cube-grid">
    <div class="sk-cube sk-cube1"></div>
    <div class="sk-cube sk-cube2"></div>
    <div class="sk-cube sk-cube3"></div>
    <div class="sk-cube sk-cube4"></div>
    <div class="sk-cube sk-cube5"></div>
    <div class="sk-cube sk-cube6"></div>
    <div class="sk-cube sk-cube7"></div>
    <div class="sk-cube sk-cube8"></div>
    <div class="sk-cube sk-cube9"></div>
  </div>
</template>

<style>
.sk-cube-grid {
  width: 40px;
  height: 40px;
  margin: 45vh auto;

  animation: sk-cubeGridOpacity 1s 1;
}

@keyframes sk-cubeGridOpacity {
  0%,
  30% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

.sk-cube-grid .sk-cube {
  width: 33%;
  height: 33%;
  background-color: #999;
  float: left;
  animation: sk-cubeGridScaleDelay 1.3s infinite ease-in-out;
}
.sk-cube-grid .sk-cube1 {
  animation-delay: 0.2s;
}
.sk-cube-grid .sk-cube2 {
  animation-delay: 0.3s;
}
.sk-cube-grid .sk-cube3 {
  animation-delay: 0.4s;
}
.sk-cube-grid .sk-cube4 {
  animation-delay: 0.1s;
}
.sk-cube-grid .sk-cube5 {
  animation-delay: 0.2s;
}
.sk-cube-grid .sk-cube6 {
  animation-delay: 0.3s;
}
.sk-cube-grid .sk-cube7 {
  animation-delay: 0s;
}
.sk-cube-grid .sk-cube8 {
  animation-delay: 0.1s;
}
.sk-cube-grid .sk-cube9 {
  animation-delay: 0.2s;
}

@-webkit-keyframes sk-cubeGridScaleDelay {
  0%,
  70%,
  100% {
    transform: scale3D(1, 1, 1);
  }
  35% {
    transform: scale3D(0, 0, 1);
  }
}

@keyframes sk-cubeGridScaleDelay {
  0%,
  70%,
  100% {
    transform: scale3D(1, 1, 1);
  }
  35% {
    transform: scale3D(0, 0, 1);
  }
}
</style>
