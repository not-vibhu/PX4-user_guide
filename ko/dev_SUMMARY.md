# 요약

* [소개](README.md)
* [시작하기](setup/getting_started.md)
  * [초기 설정](setup/config_initial.md)
  * [툴체인 설치](setup/dev_env.md)
    * [Mac OS](setup/dev_env_mac.md)
    * [리눅스](setup/dev_env_linux.md)
      * [Ubuntu/Debian 리눅스](setup/dev_env_linux_ubuntu.md)
      * [CentOS 리눅스](setup/dev_env_linux_centos.md)
      * [Arch 리눅스](setup/dev_env_linux_arch.md)
      * [고급 리눅스](setup/dev_env_advanced_linux.md)
    * [윈도우](setup/dev_env_windows.md)
      * [Cygwin 툴체인](setup/dev_env_windows_cygwin.md)
      * [가상 머신 툴체인](setup/dev_env_windows_vm.md)
      * [윈도우용 배시 툴체인](setup/dev_env_windows_bash_on_win.md)
    * [비주얼 스튜디오 코드 IDE](setup/vscode.md)
    * [Fast RTPS 설치](setup/fast-rtps-installation.md)
    * [추가 도구](setup/generic_dev_tools.md)
  * [코드 작성](setup/building_px4.md)
  * [첫 프로그램 작성](apps/hello_sky.md)
  * [프로그램/모듈 서식](apps/module_template.md)
* [개념](concept/README.md)
  * [PX4 구성 개요](concept/architecture.md)
    * [조종 장치 구성도](flight_stack/controller_diagrams.md)
  * [드론코드 플랫폼 개요](concept/dronecode_architecture.md)
  * [비행 모드](concept/flight_modes.md)
  * [비행 동작](concept/flight_tasks.md)
  * [믹서와 액추에이터](concept/mixing.md)
    * [개별 탑재 장치 믹서](concept/custom_mixer_payload.md)
  * [PWM limit 상태 머신](concept/pwm_limit.md)
  * [시스템 시작](concept/system_startup.md)
  * [SD 카드 배치](concept/sd_card_layout.md)
* [시뮬레이션](simulation/README.md)
  * [jMAVSim 모의 시험 환경](simulation/jmavsim.md)
    * [jMAVSim 다중 비행체 모의시험](simulation/multi_vehicle_jmavsim.md)
  * [가제보 모의 시험 환경](simulation/gazebo.md)
    * [가제보 기체](simulation/gazebo_vehicles.md)
    * [가제보 월드(world)](simulation/gazebo_worlds.md)
    * [가제보 다중 기체 모의시험](simulation/multi_vehicle_simulation_gazebo.md)
  * [플라이트기어 모의 시험 환경](simulation/flightgear.md)
    * [플라이트기어 기체](simulation/flightgear_vehicles.md)
    * [플라이트기어 다중 기체 모의시험](simulation/multi_vehicle_flightgear.md)
  * [JSBSim 모의 시험 환경](simulation/jsbsim.md)
  * [AirSim 모의 시험 환경](simulation/airsim.md)
  * [다중 기체 모의 시험](simulation/multi-vehicle-simulation.md)
  * [안전 장치 모의 시험](simulation/failsafes.md)
  * [HITL 모의 시험](simulation/hitl.md)
  * [하드웨어 모의 시험](simulation/simulation-in-hardware.md)
* [하드웨어](hardware/README.md)
  * [비행체 제어 장치 참고 설계](hardware/reference_design.md)
  * [제조사 보드 지원 안내](hardware/board_support_guide.md)
  * [비행체 제어 장치 이식 안내](hardware/porting_guide.md)
    * [NuttX 보드 이식 안내](hardware/porting_guide_nuttx.md)
  * [기체프레임](airframes/README.md)
    * [기체프레임 참고 자료](airframes/airframe_reference.md)
    * [새 기체프레임 추가](airframes/adding_a_new_frame.md)
  * [장치 드라이버](middleware/drivers.md)
  * [텔레메트리 무선 통신](data_links/telemetry.md)
    * [SiK 무선 통신](data_links/sik_radio.md)
  * [센서, 액츄에이터 입출력](sensor_bus/README.md)
    * [I2C 버스](sensor_bus/i2c.md)
    * [UAVCAN 버스](uavcan/README.md)
      * [UAVCAN 부트로더](uavcan/bootloader_installation.md)
      * [UAVCAN 펌웨어 업그레이드](uavcan/node_firmware.md)
      * [UAVCAN 구성](uavcan/node_enumeration.md)
      * [UAVCAN 기타 참고사항](uavcan/notes.md)
    * [UART/직렬 포트](uart/README.md)
      * [설정 가능 직렬 포트 드라이버](uart/user_configurable_serial_driver.md)
  * [RTK GPS](advanced/rtk_gps.md)
  * [짐벌 \(마운트\) 제어 설정](advanced/gimbal_control.md)
  * [보조 컴퓨터](companion_computer/pixhawk_companion.md)
* [미들웨어](middleware/README.md)
  * [uORB 메시징](middleware/uorb.md)
  * [MAVLink 메시징](middleware/mavlink.md)
  * [RTPS/ROS2 인터페이스](middleware/micrortps.md)
    * [메시지 처리 시험](middleware/micrortps_throughput_test.md)
    * [클라이언트/에이전트 직접 생성](middleware/micrortps_manual_code_generation.md)
* [모듈과 명령](middleware/modules_main.md)
  * [명령](middleware/modules_command.md)
  * [통신](middleware/modules_communication.md)
  * [조종 장치](middleware/modules_controller.md)
  * [드라이버](middleware/modules_driver.md)
    * [항속 센서](middleware/modules_driver_airspeed_sensor.md)
    * [기압 센서](middleware/modules_driver_baro.md)
    * [거리 센서](middleware/modules_driver_distance_sensor.md)
    * [관성 센서](middleware/modules_driver_imu.md)
    * [지자기 센서](middleware/modules_driver_magnetometer.md)
  * [추정자](middleware/modules_estimator.md)
  * [모의 시험](middleware/modules_simulation.md)
  * [시스템](middleware/modules_system.md)
  * [서식](middleware/modules_template.md)
* [로보틱스](robotics/README.md)
  * [리눅스에서의 외부 제어](ros/offboard_control.md)
  * [ROS](ros/README.md)
    * [MAVROS \(ROS용 MAVLink\)](ros/mavros_installation.md)
    * [MAVROS 외부 제어 예제](ros/mavros_offboard.md)
    * [가제보 모의 시험 환경의 ROS](simulation/ros_interface.md)
    * [ROS의 OctoMap 모델](simulation/gazebo_octomap.md)
    * [라즈베리 파이로의 ROS 설치](ros/raspberrypi_installation.md)
    * [외부 위치 추정 (시각/움직임 기반)](ros/external_position_estimation.md)
    * [MAVROS에서의 개별 메시지 전송](ros/mavros_custom_messages.md)
  * [드론키트](robotics/dronekit.md)
* [디버깅/로깅](debug/README.md)
  * [자주 묻는 질문](debug/faq.md)
  * [콘솔/셸](debug/consoles.md)
    * [MAVLink 셸](debug/mavlink_shell.md)
    * [시스템 콘솔](debug/system_console.md)
  * [SWD/JLink 디버깅 인터페이스](debug/swd_debug.md)
  * [오토파일럿 디버깅](debug/gdb_debugging.md)
  * [Eclipse/JLink 하드웨어 디버깅](debug/eclipse_jlink.md)
  * [센서/토픽 디버깅](debug/sensor_uorb_topic_debugging.md)
  * [모의 시험 디버깅](debug/simulation_debugging.md)
  * [디버깅 값 전송](debug/debug_values.md)
  * [시스템 범위 재현](debug/system_wide_replay.md)
  * [프로파일링](debug/profiling.md)
  * [로깅](log/logging.md)
  * [비행 로그 분석](log/flight_log_analysis.md)
  * [ULog 파일 형식](log/ulog_file_format.md)
* [자습서](tutorials/tutorials.md)
  * [지상 통제 장치](qgc/README.md)
  * [Odroid C1에서 QGC로의 동영상 스트리밍 전송](qgc/video_streaming.md)
  * [장거리 동영상 스트리밍 전송](qgc/video_streaming_wifi_broadcast.md)
  * [리눅스에서 원격 조종 수신 모듈 연결](tutorials/linux_sbus.md)
* [고급 주제](advanced/README.md)
  * [매개변수와 설정](advanced/parameters_and_configurations.md)
  * [매개변수 참고서](advanced/parameter_reference.md)
  * [컴퓨터 비전](advanced/computer_vision.md)
    * [움직임 감지(VICON, 광추적)](tutorials/motion-capture-vicon-optitrack.md)
  * [인텔 리얼센스 R200 드라이버 설치](advanced/realsense_intel_driver.md)
  * [상태 추정자 전환](advanced/switching_state_estimators.md)
  * [별도 모듈](advanced/out_of_tree_modules.md)
  * [STM32 부트로더](software_update/stm32_bootloader.md)
  * [시스템 알림음](advanced/system_tunes.md)
* [플랫폼 시험과 지속 통합](test_and_ci/README.md)
  * [시험 비행](test_and_ci/test_flights.md)
    * [시험 MC_01 - 수동 상태](test_cards/mc_01_manual_modes.md)
    * [시험 MC_02 - 완전 자동화](test_cards/mc_02_full_autonomous.md)
    * [시험 MC_03 - 자동 / 수동 혼합](test_cards/mc_03_auto_manual_mix.md)
    * [시험 MC_04 - 안전 장치 시험](test_cards/mc_04_failsafe_testing.md)
    * [시험 MC_05 - 실내 비행 (수동 상태)](test_cards/mc_05_indoor_flight_manual_modes.md)
  * [단위 테스트](test_and_ci/unit_tests.md)
  * [지속 통합](test_and_ci/continous_integration.md)
  * [젠킨스 지속 통합](test_and_ci/jenkins_ci.md)
  * [ROS 통합 테스트](test_and_ci/integration_testing.md)
  * [MAVSDK 통합 테스트](test_and_ci/integration_testing_mavsdk.md)
  * [도커 컨테이너](test_and_ci/docker.md)
  * [유지 관리](test_and_ci/maintenance.md)
* [기여(및 유선 개발 미팅)](contribute/README.md)
  * [유선 개발 미팅](contribute/dev_call.md)
  * [소스 코드 관리](contribute/code.md)
    * [git 예제](contribute/git_examples.md)
  * [문서](contribute/docs.md)
  * [번역](contribute/translation.md)
  * [용어/표기](contribute/notation.md)
  * [라이선스](contribute/licenses.md)
* [지원](contribute/support.md)

## 드론코드 관련 링크

* [PX4 사용자 안내서](https://docs.px4.io/master/en/)
* [QGroundControl 사용자 안내서](https://docs.qgroundcontrol.com/en/)
* [QGroundControl 개발자 안내서](https://dev.qgroundcontrol.com/en/)
* [MAVLink 안내서](https://mavlink.io/en/)
* [MAVSDK](https://mavsdk.mavlink.io/develop/en/index.html)
* [드론코드 카메라 관리자](https://camera-manager.dronecode.org/en/)
