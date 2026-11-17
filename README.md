

        title = new JLabel("Student Enrollment System");
        title.setFont(new Font("Dialog", Font.BOLD, 20));
        title.setBounds(125, 25, 400, 30);
        add(title);

        area = new JTextArea();
        area.setEditable(false);
        area.setFont(new Font(Font.MONOSPACED, Font.PLAIN, 13));

        label = new JLabel("Enter Student Name");
        label.setFont(new Font("Dialog", Font.BOLD, 15));
        label.setBounds(20, 58, 200, 25);
        label.setBounds(20, 60, 165, 25);
        add(label);

        txt = new JTextField();
        txt.setFont(new Font("Dialog", Font.PLAIN, 15));
        txt.setBounds(20, 84, 390, 32);
        txt.setBounds(190, 57, 420, 32);
        add(txt);

        scroll = new JScrollPane(area);
        scroll.setBounds(20, 132, 390, 278);
        scroll.setBounds(175, 110, 455, 305);
        add(scroll);

        enroll = new JButton("Enroll");
        enroll.setBounds(425, 132, 180, 38);
        enroll.setBounds(20, 110, 140, 40);
        add(enroll);

        withdraw = new JButton("Withdraw");
        withdraw.setBounds(425, 182, 180, 38);
        withdraw.setBounds(20, 165, 140, 40);
        add(withdraw);

        done = new JButton("Mark as LOA");
        done.setBounds(425, 232, 180, 38);
        done.setBounds(20, 220, 140, 40);
        add(done);

        view = new JButton("View Enrolled");
        view.setBounds(425, 282, 180, 38);
        view.setBounds(20, 275, 140, 40);
        add(view);

        enroll.addActionListener(this);
        txt.addActionListener(this);
        withdraw.addActionListener(this);
        done.addActionListener(this);
        view.addActionListener(this);
    }

    @Override
    public void actionPerformed(ActionEvent e) {
