Kinect2 SDK ���

KinectPose.cs �ȿ� 12�� �ڼ��ν� ���� 

KinectDataAnalyzer.cs �ȿ� FindPose ���� Ű��Ʈ ���̷������κ��� ������ �����ؼ� �ڼ��νĿ� ���

        /// <summary>
        /// 12�� ��ڼ� (BOTH_SIDE_OUT, BOTH_SIDE_UP, BOTH_SIDE_FRONT, BOTH SIDE DOWN, LEFT_HAND_UP, RIGHT_HAND_UP, LEFT_KNEE_UP, RIGHT_KNEE_UP, LEFT_LEG_AB, RIGHT_LEG_AB, SQUAT, CLAP)
        /// </summary>
        /// <param name="skelList"></param>
        /// <returns></returns>
        private int FindPose(ValuePair<List<DateTime>, List<XSkeleton>> skelList)