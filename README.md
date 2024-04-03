# Team: 100만 버튜버  
* Members
  | Name | Role |
  |----|----|
  | 김정문 | Project leader, 프로젝트를 총괄하고 망하면 책임진다. |
  | 신현택 | Projecy Member, 리더와 매니저의 스케쥴 관리를 잘 따라 프로젝트를 진행한다 |
  | 임민우 | Project Manager, 프로젝트의 진행 상황을 관리한다. |

* 발표자료 : https://github.com/kgkorchamhrd/intel-02/blob/main/doc/project/team1/presentation.ppt

# Project Virtual_Character

* (간략히 프로젝트를 설명하고, 최종 목표가 무엇인지에 대해 기술)
Pose Estimate, Face Tracking과 목소리 변환 AI를 이용하여 3D 모델을 컨트롤하는 프로그램을 만드는 것이 최종 목표

## High Level Design

* (프로젝트 아키텍쳐 기술, 전반적인 diagram 으로 설명을 권장)
<img src="https://github.com/kgkorchamhrd/intel-02/blob/main/doc/project/team1/design.png" width=400 height=500>

## Clone code

* (각 팀에서 프로젝트를 위해 생성한 repository에 대한 code clone 방법에 대해서 기술)

```shell
git clone https://github.com/JEONGMOONKIM/VR_C
```

## Prerequite

* (프로잭트를 실행하기 위해 필요한 dependencies 및 configuration들이 있다면, 설치 및 설정 방법에 대해 기술)

```shell
python -m venv .VR_C
source .VR_C/bin/activate
pip install -r requirements.txt
```

## Steps to build

* (프로젝트를 실행을 위해 빌드 절차 기술)

```shell
cd ~/xxxx
source .venv/bin/activate

make
make install
```

## Steps to run

* (프로젝트 실행방법에 대해서 기술, 특별한 사용방법이 있다면 같이 기술)

```shell
cd ~/xxxx
source .venv/bin/activate

cd /path/to/repo/xxx/
python demo.py -i xxx -m yyy -d zzz
```

## Output

* (프로젝트 실행 화면 캡쳐)


## Appendix

* (참고 자료 및 알아두어야할 사항들 기술)
