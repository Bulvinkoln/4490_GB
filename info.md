## Тут будут исходники

cube_fst = Cube.new(center_x: 1, center_y: 4, center_z: 11, edge_size: 3)
# rubocop:disable Lint/UselessAssignment
cube_snd = Cube.new(center_x: 9, center_y: 4, center_z: 11, edge_size: 3)
cube_thd = Cube.new(center_x: 9, center_y: 4, center_z: 11, edge_size: 4)
cube_fth = Cube.new(center_x: 9, center_y: 4, center_z: 11, edge_size: 4)
# rubocop:enable Lint/UselessAssignment
p cube_fst.cubes_list