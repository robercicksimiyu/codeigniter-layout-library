codeigniter-layout-library
==========================
Loading the library in controller
$this->load->library('layout');
or
$this->load->library('layout', array('title_for_layout'=>'test')); //any Layout library variable

$this->layout->render('your_view_file', $data);

coming soon ...
