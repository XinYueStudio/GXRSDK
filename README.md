# GXRSDK
GXRSDK  is for vr  device use for develop vr application on any plaform 

![GXR SDK](https://user-images.githubusercontent.com/15990821/114167119-25346400-9961-11eb-9676-d5d1059a03ff.png)

# GSXRPluginSamples

Copyright : Copyright (c) China Mobile Communications Group Co.,Ltd, and its affiliates. All rights reserved.

Your use of this SDK or tool is subject to the GSXR SDK License Agreement, available at
https://www.github.com/licenses/gsxrsdk/
Unless required by applicable law or agreed to in writing, the Utilities SDK distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF
ANY KIND, either express or implied. See the License for the specific language governing
permissions and limitations under the License.

GSXR_SDK在Unity引擎的实现方式， 使用GSXRPlugin(以下简称SDK)
制作运行在适配了General Standard for XR (以下简称GSXR)标准的XR设备上的
XR应用。GSXRPlugin主要包含：头部组件、手部组件和扩展多追踪器组件。
每个组件都会包含定位模块，以及不同的交互方式。特殊之处是，头部组件还会
包含图像模块，手部组件可以动态加载不同终端设备的模型。


## Supported Plaforms and Low-Level Graphics APIs

| Platform                                                                                                                                        | D3D11              | D3D12                    |  OpenGL/GLES                                 | Vulkan                 | Metal                                     |  Build Status                    |
| ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |------------------- | ------------------ | ------------------------------- | ------------------------------- | -------------------------------- |
  :heavy_check_mark: <sup>1</sup>  Android                                          | -                       | -                              |:heavy_check_mark: <sup>2</sup> |                            |                                                |  :heavy_check_mark: <sup>1</sup>       |




##QualitySettings vSyncCount

| Don't Sync                                                                                                                                   |  Every V Blank  | Every Second V Blank|
| -----------------------------------------------------------------------------------------------------|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
:heavy_check_mark: <sup>1</sup>                                                                                            | -                        | -                                                                                                                                                                                                                                                                        |




##Minimum API level Recommended Setting

| AndroidSDK            |
|------------------------|
  :heavy_check_mark: <sup>1</sup>  >=AndroidApiLevel26|


##Target Architectures

| AndroidArchitecture   |           |
| ---------------------------------------------------------|----------------------------------------------------------------------|
 :heavy_check_mark: <sup>1</sup> ARMv7 | :heavy_check_mark: <sup>1</sup> ARM64 |


##Unity 2019.3x Template

|  Unity Version |  2D   |  3D                             |  3D Width Extras                |  Hight-Definition RP      | Universal RenderPipeline        |
| ---------------|-------|---------------------------------|---------------------------------|---------------------------|---------------------------------|
|  Unity2019.3x    | -     | :heavy_check_mark: <sup>1</sup> | :heavy_check_mark: <sup>1</sup> |-                          | :heavy_check_mark: <sup>1</sup> | 

 				   
##Unity 2020 Template

|  Unity Version |  2D   |  3D                             |  3D Width Extras                |  Hight-Definition RP      | Universal RenderPipeline        |
| ---------------|-------|---------------------------------|---------------------------------|---------------------------|---------------------------------|
|  Unity2020x    | -     | :heavy_check_mark: <sup>1</sup> | :heavy_check_mark: <sup>1</sup> |-                          | :heavy_check_mark: <sup>1</sup> | 

##Unity 2021 Template

|  Unity Version |  2D   |  3D                             |  3D Width Extras                |  Hight-Definition RP      | Universal RenderPipeline        |
| ---------------|-------|---------------------------------|---------------------------------|---------------------------|---------------------------------|
|  Unity2021x    | -     | :heavy_check_mark: <sup>1</sup> | :heavy_check_mark: <sup>1</sup> |-                          | :heavy_check_mark: <sup>1</sup> | 
